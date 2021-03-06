# Lab 2 Pendulum Week 2
---

### Required Materials:

- String, twine, ribbon, or some other type of long, thin, flexible structure for tying and supporting
- A pair of scissors
- Somewhere to hang your pendulum, *e.g.*, shower curtain rod, broomstick across two chairs, taped to a dining room table, etc.
- phyphox &ldquo;Acceleration without g.&rdquo;
- Pillow, couch cushion, or something similar

##### Suggested Additional Materials:
- Toilet paper roll or something similar
- A rubber band or some other elastic material
- Measuring tape
- Tape

### Lab Goals:

- **Construct an apparatus** 
- Construct a method of suspending your phone
- Find a place to **safely** hang your phone
- **Data Analysis**
	- Understand the theory of Simple Harmonic Motion
	- Understand the relationship between period and length
	- Develop the equations from Newton's equations of motion to verify your data

---

# Part III: Building an Apparatus



:::row
:::column
:::Figure:Figure
![Carpet Pendulum](imgs/CarpetPendulum.gif)
:::
:::
:::column
:::Figure:Figure
![Bathroom Pendulum](imgs/BathroomPendulum.gif)
:::
:::
:::

:::Note
DISCLAIMER - You will be using your phone to take data, and this can sometimes lead to accidents. **Please use due care in handling your phone during this experiment.**
:::



<!---[INSERT ANIMATED GIF HERE]--->


In this experiment you will be using your phone to measure the acceleration in the x, y, and z axes without gravity. You will build an apparatus and take data. Include a picture of your setup if you can!

While you may be able to achieve a pendulum without them, we recommend using the additional materials as well. This guide will assume that you have them.

:::Figure:Figure
![Suggested Materials](imgs/IMG_0713.jpg)
:::


1. Find the cardboard tube from a toilet paper roll and flatten it.  
<!---:::Figure:Figure![Suggested Materials](imgs/IMG_0710.jpg):::--->

2. Mark the width of your phone on both sides of the flattened tube.
<!---:::Figure:Figure![Suggested Materials](imgs/IMG_0712.jpg):::--->

3. Make a cut, approximately 4 mm deep, at each mark you made with your phone. Cut from one mark to the other, along the length of the roll, to complete the cutout. Do this on both sides.

:::Figure:Figure
![Suggested Materials](imgs/IMG_0716.jpg)
:::

4. Poke holes in each of the corners of the flattened roll, leaving enough space along the edge that you don’t rip out to the edge.

:::row
:::column
:::Figure:Figure
![Suggested Materials](imgs/IMG_0720.jpg)
:::
:::
<!---:::Figure:Figure![Suggested Materials](imgs/IMG_0724.jpg):::--->

:::Figure:Figure
![Suggested Materials](imgs/IMG_0726.jpg)

:::
:::

5.  Now cut a long length of string. Make sure you leave a lot of slack, too. This string will run through the width edge, run underneath the roll, then back through and up the other width edge hole.

:::Figure:Figure
![Suggested Materials](imgs/IMG_0727.jpg)
:::

6.  Insert your phone into the whole you have cut, with the string ends on the same side as your phone face. Put a rubber band, or something else elastic, around one end of the phone (while the roll is at that end). Slide the roll and elastic band to the other side, so you can fir it around there too. This will secure your phone even more.

:::Figure:Figure
![Suggested Materials](imgs/3N1.jpeg)
:::


7.  Now find something from which to hang your string. I have used both a shower frame and a broom handle set between two chairs.

:::row
:::column
:::Figure:Figure
![Suggested Materials](imgs/IMG_0695.jpg)
:::
:::


:::Figure:Figure
![Suggested Materials](imgs/IMG_0703.jpg)
:::
:::

8. If your phone is not level, try corrective measures.

:::row
:::column
:::Figure:Figure
![Suggested Materials](imgs/IMG_0700.jpg)
:::
:::


:::Figure:Figure
![Suggested Materials](imgs/IMG_8007.jpg)
:::
:::

Note: I added tape after the second photo to ensure that everything would stay in place.



# Part IV: Experiment

##### Background
A period is the time it takes for one cycle in a repeating event or the time for which the event repeats itself. 
#####
A pendulum at rest is considered to be in equilibrium. Once the pendulum is displaced, it oscillates about the equilibrium position. The duration of time from the position of displacement after it is released and back to that position is the period of the pendulum.
#####
You should have determined by now how you will be turning your phone into a pendulum.
#####
Typically, when measuring the period of the pendulum, you would measure the angular position as a function of time. Then from those data you would calculate the period of the pendulum. 
#####
(very rough) Did you know that the clock was invented after the discovery of Simple Harmonic Motion? Simple Harmonic Motion also is how musicians keep time with one another.
Vibration on a string produces a pitch, and depending on where the musicians fingers are. Now, as the vibration diminishes, why does the pitch stay the same?
#####
Newton's famous 2nd Law of Motion states that force is equal to mass times acceleration. We know that acceleration is the second derivative of position. In Simple Harmonic Motion, force comes from the displacement of $x$, itself.

