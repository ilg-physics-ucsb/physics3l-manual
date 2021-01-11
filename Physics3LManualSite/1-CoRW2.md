# Lab 1: Coefficient of Restitution - Week 2
---
## Materials

::: Materials
- Two kinds of bouncy balls
- A hard, flat surface in an open space
- Phyphox "Acoustic Stopwatch" or an audio recording device that shows sound amplitude
:::

## Lab Goals:
- **Apparatus**
	- Use the two bouncy balls and the flat surface in an open space you identified last week.
- **Data Analysis**
	- Collect data from two balls.
	- Analyze this data to determine the coefficient of restitution for both balls.
- **Modeling**
	- Using your measured coefficient of restitution and theory of Newton's experimental law, make a prediction about the height of the ball and test your prediction. 

---

# The Experiment
## 1. Overview
Our job in this lab will be to verify Newton's Experimental Law, calculate $\epsilon$ for different balls, hypothesize what effects this constant, and use our results to make & test a prediction. While your first instinct may be to make a video recording of a ball bouncing, we will approach these tasks in a, perhaps, unexpected way: we will instead use only the sound of the the ball hitting the floor to make our measurements.

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

1. Open up your acoustic timer in "sequence mode". This mode will record the times between 5 successive sounds.
2. In a large, open area, place your phone on the ground with the microphone pointing down. For example, to accomplish this, I propped my phone up against the wall of my living room. 
3. Hold the ball at the height of a nearby marker, such as a doorknob or counter top. 
4. For determining the coefficient of restitution, it is not very important that the initial drop height is the same each run. However, we will want to look at the average across your five runs throughout your calculations, thus you should try to make each drop height as similar as possible.
6. Press "Reset" on the app to clear any accidental data.
7. Drop the ball and let 5 times register. If your ball knocks into an object or travels too far away, you will have to redo that run. Be sure to double check your times and make sure they are monotonically decreasing.
8. Record these times,, and repeat the procedure for each ball at least 5 times.

:::Question
Step 4 above claims that the initial ball drop height doesn't have to be exactly the same each run  Why is that the case? Hint: review "Newton's Experimental Law".
:::

:::Question
Exercise 1 step 4 also states you should try to use the same initial heights for each run for the purpose of averaging. Why is this necessary?
:::

::::::

## 3. Data Analysis

### Using Equations in Spreadsheets

To refresh your knowledge on how to manipulate data and use equations in a spreadsheet, watch the video below.

:::Video
<iframe width="800" height="500" src="https://www.youtube.com/embed/Zi3H_8JV3jY" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
:::

For each ball you should have recorded 5 runs, with 5 times of flight each, for a total of 25 data points per ball. We will use these data points to calculate some quantities of interest, such as  the coefficient of restitution, the maximum bounce heights, and the percent energy loss per bounce. 

