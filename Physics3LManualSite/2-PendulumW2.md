# Lab 2 Pendulum Week 2
---

## Required Materials

:::Materials
- The pendulum apparatus you built last week.
- Your cellphone
- Phyphox "Acceleration without g"
- Measuring Tape
- Pillow, couch cushion, or something soft to protect your phone
:::

## Lab Goals

- **Construct an apparatus** 
	- Set up your apparatus from last week.
- **Data Collection** 
	- Use "Acceleration without g" to collect acceleration data.
- **Data Analysis**
	- Understand the theory behind Simple Harmonic Motion
	- Understand the relationship between period and length
	- Develop the equations from Newton's equations of motion to verify your data

---

# Experiment Review

## What is the Period?
A period is the time it takes for an object to undergo one cycle in a repeating event or the time for which the event repeats itself. A pendulum at rest is considered to be in equilibrium. Once the pendulum is displaced and then released, it oscillates about the equilibrium position. The time it takes for the pendulum to swing from the release point through an arc to to the opposite point, and then back to the release point, is the period of the pendulum.

You should have determined by now how you will be turning your phone into a pendulum. Typically, when measuring the period of the pendulum, you would measure the angular position as a function of time. Then from those data you would calculate the period of the pendulum.

The pendulum found its first practical timekeeping application with the invention of the pendulum clock by Christiaan Huygens in 1656. Huygens had been inspired by Galileo&rsquo;s observation that, for small angles of displacement, pendulums of the same length have the same period of oscillation. A type of inverted pendulum is still used in some models of metronome, a device that produces a steady, adjustable beat, which musicians use as a practice aid.


# Data Collection

## Measuring Length

::::::Exercise

In this exercise you will measure the length of your pendulum in meters. This would be straightforward in lab, but since we don't have access to a lab, it might be a bit more complicated. Below are some tips and ideas to help you accomplish this task.

