# Lab 2 Pendulum Week 1
---

### All Materials Needed:

- String, twine, ribbon, or some other type of long, thin, flexible structure for tying and supporting.
- A pair of scissors.
- Someplace to hang your pendulum i.e. shower curtain rod, broomstick across two chairs, taped to a dining room table, etc.
- Phyphox "Acceleration without g”
- Pillow, couch cushion, or something similar.

##### Suggested Additional Materials:
- Toilet paper roll or something similar.
- A rubber band or some other elastic material.
- Tape.

### Lab Goals:

- **Construct an apparatus** 
	- Find a place to **safely** hang your phone.
	- Construct a way of hanging your phone.
- **Data Analysis**
	- Understand the theory of Simple Harmonic Motion.
	- Understand the relationship between period and length.
	- Develop the equations from Newton's equations of motion to verify your data.

---

## Part I: Simple Harmonic Motion

## 1. Review

Simple harmonic motion is characterized by a system whose acceleration is negatively proportional to its position. That is two say that it follows this differential equation:

:::Figure:Equation
$$
a = \frac{d^2 x}{dt^2} = -\omega^2 x
$$
:::

Where $x$ is the coordinate for position. $\omega$ is known as the angular frequency and is defined as the following:

:::Figure:Equation
$$
\omega = 2 \pi f
$$
:::
 Where $f$ is the frequency of the oscillator. **This definition of $\omega$ is true for all simple harmonic oscillators.** You maybe have seen Equation 1 solved in a lecture class before. We won't go through it here, but we will remind you that the solution gives position, $x$, as function of time , $t$. The equation for position is given in Equation 3 below. 
 
:::Figure:Equation
$$
x = x_0 \cos (\omega t)
$$
:::

$x_0$ is the amplitude of the periodic motion, but also marks the initial position. 

## 2. Simple Pendulum
[comment]: # (Period is to the length of the pendulum--use this?)

:::Figure:Figure
![Picture of Pendulum](imgs/Pendulum.png)
:::

A simple pendulum is one that is simple a point mass at the at the end of a massless string of length $L$. A simple pendulum that is released from a small initial angle ($<15 ^{\circ}$) exhibits simple harmonic motion. For the case of the pendulum it is the angular position given by $\theta$ that follows Equation 1. That is to say:

:::Figure:Equation
$$
\alpha = \frac{d^2 \theta}{dt^2} = -\omega\small_{0}\normalsize^2 \theta = -\frac{g}{L} \theta
$$
:::

You may also recall that for a simple pendulum $\omega\small_{0}\normalsize = \sqrt{\frac{g}{L}}$, where $g$ is the acceleration due to gravity and $L$ is the length of the pendulum. This has been inserted in Equation 4 above.

Lastly this means that angular position of the pendulum is given by:

:::Figure:Equation
$$
\theta = \theta\small_{0}\normalsize \cos (\omega\small_{0}\normalsize t)
$$
:::

## 3. Circular Motion

In this experiment you will be using your phone to measure accelerations. Therefore we should discuss what types of accelerations your phone will undergo as it swings back and forth. In a pendulum, the motion of the mass (your phone) moves on an arc of a circle. Therefore we can use our knowledge of circular motion. 

Object moving in a circle are said to have an angular velocity denoted as $\omega$. **This angular velocity is different from the $\omega_0$ used in Equations 4 & 5.** This angular velocity is defined as the rate of change of the angular position.

:::Figure:Equation
$$
\omega = \frac{d \theta}{dt}
$$
:::

Recall from your Physics 2 class that the acceleration an object experiences has two components. One points the radial direction (towards the pivot). This we will call $a_{rad}$ or $a_r$ for short. The other points in the direction of motion tangential to the circle. This is sometimes call $a_{tan}$ but for this lab we will call it $a_{\theta}$.

:::Figure:Figure
![Picture of Pendulum](imgs/acceleration3.png)
:::

The equation for both of the accelerations is given below:

:::Figure:Equation
$$
a_{r} = r \omega^2 = r  \left ( \frac{d \theta}{dt} \right )^2
$$
:::

<!-- a_{r} = L\omega^{2}\theta_{0}^{2}\sin^{2}(\omega t) -->

:::Figure:Equation
$$
a_\theta = r \alpha = r  \frac{d^2 \theta}{dt^2}
$$
:::

## Part II: Calculations
:::Exercise
Now we have all of the necessary information to calculate the information we will get back from our phone during the experiment. Assuming your apparatus has your phone face always pointing at the pivot point, which allows us to convert to polar coordinates, determine the equation for the acceleration in the radial direction and the equation of the acceleration in the angular direction. 

#####
Assume:
:::Figure: 
$$
\theta = theta\small_{0}\cos(\omega t)
$$
:::
Plug in the formula for theta
Assuming your phone face is pointed in the z ^hat, we only need to consider the y^hat (theta hat) and Z^hat directions for acceleration. One of these will follow the length of your phone and the other will follow the width of your phone.
Knowing the positional equation for both x and y, determine the first and second derivative of each.
Note: picture of phone at several different (3) positions with coordinates drawn on picture
Q1 Compare/Draw the conclusion that the period of one acceleration is the same as the period of the pendulum and that one period of one acceleration is double the first? “What is the period compared to…”
:::Question
Using Equation 5, determine the equation for $$a\small_{r}$$ and $$a\small_{\theta}$$ as a function of time.
:::
:::





## 1. The Experiment
Typically when measuring the period of the pendulum you would measure the angular position as a function of time. Then from that data you would measure the period of the pendulum. 

We

:::Figure:Figure
![Gif  of pendulum moving](imgs/accelerationgif.gif)
:::

##### Background
A period is the time it takes for one cycle in a repeating event. It is the time for which the event repeats itself. A pendulum at rest is considered to be in equilibrium. Once the pendulum is displaced, it oscillates about the equilibrium position. The duration of time from the position of displacement after it is released and back to that position is the period.


The restoring forces obey Hooke’s Law (approx). The restoring forces are proportional to the displacements.
PAULA’S SLIDES

Ex 1 Derive the equations
Ex 1
Assume $$\theta = \theta \small_{0} \normalsize \cos(\omega t)$$





Ex 2
Show that we can assume a point mass for your phone, making our work much easier
Zak’s overleaf
Give them equation w = sqrt (mgL/I) (equation 1)
Do MoI of point particle
Determine MoI for phone using Parallel Axis Theorem
Plug PAT MoI into equation 1
Convince students that 1/12 Ma^2 where a is length of phone is much less than ML^2 and can be ignored (we might need to guide them through this)
Q2:
We want to make the correction term (the term due to rotation) as small as possible so given that your phone is X cm long, what length of string would you like to make your pendulum?

Ex 3
Build apparatus. Take pic. Take data. 
PUT DISCLAIMER ABOUT SECURING PHONE/PILLOWS/EVERYTHING

## 4. Building an apparatus
In this experiment you will be using your phone to measure the 

[INSERT ANIMATED GIF HERE]
While you may be able to achieve a pendulum without it, we recommend you find a tube from toilet paper and, after flattening it, mark the width of your phone on both sides of the flatted tube.
Cut into the roll approximately 2cm deep at each mark of your phone’s width and then cut along the length of the roll to complete the cutout. Do this on both sides.
Poke holes in each of the corners of the now flattened roll, leaving enough space along the edge that you don’t rip out to the edge.
