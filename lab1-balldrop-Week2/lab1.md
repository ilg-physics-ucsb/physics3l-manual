# Lab 1: Coefficient of Restitution - Week 2
---
### All Materials Needed:
- Two kinds of bouncy balls
- A hard, flat surface in an open space
- Phyphox "Acoustic Stopwatch" or an audio recording device that shows sound amplitude

### Lab Goals:
- Learn to use Phyphox for data collection
- Investigate the properties of inelastic collisions
- Familiarize yourself with experimental error

---

# Part I: The Experiment
## 1. Overview and Pre-lab
Our job in this lab will be to verify Newton's Experimental Law, calculate $\epsilon$ for different balls, hypothesize what effects this constant, and use our results to make & test a prediction. While your first instinct may be to make a video recording of a ball bouncing, we will approach these tasks in a, perhaps, unexpected way: we will instead use only the sound of the the ball hitting the floor to make our measurements.

####
The reason for doing this is quite simple: sound data are "cheap" and easy to analyze. Unlike video, which requires an immense increase in pixels (and thus data) in order to improve sampling rate & accuracy, sound data is one dimensional, letting us have a suitably fast sampling rate to make precise measurements. In this experiment, we really only need a few numbers: the times that the ball hits the ground-- we can calculate all other quantities of interest from this. Sound is more than adequate for this task, and video would waste resources on capturing information about the entire environment, colors, lighting etc., which we will ultimately toss out.

####

This kind of thinking is actually critical to real experimental physics: often experiments are limited by data quality and equipment costs, so a bit of creative problem solving goes a long way in a real lab! Only measure what you need to!

####
Before moving on to the procedure, be sure that you have downloaded and installed the Phyphox app on your phone, and that you can use and access the "Acoustic Stopwatch" module. This module conveniently reports the time between "loud" sounds, so you don't even have to look at the graphs yourself. 

####

Note that there is an "Inelastic Collision" experiment module bundled with Phyphox, but it doesn't give you all the data needed for this lab, and our testing has suggested it is *less* accurate than the procedure given below. In other words, don't use it :)

:::Figure:Video
![Ball Being Dropped](imgs/droppingball.gif)
:::

## 2. Using sound to measure the coefficient of restitution

---
### Materials needed:
- Two kinds of bouncy balls
- A hard, flat surface in an open space
- Phyphox "Acoustic Stopwatch" or an audio recording device that shows sound amplitude
---





::: Exercise
After you have downloaded and installed phyphox, and have gathered your materials, follow the steps below to perform your experiment and collect data:

1. Open up your acoustic timer in "sequence mode". This mode will record the times between 5 successive sounds.
2. In your large, open area, place your phone on the ground with the mic pointing down. For example, to accomplish this, I propped my phone up against the wall of my living room. 
3. Hold the ball at the height of a nearby marker, such as a doorknob. It is not very important that the height is equal each run, but its nice for your data to be similar.
4. Press "Reset" on the app to clear any accidental data
5. Drop the ball and let 5 times register. If your ball knocks into an object or travels too far away, you will have to redo that run. Be sure to double check your times and make sure they are monotonically decreasing
6. Record these times somewhere, and repeat the procedure for each ball at least 5 times.

:::Question
In measuring $\epsilon$, why is it not very important that the ball height is exactly the same each run? Hint: review "Newton's Experimental Law".
:::

:::


## 3. Data Analysis

To analyze the data, it is probably easiest to use a spreadsheet program. Some great options are google sheets or excel if you have access to the software. You will be asked to turn in this file with your write-up at the end of the lab, so be sure to follow the instructions.

####

For each ball you should have 5 runs, with 5 times each, for a total of 25 data points. We will use these data points to calculate some quantities of interest, including the max bounce height, the energy lost per bounce, and the coefficient of restitution.

:::Exercise
Height v.s. Bounces:

In a spreadsheet, follow the instructions listed below:

1. For one of your balls, make a table such as the one below. Title this table "Time of Flight during Bounce"
AVOCADO
2. Now make another table with 5 columns and 5 rows, and calculate the max bounce height for each of the 5 times in each run. Title this table "Max Height Each Bounce"
3. Plot these sets of data on a graph where the y-axis is the ball's max height and the x-axis is the bounce number. What do the shapes of these graphs look like? Try fitting the data with functions.
4. Repeat this with the data from your other ball.

:::


:::Exercise
Energy Loss v.s. Bounces:
:::Question
Derive an equation that determines the energy lost after a bounce that *only* uses the max heights. Show any relevant work.
:::

1. Make another table that calculates the energy lost after each bounce using the equation derived above. Title this table "Energy Lost Each Bounce"
AVOCADO
2. Plot these sets of data on a graph where the y-axis is the ball's energy lost and the x-axis is the bounce number. 
3. Repeat this with the data from your other ball.
:::Question
(a) For each ball, does the energy lost seem to increase, decrease, or stay the same? Explain your reasoning.

(b) Does your observation in part (a) match Newton's Experimental Law? If not, where do you think the law fails in your experiment? 
:::

:::


:::Exercise
Coefficient of Restitution

1. Finally make a table to calculate the measured coefficient of restitution for each bounce. 
2. Calculate the average across bounces and runs using the spreadsheet AVERAGE function
3. Similarly, calculate the standard deviation of your data across bounces and runs using the STDEV function.
4. Calculate the total average over all 5 x 4= 20 measurements of $\epsilon$
5. Repeat this with the data from your other ball.

:::Question
(a) For each ball, does the energy lost seem to increase, decrease, or stay the same? Explain your reasoning.

(b) Does your observation in part (a) match Newton's Experimental Law? If not, where do you think the law fails in your experiment? 
:::

:::


## 3. Follow Up Analysis Questions

:::Question
(a) Is the standard deviation of $\epsilon$ large across bounces in a single run or the same bounce across different runs? 

(b) Why do you think this is true? 
:::

:::Question
Would your results change if you threw the ball at the ground? Why or why not?
:::

:::Question
(a) Using your equation for $\epsilon$ in terms of $h$, derive an equation that gives the height of the ball on the $n$th bounce

(b) AVOCADO

(c) Using the exponential curve you found, and your knowledge of projectile motion, sketch a rough graph of one ball's height over time.
:::

:::Question
(a) Based on your data, from what height do you need to drop the ball for its 2nd bounce to reach a height of 1 m?  Show your work and how you arrived at this conclusion.				
					
(b) Mark your predicted height as well as 1 m somewhere and test your theory using the camera on your phone.  					
					
					
(c) How accurate was your prediction? Did you lose more energy than expected? Why do you think that is?					
					
:::

## Part II: Write-up
 - For Part I, write a short paragraph describing the procedure taken and any important observations for each Exercise. Be sure to summarize your results and reasons why you believe your data are precise and accurate. If you do not think your data are accurate, explain why, and how it could be fixed in a future lab.
 - You are encouraged to attach images of your plots,  data, and setup -- doing so may allow you to regain partial or full credit even if your experiment fails.
 - At the end of your write-up, please include the answers to all questions, clearly numbered. Show your work if applicable.