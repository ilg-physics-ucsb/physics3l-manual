# Lab 3: Simple Harmonic Motion - Week 2
---

# Intro

## Required Materials

::: Materials
- Your apparatus from last time
- One or two zip-lock bags
- Household baking goods and measuring cups, coins, batteries, or other objects of known mass.
- Measuring tape or meter stick
- Pillow, couch cushion, or something similar.
- Phyphox &ldquo;Acceleration Without g&rdquo; (preferred), or &ldquo;Acceleration (with g).&rdquo;
:::

## Lab Goals:

- **Data Collection**
  - Add masses to your system and measure the stretch of the spring.
  - Use your phone to measure acceleration as your phone oscillates on the spring.
- **Data Analysis**
  - Test Hooke&rsquo;s Law and analyze the regimes in which it holds.
  - Analyze the relationships among mass, *k*, and period for simple harmonic oscillators.

---


## Mass Tables:

### US Coins
::: Table 
| Dollar | Half Dollar | Quarter | Dime | Nickel | Penny |
| :--------: | :--------: | :--------: | :--------: | :--------: | :--------: |
| 8.1g | 11.3g | 5.7g | 2.3g | 5.0g | 2.5g |
:::

### Batteries
::: Table
| | AA | AAA | 9-V | D | C |
| -------- | :--------: | :--------: | :--------: | :--------: | :--------: | 
| Alkaline | 23g | 11.5g |45g | 135g | 65g | 
| Lithium | 15g | 7.6g | 37g| -|- | 
|Rechargable Ni-MH | 31g | 14g |-  | 160g | 80g |
:::

### Household goods
::: Table
|  | Metric equivalent (ml) | Water | All Purpose Flour | Granulated White Sugar | Table Salt |
| -------- | :--------: | :--------: | :--------: | :--------: | :--------: |
| Density (g/ml) |   | 1g/ml |  0.6g/ml |  0.92g/ml    |  1.26g/ml  | 
| 1 cup     |  237ml    |   237g   |  130g   | 200g | 273g | 
| 1 teaspoon     |  4.9ml    |   4.9g   |   3.3g  | 4g | 5.7g |
| 1 tablespoon     |  14.8ml    |   14.8g   |   8.5g  | 12.6g | 17g |
:::

---

# The First Experiment: Hooke&rsquo;s Law

:::Figure
![Sugar in bag hanging on rubberband](../imgs/lab3/Measurement.png)
:::

For this experiment you will hang a zip-lock bag on a spring, and add mass to the bag. You will measure the length of the spring as you add more and more mass.

## Collecting Data
::::::Exercise
In this exercise you will collect the data from the experiment.

1. Collect the masses you decided on last week. If you have changed your masses that is fine; just be sure to update your data table.

2. Measure the length of your spring in its resting position.

:::Note
The end of a tape measure is specially made to allow for both inside and outside measurements without loss of accuracy. (You will notice that it slides back and forth a bit.) Unless you can actually hook it on the end of your spring, it is best to make your measurement from a reference mark further down the tape measure, and make the appropriate subtraction.

If you are using a ruler, if the scale begins right at the end of the ruler, then you should not use the end of the ruler as your zero reference. You should choose a mark away from the end as your reference, and make the appropriate subtraction.
:::

3. Take 10 data points, starting with ~50 g and going to roughly 500 g. Make sure that your first mass is heavy enough to cause your spring to stretch by a measurable amount.

:::Note
Some springs are manufactured to have what is called &ldquo;initial tension.&rdquo; That is, it takes some force to reach the point at which the coils of the spring just barely separate. It may be useful to keep this in mind when you perform your data analysis.
:::

4. Record your mass and $\Delta y$ data in the spreadsheet you made last week. Leave each mass for 5 to 10 seconds before measuring. (The mass should be at rest when you make your measurement.)

5. Check your units to ensure that they are correct. Calculate the values in your table for $F$ and $k$.

:::Question

1. What tool did you use to make your length measurements?

2. What is your uncertainty?
:::

:::Question

1. Describe the masses you used.

2. Estimate the uncertainty in your mass values.

3. What are the sources of uncertainty here?
:::

::::::

## Analyzing Data

::::::Exercise
In this exercise you will analyze the data from Exercise 2 to determine if your spring obeys Hooke&rsquo;s Law.

1. Graph $\Delta y$ vs. $m$, with $m$ as the independent variable.

:::Question

1. Based on the equation you derived in last week&rsquo;s lab, what should the functional form of this plot be (*e.g.*, quadratic, root, linear, exponential, etc.)?

2. What is the shape of your graph? Does it match your expectation?
:::


