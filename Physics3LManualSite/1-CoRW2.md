# Lab 1: Coefficient of Restitution - Week 2
---
## Materials

::: Materials
- Two kinds of bouncy balls
- A hard, flat surface in an open space
- Phyphox &ldquo;Acoustic Stopwatch&rdquo; or an audio recording device that shows sound amplitude
:::

## Lab Goals
- **Apparatus**
	- Use the two bouncy balls and the flat surface in the open space you identified last week.
- **Data Analysis**
	- Collect time-of-flight data from two balls.
	- Analyze these data to determine the coefficient of restitution for both balls.
	- Using your measured coefficient of restitution and theory of Newton&rsquo;s Experimental Law, determine how the maximum bounce heights change with bounce number.
	- Determine the percent energy loss per bounce for each ball.

---

:::Note
Be sure to include all tables, plots and reasoning in your **written report**.
:::

# The Experiment
## 1. Overview
In this lab we will investigate Newton&rsquo;s Experimental Law by observing a ball bounce off the floor multiple times. We will calculate $\epsilon$ for two different balls, use our results to predict subsequent bounce heights, and understand how energy is lost to the environment during each collision.

:::Note
If you find that your Acoustic Stopwatch is stopping or starting when you don&rsquo;t expect it to, you may need to adjust the threshold. The default is $0.1$ a.u. Increasing the threshold means that the sound will have to be **louder** to trip the stopwatch. Decreasing it means **quieter** sounds will trip the stop watch. Adjust accordingly.
:::

:::Note
Note that there is an &ldquo;Inelastic Collision&rdquo; experiment module bundled with Phyphox, but it doesn&rsquo;t give you all the data needed for this lab, and our testing has suggested that it is *less* accurate than the procedure given below. In other words, don&rsquo;t use it :)
:::

:::Video
![Ball Being Dropped](../imgs/lab1/droppingball.gif)
:::

## 2. Measure the times of flight between bounces

:::Note
In the Google assignment on Gauchospace, you should have received a Google Doc template worksheet to fill out, as well as a Google Sheets spreadsheet.

Use this spreadsheet to record and analyze your data. It will be submitted along with your worksheet.

**Note:** There are two tabs at the bottom of the spreadsheet &ndash; one for each ball.
:::

---

:::::: Exercise
Follow the steps below to collect data with the Acoustic Stopwatch module in Phyphox.

1. Open your acoustic timer in &ldquo;sequence mode.&rdquo; This mode will record the times between six successive sounds (and thus five times of flight). If you need to adjust the threshold (see note above) you must do this from the &ldquo;simple mode.&rdquo;
2. In a large, open area, place your phone on the ground with the microphone pointing down. For example, in the video above, the phone is propped against the wall.
3. Hold the ball at the height of a nearby marker, such as a doorknob or counter top. 
4. For determining the coefficient of restitution or energy loss during collisions, the initial drop height does not have to be the same for each run. For the maximum bounce heights, however, the initial height is important. Since we want to average across different runs of the experiment, you should try to *make each initial drop height the same*.
5. Press &ldquo;Reset&rdquo; on the app to clear any accidental data.
6. Drop the ball and let five times of flight register. If your ball knocks into an object or travels too far away, you will have to redo that run. Be sure to double-check your times and make sure they are monotonically decreasing.
7. Record these times in the spreadsheet provided for you in the Google assignment, and repeat the procedure for each ball at least five times.

:::Question
Step 4 above claims that the initial ball drop height doesn&rsquo;t have to be exactly the same each run for determining the coefficient of restitution or energy loss during collisions. Why is that the case? Hint: Review &ldquo;Newton&rsquo;s Experimental Law.&rdquo;
:::

:::Question
Step 4 above also states that you should try to use the same initial heights for each run for the purpose of averaging. Why is this necessary?
:::

::::::

# Data Analysis

For each ball you should have recorded five runs, with five times of flight each, for a total of 25 data points per ball. We will use these data points to calculate some quantities of interest, such as the coefficient of restitution, the maximum bounce heights, and the percent energy loss per bounce.

## 1. Using Equations in Spreadsheets

To refresh your knowledge of how to manipulate data and use equations in a spreadsheet, watch the video below.

:::Video
<iframe width="800" height="500" src="https://www.youtube.com/embed/Zi3H_8JV3jY" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
:::



## 2. Determining the Coefficient of Restitution

::::::Exercise

1. In the provided Google Sheet, calculate the measured coefficient of restitution $\epsilon$ for each bounce by using the recorded times of flight. Use the formula you derived in Week 1, Question 1, relating the coefficient of restitution $\epsilon$ to the times of flight $t_n$ and $t_{n+1}$.
2. Using the &ldquo;AVERAGE&rdquo; function in Google Sheets, calculate the total average over all 5 x 4 = 20 measurements of $\epsilon$ for one ball.
3. Using the &ldquo;STDEV&rdquo; function in Google Sheets, calculate the standard deviation over these measurements.
4. Repeat this exercise with the data from your other ball.

:::Question
Report your average $\epsilon$ and the standard deviation for each ball, based on the entire set of data. Write this result in the form:

Measured coefficient of restitution = $(\epsilon_{average} \pm STD)$ 
:::

:::Note
Make sure to include a copy of this table in your written lab report. **You need to do this for all your tables, but we won&rsquo;t remind you again.**
:::

::::::

## 3. Making a plot

Making plots is an important part of data analysis and presentation. Humans are visual creatures, and it is much easier for us to find patterns and features in a plot than it is by looking at a table.

