# Lab 2 Pendulum Week 1
---

### Required Materials:

::: Materials
- String, twine, ribbon, or some other type of long, thin, flexible structure for tying and supporting
- A pair of scissors
- Somewhere to hang your pendulum, *e.g.*, shower curtain rod, broomstick across two chairs, taped to a dining room table, etc.
- Phyphox &ldquo;Acceleration without g.&rdquo;
- Pillow, couch cushion, or something similar
:::

### Suggested Additional Materials:

::: Materials
- Toilet paper roll or something similar
- A rubber band or some other elastic material
- Measuring tape
- Tape
:::

### Lab Goals:

- **Construct an apparatus** 
	- Devise a method of suspending your phone
	- Find a place to **safely** hang your phone
- **Data Analysis**
	- Understand the theory behind Simple Harmonic Motion
	- Understand the relationship between period and length
	- Develop the equations from Newton's equations of motion to verify your data

---

# Theory: Simple Harmonic Motion

## 1. Review

Simple harmonic motion is characterized by a system whose acceleration is *negatively proportional* to its position. This is expressed in following differential equation:

:::Equation harmonicDiffEq
$$
a = \frac{d^2 x}{dt^2} = -\Omega^2 x
$$
:::

where $x$ is the coordinate for position, $\Omega^2$ is the constant of proportionality, and $\Omega$, by itself, is known as the angular frequency and is defined as the following:

:::Equation omega
$$
\Omega = \frac{2 \pi}{T}
$$
:::

where $T$ is the period of the oscillator. 
 
::: Note
We have not made any mention to what type of oscillator this describes. It could be a pendulum, a ball in bowl, a mass on a spring, etc. This definition of $\Omega$ is true for all simple harmonic oscillators.
:::