For convenience, we have a template of an [organized google sheet](https://docs.google.com/spreadsheets/d/1BLGy1LDlR9DbBSJBjNng0Bqsdq2v0hdrRohqFt27sUM/edit?usp=sharing) that you can use for your data. If you wish to use the template, please make your own copy of it. 
Note: you will still have to fill in the correct sheet formulas and make the required plots on your own .

### Coefficient of Restitution

::::::Exercise

1. Make a table to calculate the measured coefficient of restitution for each bounce. 
2. Calculate the average across bounces **and** runs using the spreadsheet.
3. Similarly, calculate the standard deviation of your data across bounces **and** runs using the STDEV function.
4. Calculate the total average over all 5 x 4= 20 measurements of $\epsilon$ per ball.
5. Repeat this with the data from your other ball.

:::Question
1. Look at the standard deviations obtained across runs and those obtained across bounces. Is one set of standard deviations larger than the other?

2. What do you think this means?

3. Explain if you observation is part (a) is consistent with Newton's Experimental Law.

4. Whether or not it is consistent, discuss why you might expect the observation made in part (a) based on the relationship between energy lost and bounce number you observed in Exercise 3.
:::

:::Question
Report your average $\epsilon$ and the standard deviation for each ball, based on the entire set of data. Write this result in the form:

Measured coefficient of restitution =$(\epsilon_{average} \pm  STD)$ 
:::

::::::

### Predicting maximum bounce heights
::::::Exercise


In a spreadsheet, follow the instructions listed below:

1. For one of your balls, make a table such as the one below. Title this table "Time of Flight during Bounce"


| Bounce # | Run 1 (s) | Run 2 (s) | Run 3 (s) | Run 4 (s)  | Run 5 (s) | Average Time of Flight (s) |
| -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| 1    |      |     |     |     |     |     |
| ...   |      |     |     |     |     |     |
| 5   |      |     |     |     |     |     |

2. Fill this table with the data you collected from the first ball in Exercise 1. In the last column us a spreadsheet equation to calculate the average time of flight for each bounce. Make a plot that has the average time of flight on the y-axis and the bounce number on the x axis.

2. Now make another table with 7 columns and 6 rows, and calculate the max bounce height for each of the 5 times in each run. Title this table "Max Height Each Bounce" **Be sure to include units**
3.  What do the shapes of these graphs look like? Try fitting the data with functions.
4. Repeat this with the data from your other ball.

:::Question
1. What mathematical equation did you use to get the max height for each bounce?

2. For one of your cells, what was the spreadsheet formula you used to calculate the max height for each bounce?
:::

::: Question
Based on your plots alone, what type of line or curve fits your data best? E.g. does the plot look linear, quadratic, logarithmic etc.? Justify you answer.
:::

::::::

::::::Exercise
Energy Loss v.s. Bounces:
:::Question
Derive an equation that determines the percent energy lost after a bounce that *only* uses the max heights. Show any relevant work **Hint: The percent energy loss is the energy lost during the collision divided by the initial energy of the ball.**
:::

1. Make another table that calculates the energy lost after each bounce using the equation derived above. Title this table "Percent Energy Lost Each Bounce" **Hint: since you will need to know the initial energy to calculate the percent energy lost, you will not be able to perform this calculation for the first bounce.**
2. Calculate the average percent energy lost per bounce. Create a plot of the average percent energy lost per bounce as a function of bounce number.
3. Repeat this with the data from your other ball.

:::Question
1. For each ball, does the energy lost seem to increase, decrease, or stay the same with increasing bounce number? Explain your reasoning.

2. Does your observation in part (a) match Newton's Experimental Law? If not, where do you think the law fails in your experiment? 
:::

::::::


## 4. Follow Up Analysis Questions

:::Question

1. Based on *Newton's Experimental Law*, should your results change if you threw the ball at the ground? Why or why not?

2. Based on *your observations*, might your results change if you threw the ball at the ground? Why or why not?
:::

:::Question
1. Using your equation for $\epsilon$ in terms of $h$, derive an equation that gives the height of the ball on the $n$th bounce

::: Note
Hint: What is $h_2/h_1$, in terms of $\epsilon$? What is $h_3/h_2$ in terms of $\epsilon$? What is $(\frac{h_3}{h_2})(\frac{h_2}{h_1}) = \frac{h_3}{h_1}$ in terms of $\epsilon$? 
:::

2. Based on your answer to part (a) of this question, does your response to question 4 still make sense? Why or why not? 

3. In the plot containing your height v.s. bounce data, graph the equation from part (a) using the average $\epsilon$ you found in Question 8. Do you think this model fits your data well? 

4. Using the exponential curve you found, and your knowledge of projectile motion, sketch a rough graph of one ball's height over time.
:::

:::Question
1. Based on your data, from what height do you need to drop the ball for its 2nd bounce to reach a height of 28 cm (the length of a sheet of paper)?  Show your work and how you arrived at this conclusion.				
										
2. Use the Acoustic Stopwatch to determine the height of the ball on the second bounce. You may also use your phones camera as an independent form of verification.
					
3. How accurate was your prediction? Calculate the *percent discrepancy*.
					
:::

# Conclusion

::: Exercise
For Part I, write a short paragraph describing the procedure taken and any important observations for each Exercise. Be sure to summarize your results and reasons why you believe your data are precise and accurate. If you do not think your data are accurate, explain why, and how it could be fixed in a future lab.
:::

