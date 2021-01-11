# Lab 1: Coefficient of Restitution - Week 2
---
## Materials

::: Materials
- Two kinds of bouncy balls
- A hard, flat surface in an open space
- Phyphox "Acoustic Stopwatch" or an audio recording device that shows sound amplitude
:::

## Lab Goals
- **Apparatus**
	- Use the two bouncy balls and the flat surface in the open space you identified last week.
- **Data Analysis**
	- Collect times of flight data from two balls.
	- Analyze this data to determine the coefficient of restitution for both balls.
	- Using your measured coefficient of restitution and theory of Newton's experimental law, determine how the maximum bounce heights change with bounce number.
	- Determine the percent energy loss per bounce for each ball.

---

:::Note
Be sure to include your spreadsheet, including tables, plots and sample calculations.
:::

# The Experiment
## 1. Overview
In this lab we will investigate Newton's Experimental Law by observing a ball bounce off the floor multiple times. We will calculate $\epsilon$ for two different balls, use our results to predict subsequent bounce heights, and understand how energy is lost to the environment during each collision.

:::Note
If you find that your Acoustic Stopwatch is stopping or starting when you don't expect it to, you may need to adjust the threshold. The default is $0.1$ a.u. Increasing the threshold means the sound will have to be **louder** in trip the stopwatch. Decreasing it means **quieter** sounds will trip the stop watch. Adjust accordingly.
:::

:::Note
Note that there is an "Inelastic Collision" experiment module bundled with Phyphox, but it doesn't give you all the data needed for this lab, and our testing has suggested it is *less* accurate than the procedure given below. In other words, don't use it :)
:::

:::Video
![Ball Being Dropped](../imgs/lab1/droppingball.gif)
:::

## 2. Using sound to record the time of flight between bounces

---

:::::: Exercise
Follow the steps below to collect data using the Acoustic Stopwatch module in Phyphox.

1. Open your acoustic timer in "sequence mode". This mode will record the times between 6 successive sounds (and thus 5 times of flight).
2. In a large, open area, place your phone on the ground with the microphone pointing down. For example, in the video above, the phone is propped against the back wall.
3. Hold the ball at the height of a nearby marker, such as a doorknob or counter top. 
4. For determining the coefficient of restitution, bounce heights, or energy loss during collisions, the initial drop height does not have to be the same each run. However, we will want to look at the average across your five runs throughout your calculations, thus you should try to *make each initial drop height the same across runs*.
5. Press "Reset" on the app to clear any accidental data.
6. Drop the ball and let 5 times of flight register. If your ball knocks into an object or travels too far away, you will have to redo that run. Be sure to double check your times and make sure they are monotonically decreasing.
7. Record these times on a and repeat the procedure for each ball at least 5 times.

:::Question
Step 4 above claims that the initial ball drop height doesn't have to be exactly the same each run. Why is that the case? Hint: Review "Newton's Experimental Law".
:::

:::Question
Step 4 above also states you should try to use the same initial heights for each run for the purpose of averaging. Why is this necessary?
:::

::::::

## 3. Data Analysis

### Using Equations in Spreadsheets

To refresh your knowledge on how to manipulate data and use equations in a spreadsheet, watch the video below.

:::Video
<iframe width="800" height="500" src="https://www.youtube.com/embed/Zi3H_8JV3jY" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
:::

For each ball you should have recorded 5 runs, with 5 times of flight each, for a total of 25 data points per ball. We will use these data points to calculate some quantities of interest, such as the coefficient of restitution, the maximum bounce heights, and the percent energy loss per bounce. 

:::Exercise