[Fi](#Fi-pendDiagram) below shows a front view and a side view of your phone in the cradle. In the front view, the long axis of the phone is coming in and out of the screen, in the side view it is running parallel to the screen.

The distance you want to measure is from the pivot to the center of mass of the phone. This is depicted as $L$. 

- If you have a measuring tape, use one end at the point of the pivot and then measure straight downward to the center of mass of your phone. 

- If you do not have a measuring tape but have a ruler, cut a piece of string that you will dangle from the surface of the pivot to your phone in a straight, downward line. Then use a ruler to measure the length of that string.

- If you don&rsquo;t have a ruler of any sort, then we recommend using lined paper. You can look up the spacing for different types of rulings. (If you have an 8-1/2&Prime; &times; 11&Prime; piece of paper, you might be able to figure out the spacing by, for example, lining up a long edge of the lined paper with the short edge of the 8-1/2&Prime; &times; 11&Prime; sheet.)

If you do not feel that you can reliably measure the distance between the phone and the pivot, you can measure $l$ and the distance from the bottom end of the string to the center of the phone, and use geometry (the Pythagorean theorem) to find $L$. (You can, of course, make the second measurement by measuring the distance between the two strings at the roll end, and dividing by two.) If you do this, we suggest that you keep your string lengths perpendicular to the floor. That is, from the front view, you do not want them flaring out or in, but rather, straight up (parallel). 

This should be true in either case. If you measure straight from the pivot to the center of the phone, this does not affect your measurement. If, however, you measure the length $l$, if the strings are not parallel, the length you then calculate for $L$ will differ slightly from the actual length.

:::Note
Regardless your choice in measuring device, make sure that the resolution of the measurement is appropriate.
:::

:::Figure pendDiagram
![Suggested Materials](../imgs/lab2/Diagram.png)
:::

:::Question
1. What tool did you use to measure the length of your pendulum?
2. Write a short description of the procedure you used to measure the length.
:::

:::Question
What is the length of your pendulum in meters? Be sure to include the uncertainty in your measurement. 

**Hint:** If you forgot how to get uncertainty from a scale, the information is contained in Lab $0$.
:::

::::::

## Recording the Acceleration Period with Phyphox

:::::: Exercise

In this exercise you will use phyphox to collect acceleration data from your phone while it is swinging.

1. Look up the mass of your phone online. Record the value in your table. Make sure to use the correct units.
2. Open the &ldquo;Accelerometer **without** g&rdquo; experiment and tap ⋮ to go to &ldquo;Timed Run.&rdquo; Choose an appropriate start delay and experiment duration (around 15-20 seconds). When you hit play the phone will wait the set amount of time to start collecting data and then collect data only for the duration you set. This will allow you get a nice run of data and not have to do any trimming later.

:::Figure
![Screenshot of Timed Run](../imgs/lab2/TimedRun.jpg)
:::

3. Displace the phone by a small amount (roughly $15^{\circ}$ or less), hit play, and then release your phone.
4. Let it swing for the time you set in Step 3 and then look at your data. 
5. Ensure that the data look good (see notes below) and that you have 10 or more periods.

:::Note
&ldquo;Good data&rdquo; is hard to define. You might just try taking a couple of runs to see what type of data come out. You should, however, be able to make *some* predictions about what good data should look like.

Recall that $a\small_{\theta}$ should look like $\cos(\Omega t)$ while $a\small_{r}$ should look like $\sin^2 (\Omega t)$. Thus you should hope to see things such as that $a\small_{r}$ has roughly half the period of $a\small_{\theta}$. You should notice that $a\small_{\theta}$ oscillates about $0$, while $a\small_{r}$ is almost entirely positive. (Your final axis shouldn&rsquo;t have much on it.) It is unlikely that you will get perfect data (*i.e.*, exact cosine and sine-squared functions), but you should see these sorts of trends.
:::

:::Note
Pay attention to the vertical axis scaling on your three plots. They won&rsquo;t all be the same, so you shouldn&rsquo;t directly compare your three graphs to each other without first rescaling or noting the difference in scales.
:::

::::::

# Data Analysis 

## Measuring the Average Period

::::::Exercise
We want to determine the period, $T$, of the oscillations of motion. We will do so by looking at the oscillatory behavior of the accelerations recorded by the phone in the three different directions. Remember your derivations from Week 1 to determine the relationship between the periods of the accelerations in the different directions and the period  $T$ of motion of the pendulum.

:::Question

1. How do the periods of the accelerations measured by the phone compare to the positional period of the pendulum?

2. Which axis has the same period as the period of motion?
:::

1. Find the period of motion of the pendulum by measuring the average period of the acceleration that has the same period as the period of motion (your answer from the previous question).

To find the average period, measure the time it takes the pendulum to complete 10 periods (see [Fi](#Fi-periodGif)), and divide by the number of periods (in this case, 10). This will reduce the error in your measurement. If your data cover only eight or nine periods, that works as well. [Fi](#Fi-periodGif) shows you can make a quick measurement of many periods in the Phyphox app. 
- Simply click the "Pick Data" button at the bottom of the screen then touch the point where you would like to start your measurement. 
- Then drag your finger to the end point. A box will appear that will display the difference between the two times you selected.

:::Figure periodGif
![How to measure period in phyphox](../imgs/lab2/PeriodMeasurement.gif)
:::

:::Question
What is the average period of motion? Include 4 decimal places in your measurement.
:::

Remember that the period $T$, is determined by the pendulum length $L$, and the acceleration due to gravity $g$.

:::Equation period
$$T=2\pi \sqrt{\frac{L}{g}}$$
:::

1. Rewrite the Equation 1 to find $g$ in terms of $L$ and $T$.
2. Using the value $L$ that you measured earlier and $T$  which you found from the acceleration data, determine the value of $g$.
3. Find the percent discrepancy between the value you found for $g$ and the accepted value of $9.806 m/s^2$.

:::Question
1. What is the value of $g$ from your measurements? Don&rsquo;t worry about uncertainty.

2. What is the percent discrepancy that you recorded?
:::

::::::

---

## Propagation of Uncertainty

In the last exercise, you calculated a value for $g$ by using your one data measurement. Up until this point in Physics 3L when we have discussed uncertainty, we have determined it either from a scale or by calculating a standard deviation. 

A standard deviation requires multiple measurements of the same value...but you have only one measurement! How can you find the uncertainty in that measurement? Your measurement is the result of a calculation involving values that you measured directly. If you know the uncertainties in those values, then you can calculate how those uncertainties **propagate**&mdash;through the calculation&mdash;to give the overall uncertainty in that measurement. Thus, if you know the uncertainties in $T$ and $L$ you can calculate how they **propagate** to find the uncertainty in $g$.

Figuring out how uncertainties propagate can get complicated and we won&rsquo;t provide the techniques in this lab but we will provide the formula for how to calculate the uncertainty in $g$. 

In the equation below, the uncertainties are denoted with a $\delta$ before the variable and the best estimate is just the variable (*e.g.* $\delta L$ is the uncertainty in the length $L$).

:::Equation
$$
\delta g = g \sqrt{\left ( \frac{\delta L}{L}\right)^2 + \left ( \frac{2\delta T}{T}\right )^2}
$$
:::

:::Note
In the equation above $L$, $g$ and $T$ are all the measured values. The value for $g$ is not measured directly but is calculated from the other two values which are measured directly.
:::

::::::Exercise
In this exercise you will calculate how the uncertainties in $L$ and $T$ propagate, to determine the uncertainty in $g$.

1. First we must determine the uncertainty in $T$. To do this look at your accelerometer data from the &ldquo;Lab $0$: Intro to Phyphox&rdquo; lab. 
2. Open the spreadsheet and look at the time column. In a separate column, take the difference between one time value and the one before it.
3. Divide that difference by 2. This will be your uncertainty in one time measurement, $\delta t$. 
4. To measure the period you took a difference and averaged it. The uncertainty in that operation is given by the following equation where $N$ is the number of periods you measured:

:::Equation
$$
\delta T =\frac{\sqrt{2}}{N}\delta t
$$
:::

::: Question 
What is the period of your pendulum in seconds reported to correct significant figures and with uncertainty?
:::

5. Use the uncertainty in the period, uncertainty in the length, and Equation 2 to determine the uncertainty in $g$.

:::Question
Report your value of $g$ in $m/s^2$ to correct significant figures and with uncertainty.
:::

::::::

---

## Linearizing Data

Determining the quality of a non-linear curve fit quantitatively can be very challenging, and is beyond this class.

However, it is possible to analyze a **linear** fit quantitatively. There are some semi-complicated equations that calculate the uncertainties in the slope and intercept for a linear fit. We won&rsquo;t worry about the details of those here but will use the LINEST function in google sheets.

LINEST is short for Linear Estimation. It will use the method of least squares to make a best estimate of the line that fits your data.

Below is a video that we showed you last week. Last week, we wanted to show you how to make a plot and perform a fit. This week you can skip to the end where it shows you how to use the LINEST function in Google Sheets as well as how to get the slope, the uncertainty in the slope, the intercept, and the uncertainty in the intercept.

:::Video
<iframe width="100%" height="500" src="https://www.youtube.com/embed/wkqlSuAoFLQ" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
:::



::: Exercise

In this exercise you will be submitting your data in a Google form that will be collected into one larger data set with data from all the students in your section. We will then **linearize** the class data, fit a line to the data, and make a quantitative judgment about the experiment. Submit your data in the form linked in the table below. Make sure that the mass you provide is in **kilograms**, the length is in **meters**, and the period is in **seconds**. **Also make sure that you select your correct section!**

### Submit Data to Google Form

<iframe src="https://docs.google.com/forms/d/e/1FAIpQLSefiSL52tiu9OSAtU1GQrwIIwUhYC4kmqIcDddJfJuHdJGm6Q/viewform?embedded=true" width="100%" height="1050" frameborder="0" marginheight="0" marginwidth="0">Loading…</iframe> 

:::




::::::Exercise

In this exercise you will linearize your first equation, namely [Eq](#Eq-period). Then you will use your data, plus the data submitted by your peers create a linear plot and determine the slope and intercept.

To linearize an equation you must perform a mathematical operation on your equation so that the independent variable is linear&mdash;this means that it appears once in the equation and is to the first power. While performing the linearization to the independent variable you track the mathematical operations done to the dependent variable. You then apply those operations to the dependent variable to generate a new equation that is linear.

For this lab $L$ is your independent variable and $T$ is your dependent variable. If you square both sides of [Eq](#Eq-period) you will have a function $T^2$ that is linear in $L$.

:::Question
Linearize [Eq](#Eq-period). What is the new equation?
:::

::: Note
Wait until your TA tells you that it is OK to proceed. You&rsquo;ll need enough submissions to make a usable set of data. 
:::


1. Make a new column in your spreadsheet. In this column square each of the period measurements. 
2. Create a new plot  of $T^2$ and  $L$.
3. Add a linear trend line and use the LINEST function to get the uncertainties for the slope and the intercept.

:::Question
1. What is the value of the slope? Make sure to include the units and uncertainty.

2. Based on your response in Question 8, what is the theoretical equation of the slope?
:::

:::Question
Using the slope. what is the value of $g$.
:::

Determining the uncertainty in $g$ is slightly more complex than just using the uncertainty in the slope provided by LINEST. The slope does not exactly equal $g$, therefore the uncertainties aren&rsquo;t exactly equal either. To determine the uncertainty you must calculate how it **propagates** in the calculation you used to find $g$ from $m$. The details of this topic will be saved for later. Use the assumption that the uncertainty in $g$&mdash;denoted $\delta g$&mdash;is related to the uncertainty in the slope&mdash;$\delta m$&mdash;in the following way:

:::Equation
$$
\delta g = g \left(\frac{\delta m}{m}\right)
$$
:::

:::Question
1. What is the value you measured for $g$ along with the uncertainty?

2. Does the accepted value of $g$ fall within your window of uncertainty?

3. Does this strengthen the theory? Why or why not?
:::

5. Find the percent discrepancy between the value you found for $g$ and the accepted value of $9.806 m/s^2$.

:::Question
What is the value of $g$ and of the percent discrepancy that you recorded?
:::

::::::

# Conclusion

:::Exercise
Write a brief conclusion summarizing the important parts of this lab. 

**Hint:** Briefly summarize each exercise. Where appropriate, include how it fits logically with other exercises. In a couple sentences state your results for your different $g$'s  and how they are related.
:::