However, in order for plots to be useful for your future self and for others, they need to be properly formatted. In this lab course we will use the following guidelines for making a plot.

**Guidelines**

- Plots should have a title that explains the point of the graph.
- Each axis should be labeled, with the units included.
- The type of plot should be a scatter plot. This means that the data points should not be connected.
- If you are fitting the data, you should include the equation of the line you are using.
- If you are plotting multiple data sets on the same graph, make sure to use a legend so each data set can be identified.

In one of the exercises below, you will perform a curve fit to your data. For the exercise you will fit a line to your data. When we perform a fit, when possible we also want to get quantitative results from the fit. The video below will guide you through how to create a plot, perform a fit, and get quantitative results about the slope and intercept.

The video shows a scenario where you are driving from San Francisco to San Diego. You create a plot of distance in kilometers against time in hours. You perform a fit of the data to determine the velocity at which you were traveling.

:::Video
<iframe width="800" height="500" src="https://www.youtube.com/embed/wkqlSuAoFLQ" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
:::

## 4. Determining maximum bounce heights

::::::Exercise

1. Use the table provided in the attached Google Sheet to calculate the maximum bounce heights corresponding to each of the five times of flight in each run. Title this table &ldquo;Max Height of Ball During Flight.&rdquo;

2. In the last two columns use a spreadsheet equation to calculate the average of the maximum height for each bounce, which we will denote by $\overline{h_n}$.  In the last column use a spreadsheet equation to calculate the standard deviation of $\overline{h_n}$ for each bounce.

Now that we calculated the average of the maximum heights, $\overline{h_n}$, for each bounce, we want to determine how the they depend on the bounce number $n$.

3. Make a plot of $\overline{h_n}$ as a function of the bounce number $n$ for each run of your ball. **Hint:** Make sure you include all elements of a good graph (*e.g.*, properly labeled axes with units, graph title, etc).

4. On the **same plot** as above, graph the equation from Week 1, Question 3, part b) using the average $\epsilon$ you reported in the previous Exercise and the average value for the maximum height of the first bounce, $\overline{h_1}$. **Hint:** In the Google Sheet provided there is a column for including your theoretical values. The first row of the column should contain your value for $\overline{h_1}$; then you can calculate the rest of the rows from there.

::: Question

1. Look at the theoretical values you plotted compared to the experimental ones. Does this model fit your data well? Explain. **Hint:** Do you notice any visual trends between your experimental data and your theoretical values?

2. Does your observation in part (a) match Newton&rsquo;s Experimental Law? Why or why not?
:::

::::::

## 5. Determining Percent Energy Loss per Bounce

::::::Exercise

1. Make another table that calculates the percent energy loss (PEL) after each bounce by using the equation derived in Question 5 from Week 1. Title this table &ldquo;Percent Energy Loss during Each Bounce.&rdquo; **Hint: since you will need to know the initial energy to calculate the percent energy lost, you will not be able to perform this calculation for the first bounce.**

2. Calculate the average across bounces **and** runs by using the spreadsheet. The average across bounces means that you average PEL across runs for each bounce number (*e.g.*, average all first bounces across all 5 runs). The average across runs means that you average PEL for all the bounces in that run.
3. Similarly, calculate the standard deviation of your data across bounces **and** runs by using the STDEV function.
4. Calculate the total average over all 5 x 4 = 20 measurements of PEL per ball.
5. Calculate the standard deviation over all measurements.
5. Repeat the above steps with the data from your other ball.

:::Question

1. Look at the standard deviations you obtained across runs and those you obtained across bounces. Is one set of standard deviations larger than the other?

2. What do you think this means?

3. Does your observation in part (a) match Newton&rsquo;s Experimental Law? Why or why not?

:::

6. Create a plot of the average percent energy lost, PEL, per bounce as a function of bounce number, for one ball.

7. Perform a linear fit to your data. Make sure to include the equation in the plot. 

8. Repeat this with the data from your other ball.

:::Question
1. For each ball, does the percent energy loss seem to increase, decrease, or stay the same with increasing bounce number? Explain your reasoning.

2. Does your observation in part (a) match Newton&rsquo;s Experimental Law? Why or why not?
:::

::::::


## 6. Follow-up Analysis Questions

:::Question

1. Based on *Newton's Experimental Law*, should your results change if you threw the ball at the ground? Why or why not?

2. Based on *your observations*, might your results change if you threw the ball at the ground? Why or why not?
:::

:::Question
1. Based on your data, from what height do you need to drop the ball for its 2<sup>nd</sup> bounce to reach a height of 28 cm (the length of a sheet of paper)?  Show your work and how you arrived at this conclusion. Pick either of the two balls to answer this question.		
										
2. Use the Acoustic Stopwatch to determine the height of the ball on the second bounce. You may also use your phone&rsquo;s camera and a piece of paper as an independent form of verification.
					
3. How accurate was your prediction? Calculate the *percent discrepancy* between your predicted height and the experimentally measured one.
					
:::

:::Note
You need to include your spreadsheet with your submission. This will be used to check your calculations in case some of your answers are incorrect. **This is not to replace the plots and tables included in your report.**
:::
# Conclusion

::: Exercise
Write a short paragraph describing the procedure you followed, and any important observations for each Exercise. Be sure to summarize your results and reasons why you believe your data are precise and accurate. If you do not think your data are accurate, explain why, and how this could be fixed in a future lab.
:::