You will be determining $k$ from the slope, $s$, of your plot. Just as in the previous lab you found the uncertainty in the value of *g* from the uncertanties in *T* and *L* for your pendulum, you will need to calculate how the uncertainty in your slope $s$ propagates in your calculation of the value of $k$. This calculation is very similar to the one that you used in the previous lab. The uncertainty in $k$, which we denote by $\delta k$, is given in terms of the uncertainty in the slope $s$, which we denote by $\delta s$, by the following equation:

:::Equation uncertainty
$$
\delta k = \frac{k}{s}\delta s
$$
:::

2. Use your knowledge from last week and the information on uncertainty provided, to determine the spring constant and the uncertainty in it.

:::Question
What is the spring constant for your spring?
:::

::: Question
Does your spring appear to obey Hooke&rsquo;s law? Explain your reasoning.
:::

::::::

## Using Results

::::::Exercise
In this exercise you will use the data you collected and analyzed in Exercises 1 and 2 to measure the mass of your phone.

1. Place the Phyphox-enabled device you plan on using in experiment 2 in your bag so that it is the only mass weighing on your spring.  Measure the displacement, $\Delta y$. If your bag is dirty from the masses you used, go ahead and use a new bag.

:::Note
If possible, and you feel comfortable doing so, remove your phone from its case. This way you are directly measuring only the mass of your phone.
:::

:::Question

1. What is the displacement, $\Delta y$, with your phone as the mass?

2. Using your results from Exercise 2 and the $\Delta y$ for your phone, estimate the mass of your phone.

3. How does this value compare to what you find online? Note that cases and other things on your phone will increase your estimated mass.
:::

::::::

# The Second Experiment: Simple Harmonic Motion

:::Video
![GIF of moving phone](../imgs/lab3/SHM.gif)
:::

The second experiment will involve your putting your phone in the zip-lock bag and then setting it in motion. You will use the &ldquo;Acceleration without g&rdquo; to measure the acceleration experienced by your phone. You will then use the acceleration to measure the period, and the spring constant of the spring.

## Collecting SHM Data

:::::Exercise
In this exercise you will use Phyphox to collect your data. 

1. Open the "Acceleration (without g)" module on PhyPhox. If you have only "Acceleration with g" that is fine, too.

2. Place your phone in the bag attached to your spring. Note which accelerometer will be sensing vertical motion with your phone in this position.


:::Question
In what axis will your data be collected?
:::

:::Note
Just as in the pendulum lab, we recommend that you use the &ldquo;Timed Run&rdquo; feature of Phyphox. 
:::

3. Press the &ldquo;Play&rdquo; button in the module to begin recording data.

4. Pull down your phone to stretch the spring, and let go.

5. Wait either for the time to run out, or for at least 10 periods to pass.

6. Find $\Delta$t for as many clear periods as you have, and note how many periods you measured.

7. Fill your data table with your measured $\Delta$t and the number of periods, $n$.

:::Video
![Period Measurement](../imgs/lab3/PeriodMeasurement.gif)
:::


:::Note
To calculate the period, T, divide the time by the number of periods, $n$. Note that $n$ is the number of **periods**, not peaks.
:::

8. Repeat this process with four additional mass values. 

:::Note
You can add masses in a separate bag if you are using something messy, such as water or flour.
:::

::::::

## Analyzing SHM Data

::::::Exercise
In this exercise, you will analyze the data you collected in Exercise 5, and use the principles of simple harmonic motion to determine the value of $k$.

:::Question
1. What is the expression for the period, $T$, as a function of mass, $m$, and the spring constant, $k$?

2. If you were to plot $T$ vs $m$ should you fit a line to it? Why or why not?
:::

Last week you had a very similar expression for period. You analyzed it by linearizing the equation and performing a linear fit.

:::Question
How would you linearize the period with respect to mass? (What&rsquo;s the equation?)
:::

1. Graph your linearized data.
2. Fit a line to your linearized graph.

You will have to find the uncertainty in $k$ by calculating how the uncertainty in the slope propagates through your calculation of $k$ from it. The equation you should use is [Eq](#Eq-uncertainty).

:::Question
a) What is the expression for the slope of your line?

b) What is the $k$ value from your fit data?

c) What is the uncertainty, $\delta k$, in your $k$ value?
:::

::::::

# Conclusion
:::Question
If you were asked which of the two methods of measuring the spring constant is the more *precise*, which experiment would you choose, and why? 
:::

::: Exercise
Write a short summary of this lab. Describe the two experiments you performed, and discuss how your two measurements of $k$ relate to each other.
:::