We need to generate a spreadsheet in which you will record your data and perform the analysis.
For convenience, we have a template of an [organized google sheet](https://docs.google.com/spreadsheets/d/1BLGy1LDlR9DbBSJBjNng0Bqsdq2v0hdrRohqFt27sUM/edit?usp=sharing) that you can use for your data. If you wish to use the template, please make your own copy of it. 
Note: You will still have to fill in the correct sheet formulas and make the required plots on your own.

Follow the instructions listed below:

1. For one of your balls, make a table such as the one below (or use the one provided in the template). Title this table "Time of Flight during Bounce"


| Bounce # | Run 1 (s) | Run 2 (s) | Run 3 (s) | Run 4 (s)  | Run 5 (s) | Average Time of Flight (s) | Standard Deviation (s)
| -------- | -------- | -------- | -------- | -------- | -------- | -------- |-------- |
| 1    |      |     |     |     |     |     |     |
| ...   |      |     |     |     |     |     |     |
| 5   |      |     |     |     |     |     |     |


2. Fill this table with the data you collected from the first ball in Exercise 1. In the last two columns use a spreadsheet equation to calculate the average time of flight for each bounce and a spreadsheet equation to calculate the standard deviation for each bounce.

3. Repeat the above steps with the data from your second ball.
:::


### Coefficient of Restitution

::::::Exercise

1. Make a table (or use the template table) to calculate the measured coefficient of restitution $\epsilon$ for each bounce using the recorded time of flights. Use the formula you derived in Week 1 Question 1 relating the coefficient of restitution $\epsilon$ to the times of flight $t_n$ and $t_{n+1}$.
2. Calculate the total average over all 5 x 4= 20 measurements of $\epsilon$ per ball.
3. Calculate the standard deviation over all measurements.
4. Repeat this exercise with the data from your other ball.

:::Question
Report your average $\epsilon$ and the standard deviation for each ball, based on the entire set of data. Write this result in the form:

Measured coefficient of restitution =$(\epsilon_{average} \pm  STD)$ 
:::

::::::

### Predicting maximum bounce heights
::::::Exercise

In a spreadsheet, follow the instructions listed below:

1. Make a table in which you calculate the maximum bounce heights corresponding to each of the 5 times of flight in each run. Title this table "Maximum Height for Each Bounce." **Be sure to include units.**

:::Question
1. What mathematical equation did you use to calculate the maximum height for each bounce?

2. For one of your cells, what was the spreadsheet formula you used to calculate the maximum height for each bounce?
:::

Now that we calculated the maximum heights for each bounce, we want to determine how the height $h_n$ depends on the bounce number $n$. 

2. Make a plot of the maximum bounce heights $h_n$ as a function of the bounce number $n$ for each run of your ball. Hint: Make sure you include all elements of a good graph (e.g. properly labeled axes with units, graph title, etc).

3. In the above plot, graph the equation from Week 1 Question 3 part b) using the average $\epsilon$ you reported in the previous Exercise. Do you think this model fits your data well? 

4. Using the exponential curve you plotted, and your knowledge of projectile motion, sketch a rough graph of one ball's height over time.
::::::

### Percent Energy Loss
::::::Exercise
1. Make another table that calculates the percent energy loss (PEL) after each bounce using the equation derived in Question 5 from Week 1. Title this table "Percent Energy Loss during Each Bounce." **Hint: since you will need to know the initial energy to calculate the percent energy lost, you will not be able to perform this calculation for the first bounce.**

2. Calculate the average across bounces **and** runs using the spreadsheet.
3. Similarly, calculate the standard deviation of your data across bounces **and** runs using the STDEV function.
4. Calculate the total average over all 5 x 4= 20 measurements of PEL per ball.
5. Calculate the standard deviation over all measurements.
5. Repeat the above steps with the data from your other ball.

:::Question
1. Look at the standard deviations obtained across runs and those obtained across bounces. Is one set of standard deviations larger than the other?

2. What do you think this means?

3. Explain if your observation in part (a) is consistent with Newton's Experimental Law.

:::

6. Create a plot of the average percent energy lost PEL per bounce as a function of bounce number.
7. Repeat this with the data from your other ball.

:::Question
1. For each ball, does the percent energy loss seem to increase, decrease, or stay the same with increasing bounce number? Explain your reasoning.

2. Does your observation in part (a) match Newton's Experimental Law? If not, where do you think the law fails in your experiment? 
:::

::::::


## 4. Follow Up Analysis Questions

:::Question

1. Based on *Newton's Experimental Law*, should your results change if you threw the ball at the ground? Why or why not?

2. Based on *your observations*, might your results change if you threw the ball at the ground? Why or why not?
:::

:::Question
1. Based on your data, from what height do you need to drop the ball for its 2nd bounce to reach a height of 28 cm (the length of a sheet of paper)?  Show your work and how you arrived at this conclusion.				
										
2. Use the Acoustic Stopwatch to determine the height of the ball on the second bounce. You may also use your phone's camera as an independent form of verification and a piece of paper.
					
3. How accurate was your prediction? Calculate the *percent discrepancy* between your predicted height and the experimentally measured one.
					
:::

# Conclusion

::: Exercise
Write a short paragraph describing the procedure followed and any important observations for each Exercise. Be sure to summarize your results and reasons why you believe your data are precise and accurate. If you do not think your data are accurate, explain why, and how it could be fixed in a future lab.
:::

