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
#####
<!---This was an idea I had for showing the same thing but with a pendulum...alas, I could not find it...
#####
![SHMSpring](imgs/SHMSpring.gif?Style=centerme)-->
#####

:::Exercise
In order to accurately measure the length of your pendulum, we will need to figure a method for determining that. If you have a measuring tape, use it. We could use another string and use that. We could ______. You are free to use either of those methods. However, using trigonometry will be more accurate in the end and will require a little explanation.
#####
First, we suggest that you keep your string lengths perpendicular to the floor, i.e. from the front view, you do not want them flaring out or in, but rather straight up. This will make things a little easier. Secondly, you will need to calculate two projections of the length in order to use the Pythagorean theorem to determine the effective length of your pendulum.
#####
//pictures here
#####
//diagrams here
#####

Measure the length of your pendulum. Print a ruler from an online source or use a money. A dollar bill is 6" long and if you need something smaller, a quarter is 1 inch.
:::


::: Exercise

In this exercise you will use Phyphox to collect acceleration data from you phone while it is swinging.

1. Make a table. Be sure to include things like mass, $m$, length, $L$, period, $T$.


:::Figure:Table

| Mass [kg] | Length [m]| Period [s] | 
| -------- | -------- | -------- |
|     |     |     | 

:::


2. Look up the mass of your phone online. Record the value in your table. Make sure to use the correct units. 
3. Using the "Accelerometer **without** g" experiment and tap ⋮ to go to "Timed Run". Chose an appropriate start delay (first blank) and experiment duration (second blank & about 15-20 secounds). Now, when you hit play, the phone will wait the set amount of time to start collecting data and then only collect data for the time you set. This will allow you get a nice run of data and not have to do any trimming later.

:::Figure:Figure
![Screenshot of Timed Run](imgs/TimedRun.jpg)
:::

5. Displace the phone by a small amount (something like $15^{\circ}$), hit play, and then release your phone.
6. Let it swing for the time you set in Step 3 and then look at your data. 
7. Ensure that the data looks good, and that you have 10 or more periods before exporting it.

:::Note
"Good" data is hard to define. You might just try taking a couple runs to see what type of data comes out. You should however be able to make *some* predictions about what good data should look like. Recall that $a_\theta$ should look like $\cos(\Omega t)$ while $a_r$ should look like $\sin^2 (\Omega t)$. Thus you should hope to see things like $a_r$ has half roughly the period of $a_theta$. You should notice that $a_\theta$ oscillates about $0$ while $a_r$ is almost entirely positive. Your final axis shouldn't have much on it). It is unlikely that you will get perfect data (i.e. exact cosine and sine squared functions), but should see these sort of trends.
:::

:::Note
Pay attention to the vertical axis scaling on your three plots. They won't all be the same so you shouldn't directly compare your three graphs to each other without first rescaling or noting the difference in scales.
:::
:::



# Part V: Data Analysis 
<!---ex 2 get everyone's data, plot it, do a power fit. check that it matches theory-->

:::Exercise
7. Determine which axis has the appropriate data and calculate the average for one period. Use upwards of 10 periods or more.
8. Create a spreadsheet and import the data from your phone--this is easily done by sending the data from your phone in an email to yourself. 
:::Question:
Some Question here about their plot or data collected
#####
a) What is the period?
#####
b) What is g?
#####

#####
-Does the period significantly depend on the length? Why? Justify your answer.
#####
:::
::: 
:::Exercise
Length = X
1. Make a new apparatus or re-use your old one using the given length.
2. Fill out this form (or sheet) to submit your 'Acceleration without g' data in order to average one period using the results of all the students in your section.
3. mass question

:::
:::Exercise


5. It is very hard to make analytical comparisons unless we linearize.  Plot this data and perform a power curve fit

6. Calculate g based on the resulting average of one period for the given length.

:::Question
Even though you only took data for one initial angular displacement and one mass, answer the following questions (based on your intuition?)
#####
Does the period significantly depend on the mass? Why? Justify your answer.
#####
Based on the average of one period, what is g?
:::
:::


:::Exercise
<!---ex 3 linearize it. show linest video. "this is your error now, on your slope", translate it into error in g. how does that value compare to your known g?--->
:::
# Part VI: Conclusion
::: Exercise
1. Describe the experiment you will be performing next week.

2. Briefly state how the acceleration you will measure will be related to the period of the pendulum.

3. Summarize how using your phone as the bob affects your pendulum.
	:::