You may have seen [Eq](#Eq-harmonicDiffEq) solved in a lecture class before. We won&rsquo;t go through the derivation here, but we will remind you that the solution for the position $x$ as function of time  $t$ is given in [Eq](#Eq-harmonicSol) below. 
 
:::Equation harmonicSol
$$
x = x\small_{0}\normalsize\cos (\Omega t)
$$
:::

where $x\small_{0}\normalsize$ is the amplitude of the periodic motion, but also marks the initial position. 

## 2. Simple Pendulum
[comment]: # (Period is to the length of the pendulum--use this?)

:::Figure
![Picture of Pendulum](../imgs/lab2/Pendulum.png)
:::

A simple pendulum consists of a point mass at the end of a massless string of length $L$. A simple pendulum that is released from a small initial angle ($15 ^{\circ}$ or less) exhibits simple harmonic motion. The angular position $\theta$ follows Equation 1. That is to say:

:::Equation angularHarmDiffEq
$$
\alpha = \frac{d^2 \theta}{dt^2} = -\Omega^2 \theta = -\frac{g}{L} \theta
$$
:::

You may also recall that for a simple pendulum $\Omega = \sqrt{\frac{g}{L}}$, where $g$ is the acceleration due to gravity and $L$ is the length of the pendulum. This has been inserted in Equation 4 above.

Lastly, this means that angular position $\theta$ of the pendulum is given by:

:::Equation pendSol
$$
\theta = \theta\small_{0}\normalsize \cos (\Omega t)
$$
:::

:::Question
Use the information above and [Eq](#Eq-omega) to write an equation for the period of the pendulum in terms of $g$ and $L$.
:::

## 3. Circular Motion

In this experiment you will be using your phone to measure accelerations. Therefore we should discuss what types of accelerations your phone will undergo as it swings back and forth. In a pendulum, the motion of the mass (your phone) moves on an arc of a circle. Therefore we can use our knowledge of circular motion. 

Objects moving in a circle are said to have angular velocity, denoted as $\omega$. This angular velocity is defined as the rate of change of the angular position.

:::Equation angVel
$$
\omega = \frac{d \theta}{dt}
$$
:::

Recall from Physics 2 that the acceleration an object experiences when it moves in an arc or circle at varying speed, has two components. One component points in the radial direction (towards the pivot). We will call it $a\small_{rad}\normalsize$ or $a\small_{r}\normalsize$ for short. The other component points in the direction of motion tangent to the circle. This is sometimes called $a\small_{tan}\normalsize$ but for this lab we will call it $a\small_{\theta}\normalsize$.

:::Figure
![Picture of Pendulum](../imgs/lab2/acceleration3.png)
:::

The equation for both of the accelerations is given below:

:::Equation radialAcc
$$
a\small_{r}\normalsize = r \omega^2 = r  \left ( \frac{d \theta}{dt} \right )^2
$$
:::

<!-- a\small_{r}\normalsize = L\omega^{2}\theta_{0}^{2}\sin^{2}(\omega t) -->

:::Equation tangAcc
$$
a\small_{\theta}\normalsize = r \alpha = r  \frac{d^2 \theta}{dt^2}
$$
:::

# Calculations

## 1. The Experiment

In this lab you will turn your phone into a pendulum. You will suspend it in some way (we provide some ideas below) and then use the &ldquo;Accelerometer without g&rdquo; to measure the phone&rsquo;s acceleration along all three axes while your phone swings back and forth. Figure 3 shows one such setup. We will use the acceleration data to measure the period of the pendulum.

:::Figure
![Phone Swinging Image](../imgs/lab2/phonePendulumGif.gif)
:::

## 2. Relationship Between the Period of Acceleration and the Period of Position

Typically, when measuring the period of the pendulum, you would measure the *angular position* as a function of time. Then from those data you would calculate the period of the pendulum.

:::Note
The Phyphox app *can't measure position* but it *can measure acceleration*. Therefore we need to determine the relationship between the period of the acceleration and the period of the angular position.
:::

:::Figure pendAccgif
![Gif  of pendulum moving](../imgs/lab2/accelerationgif.gif)
:::

Since we are measuring the period of the acceleration and not the angular position, we need to understand the relationship between the two. In [Fi](#Fi-pendAccgif) you can see how the **net acceleration** vector changes with time. Notice that this change is periodic. Also notice that at the bottom of the swing the acceleration is pointed entirely radially, and at the top of the swing it is pointed entirely tangentially. 

This indicates that both $a\small_{r}\normalsize$ and $a\small_{\theta}\normalsize$ have some sort of periodic behavior, but it is not a given that the period of either acceleration would match that of the angular position. We can get some intuition by watching the animation, however. Notice that it takes one full swing of the pendulum for $a\small_{\theta}\normalsize$ to point in the same direction, while $a\small_{r}\normalsize$ points radially twice in one full swing.

::::::Exercise
Assume that the angular position of the pendulum is given by [Eq](#Eq-pendSol) above.

:::Question
Derive the equation for the radial acceleration of the pendulum $a\small_{r}\normalsize$ as a function of time by using [Eq](#Eq-pendSol) and [Eq](#Eq-radialAcc). Show your work.
:::

:::Question
Derive the equation for the radial acceleration of the pendulum $a\small_{\theta}\normalsize$ as a function of time by using [Eq](#Eq-pendSol) and [Eq](#Eq-tangAcc). Show your work.
:::

Now you should know that both the radial and tangential accelerations are periodic. Let's put this all together to see how the periods of these two functions relate to the thing we care about, the period of the angular position.

:::Question

Using the equations you just derived and [Eq](#Eq-omega) you can get the periods for both the radial and tangential accelerations. Use these periods and your response to Question 1 to answer the following questions.

1. What is the relationship between the period of $a\small_{r}\normalsize$ and the period of the angular position? **Hint:** To find the period of $\sin^2 (x)$, us the identity involving cosine of the double angles: $\sin^2 (x) = (1-\cos (2x))/2$

2. What is the relationship between the period of $a\small_{\theta}\normalsize$ and period of the angular position?

3. Which should you use to measure the period of the angular position of the pendulum?
:::

Recall that the radial acceleration vector always points towards the pivot. The tangential acceleration points in the direction of motion (tangent to the circular arc). 

Figure 5 shows how the coordinate system for your accelerometer moves with your phone. 

:::Figure
![Phone Swinging Diagram](../imgs/lab2/PhonePendulum.png)
:::

::: Question
Build a list that identifies which axis of your accelerometer is the long, short, and screen axis, and which of the two correlate to the $a\small_{r}\normalsize$ and $a\small_{\theta}\normalsize$ vectors. 

This is just an example: 

Long Axis is x = $a\small_{r}\normalsize$, etc.
:::
::::::


## 3. Is Your Phone a Simple Pendulum?

So far, most of our discussion has been based on a simple pendulum, which consists of a point mass at the end of a massless string.

Your phone is not a point mass, but are we able to treat it as one? The answer is yes, but only under certain conditions. 

You were taught in Physics 2 [fn]Hopefully[/fn] that for a physical pendulum (not a simple pendulum), the angular frequency is given by:

::: Equation physicalOmega
$$
\Omega = \sqrt{\frac{mgL}{I}}
$$
:::

Where $I$ is the moment of inertia of the mass around the axis of rotation.

:::::: Exercise

:::Question
Verify that when we use the moment of inertia for a simple pendulum (point mass), we obtain the $\Omega$ we expect.
:::

To find the moment of inertia of your phone around the pivot point we will need to do two things.

1. First, we will assume that your phone has the same moment of inertia as a bar rotating about its center. This is given by:


:::Equation
$$
I\small_{phone-cm}\normalsize = \frac{1}{12}ml^2
$$
:::

where $l$ is the length of one of the (long) edges of your phone.

1. The equation for $I\small_{phone-cm}\normalsize$ works only for rotating your phone about its **center of mass**. For our setup, your phone will not be rotating about its center of mass, but about the pivot of the pendulum. To get the moment of inertia about the pivot we will have to apply the [parallel axis theorem](https://en.wikipedia.org/wiki/Parallel_axis_theorem#Mass_moment_of_inertia) [fn]The parallel axis theorem states that the moment of inertia about some point is given by $I = I_{cm} + md^2$ where $d$ is the distance between the point and the center of mass. In our case, $d=L$[/fn]. When the phone is swinging about a pivot distance $L$ away, you find:

:::Equation
$$
I\small_{phone}\normalsize = \frac{1}{12}ml^2 +mL^2
$$
:::

3. Now that you have the moment of inertia for your phone, plug it into [Eq](#Eq-physicalOmega).
4. Factor out $mL^2$ from the denominator. 

:::Question
1. Under what conditions does your phone behave as a simple pendulum? **Hint: Consider the ratio of $\frac{l}{L}$.**

2. If your phone had a length of 8 cm and the pendulum a length of 50 cm, what would be the percent difference between the period of an ideal simple pendulum of 50 cm, and that of your phone pendulum.
:::
::::::


<!---##### Background
A period is the time it takes for one cycle in a repeating event. It is the time for which the event repeats itself. A pendulum at rest is considered to be in equilibrium. Once the pendulum is displaced, it oscillates about the equilibrium position. The duration of time from the position of displacement after it is released and back to that position is the period.

We want to make the correction term (the term due to rotation) as small as possible so given that your phone is X cm long, what length of string would you like to make your pendulum?)--->


# Building an Apparatus

:::Note
DISCLAIMER - You will be using your phone to take data, and this can sometimes lead to accidents. **Please use due care in handling your phone during this experiment.**
:::

::::::Exercise

<!---[INSERT ANIMATED GIF HERE]--->
:::LFigure
![Carpet Pendulum](../imgs/lab2/CarpetPendulum.gif)
:::

:::RFigure
![Bathroom Pendulum](../imgs/lab2/BathroomPendulum.gif)
:::


In this experiment you will be using your phone to measure the acceleration in the x, y, and z axes without gravity. You will build an apparatus and take data. Include a picture of your setup if you can!

While you may be able to achieve a pendulum without them, we recommend using the additional materials as well. This guide will assume that you have them.

:::Figure
![Suggested Materials](../imgs/lab2/IMG_0713.jpg)
:::


1. Find the cardboard tube from a toilet paper roll and flatten it.  
<!---:::Figure:Figure![Suggested Materials](imgs/IMG_0710.jpg):::--->

2. Mark the width of your phone on both sides of the flattened tube.
<!---:::Figure:Figure![Suggested Materials](imgs/IMG_0712.jpg):::--->

3. Make a cut, approximately 4 mm deep, at each mark you made with your phone. Cut from one mark to the other, along the length of the roll, to complete the cutout. Do this on both sides.

:::Figure
![Suggested Materials](../imgs/lab2/IMG_0716.jpg)
:::

4. Poke holes in each of the corners of the flattened roll, leaving enough space along the edge that you don’t rip out to the edge.

:::Figure
![Suggested Materials](../imgs/lab2/IMG_0720.jpg)
:::

<!---:::Figure:Figure![Suggested Materials](imgs/IMG_0724.jpg):::--->

:::Figure
![Suggested Materials](../imgs/lab2/IMG_0726.jpg)
:::

5.  Now cut a long length of string. Make sure you leave a lot of slack, too. This string will run through the width edge, run underneath the roll, then back through and up the other width edge hole.

:::Figure
![Suggested Materials](../imgs/lab2/IMG_0727.jpg)
:::

6.  Insert your phone into the slot you have cut, with the string ends on the same side as your phone face. Put a rubber band, or something else elastic, around one end of the phone (while the roll is at that end). Slide the roll and elastic band to the other side, so you can fit it around there too. This will secure your phone even better.

:::Figure
![Suggested Materials](../imgs/lab2/3N1.jpeg)
:::


7.  Now find something from which to hang your string. I have used both a shower frame and a broom handle set between two chairs.

:::Figure
![Suggested Materials](../imgs/lab2/IMG_0695.jpg)
:::

:::Figure
![Suggested Materials](../imgs/lab2/IMG_0703.jpg)
:::


8. If your phone is not level, try corrective measures.

:::Figure
![Suggested Materials](../imgs/lab2/IMG_0700.jpg)
:::

:::Figure
![Suggested Materials](../imgs/lab2/IMG_8007.jpg)
:::

Note: I added tape after the second photo to ensure that everything would stay in place.

:::Question
Include a photo of your apparatus. **Hint:** Your phone does not need to be included in the picture.
:::


::::::


# Conclusion
::: Exercise
1. Describe the experiment you will be performing next week.

2. Briefly state how the acceleration you will measure will be related to the period of the pendulum.

3. Summarize how using your phone as the bob affects your pendulum.
:::