$$
F = ma
$$
$$
F = m  \frac{d^2 x}{dt^2}
$$
$$
F = -kx
$$
$$
m \frac{d^2 x}{dt^2} = -kx
$$
$$
\frac{d^2 x}{dt^2} = -\frac{k}{m}x
$$
This is the form of the differential equation of SHM. The answer,  it seems, must come from the time-honored tradition of guessing. When you plot your pendulum's motion during the experiment, you will see sinusoidal motion. This was the guess that was made for the differential equation! The guessed solution was $x = A \sin\omega t$ but if that was $x$, was the second derivative equal to $-\frac{k}{m} x$?
#####
This was an idea I had for showing the same thing but with a pendulum...alas, I could not find it...
#####
![SHMSpring](imgs/SHMSpring.gif?Style=centerme)
#####
Why did I write this proof? I really don't know...but here it is:
$$
x = A\sin\omega t
$$
$$
\frac{d^2 x}{dt^2} = -A\omega^2\sin\omega t
$$
$$
\frac{d^2 x}{dt^2} = -\omega^2x
$$
$$
\omega^2 x = - \frac{k}{m}
$$
$$
\omega =  \sqrt\frac{k}{m}
$$
The frequency is measured in radians per second. There are $2\pi$ radians in each cycle, $f$.

:::Figure:Figure
$$
\omega = 2\pi f
$$
:::
Looking now at a free body diagram of a pendulum, we see
![Suggested Materials](imgs/PendulumFBD.gif?style=centerme)

#####
and if the dashed line is $x = 0$, then
$$
F = ma
$$
$$
ma\small_{x}\normalsize = -T\sin\theta = -T\frac{x}{l}
$$
$$
ma\small_{y}\normalsize = T\cos\theta -mg
$$
$$
\cos\theta \approx 1
$$
$$
a\small_{y}\normalsize \approx 0
$$
$$
0 = T\cos\theta - mg
$$
$$
T = mg
$$
$$
ma\small_{x}\normalsize = -mg\frac{x}{l}
$$
$$
a\small_{x}\normalsize\;\;or\;\;\frac{d^2 x\small_{x}\normalsize}{dt^2} = -\frac{g}{l}x
$$
$$
a\small_{x}\normalsize = -\omega^2x
$$
$$
\omega = -\sqrt\frac{g}{l}
$$

and using equation 13 above, 
$$\omega = 2\pi f  = \frac{2\pi}{T}
$$
$$\therefore \;\;\;\;\;\;T = 2\pi \sqrt\frac{l}{g}
$$

#####
#

:::Exercise
1. Make a table. Be sure to include things like mass, m, length, l, period, T, as well as the initial angle, $\theta$ (you only need approximate this)


:::Figure:Table

| Mass | Column 2 | Column 3 | Zak added Column |
| -------- | -------- | -------- |---|
| Text     | Text     | Text     | Hi |

:::


2. Look up the mass of your phone online. Record the data (alternately they can grab some things from the kitchen with weight listed on them and create a balance -- this link here is for anything we may need to weigh in the future: https://www.hunker.com/13414006/how-to-weigh-things-without-a-scale
3. Measure the length of your pendulum (AVOCADO come back to this). Print a ruler from an online source or use a money. A dollar bill is 6" long and if you need something smaller, a quarter is 1 inch.
4. measure small angle for one length
5. Using the 'Accelerometer without g' function (and we find making it a timed run gives a lot of data and the ability to start the pendulum in motion before recording starts).
6. Determine which axis you will be using and calculate the averaged measured period using ~10 periods.
7. Create a Google Sheet and import your data from your phone--this is easily done by sending the data from your phone in an email to yourself). Plot your data.
8. Determine which axis you will be using and calculate the averaged measured period using ~10 periods.
9. Fill out this form to submit the data for your classes total data.

:::Question:
Some Question here about thier plot or data collected

what is the period?

what is the frequency?

question about potential and kinetic energy?
:::
:::

# Part V: IDR
ex 1 take your data put it in table that makes sense, calculate g (10 periods, divide by 10).
ex 2 get everyone's data, plot it, do a power fit. check that it matches theory
ex 3 linearize it. show linest video. "this is your error now, on your slope", translate it into error in g. how does that value compare to your known g?



# Part VI: Conclusion
::: Exercise
1. Describe the experiment you will be performing next week.

2. Briefly state how the acceleration you will measure will be related to the period of the pendulum.

3. Summarize how using your phone as the bob affects your pendulum.
	:::