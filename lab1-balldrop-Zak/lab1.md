# Lab 1: Coefficient of Restitution Week 1
---
### All Materials Needed:
- Two kinds of bouncy balls
- A hard, flat surface in an open space
- Phyphox "Acoustic Stopwatch" or an audio recording device that shows sound amplitude

### Lab Goals:
- Find a two objects to drop and a place to drop them.
- Learn how to use equations in a spreadsheet.
- Understand the prerequisite theory to process the data. 

---

# Part I: Kinematics, Collision and Energy Loss

You have likely mastered the basic kinematic relations that govern projectile motion and collisions in previous introductory physics courses. In this lab, we will now investigate inelastic collisions, and energy loss to the environment.

####
When you drop a ball from rest, you can calculate its height over time until it hits the floor: the usual routine of applying Newton's equations for constant acceleration will give you a fairly accurate account of the ball's trajectory. Once the ball hits the floor, however, it loses some amount of its total energy. This is evidenced by the fact that the ball will not bounce for the rest of eternity --- its successive heights quickly decline until it comes to rest.

####
With this phenomena in mind, we can now ask about how to characterize this energy loss, if we can predict the successive bounce heights, and what the mathematical description of this kind of motion looks like. Can we develop equations which will be predictive, i.e. precise and accurate?

####

:::Question
(a) You drop a 0.1 kg ball from a height of 1m above the floor. Write the equation that gives the ball's height over time, until it hits the floor. 

(b) What is the equation for potential energy of the ball as a function of height? The floor is the reference for zero potential energy.

(c) What is the total energy of the the ball as function of height, if it was dropped from a height of $h_{max}$.

(d) Using (c) and (b) and the conservation of energy, what is the kinetic energy as a function of height?
:::

####
## 1. The Coefficient of Restitution
When a ball bounces, and hence loses energy, your first observation may be that the speed of the ball is reduced. This observation is what led Newton to propose "Newton's Experimental Law", which is now characterized by a quantity known as the coefficient of restitution. 

####

**Newton's Experimental Law** states the following:  given a pair of bodies in collision, the ratio of final relative speed to initial relative speed is always the same.
####

In our ball drop experiment, one of these bodies is "Earth" and the other is our ball. Since we are naturally measuring our ball's velocity with respect to Earth (with the Earth's velocity change due to a tennis ball being negligible, of course!), we obtain the following mathematical sentence:

:::Figure:Equation
$$
\epsilon = v_f/v_0
$$
:::

Which, in ideal circumstances, applies to all collisions between these two bodies. The $\epsilon$ here is our definition of the [coefficient of restitution](https://en.wikipedia.org/wiki/Coefficient_of_restitution). 

:::Question
(a) Rewrite equation 1 in terms of the ball's kinetic energy **just before** and **just after** collision.

(b) Using your answer to Question 1.d, rewrite your answer for Question 2.a, in terms of the height of the ball. **Hint:** The max height of the ball will change after it bounces off the ground. Therefore you need a new max height.

(c) From Question 1, if $\epsilon=0$, what is the ball's energy after the first bounce? What is its next maximum height?

(d) If $\epsilon=1$, what is the ball's energy after the first bounce? What is its next maximum height?
:::

# The Experiment
## 1. Overview
Our job in this lab will be to verify Newton's Experimental Law, calculate $\epsilon$ for different balls, hypothesize what effects this constant, and use our results to make & test a prediction. While your first instinct may be to make a video recording of a ball bouncing, we will approach these tasks in a, perhaps, unexpected way: we will instead use only the sound of the the ball hitting the floor to make our measurements.

####
The reason for doing this is quite simple: sound data are "cheap" and easy to analyze. Unlike video, which requires an immense increase in pixels (and thus data) in order to improve sampling rate & accuracy, sound data is one dimensional, letting us have a suitably fast sampling rate to make precise measurements. In this experiment, we really only need a few numbers: the times that the ball hits the ground-- we can calculate all other quantities of interest from this. Sound is more than adequate for this task, and video would waste resources on capturing information about the entire environment, colors, lighting etc., which we will ultimately toss out.

####

This kind of thinking is actually critical to real experimental physics: often experiments are limited by data quality and equipment costs, so a bit of creative problem solving goes a long way in a real lab! Only measure what you need to!

####
Be sure that you can use and access the "Acoustic Stopwatch" module. This module conveniently reports the time between "loud" sounds, so you don't even have to look at the graphs yourself. 

####

Note that there is an "Inelastic Collision" experiment module bundled with Phyphox, but it doesn't give you all the data needed for this lab, and our testing has suggested it is *less* accurate than the procedure given below. In other words, don't use it :)

A brief demonstration of the data collection portion of the lab can be seen in Video 1. 

:::Figure:Video
![Ball Being Dropped](imgs/droppingball.gif)
:::

:::Question
Answer the following "practice" questions to make sure you know how to calculate the relevant quantities for your experiment:

(a) Say the time between two consecutive bounces was 2 seconds. Using your knowledge of basic kinematics, determine the max height reached in this period. 

(b) What is the total energy *density* of the ball during this period? This is just the energy divided by the mass (so you don't have to worry about weighing it). Give your answer with appropriate units

(c) If the time to the next consecutive bounce was 1 second calculate the max height and energy density of the ball during this time period.

(d) Calculate the percent energy lost after the second bounce.

(e) Do you think this ball is a "good" bouncer? Why or why not?
:::

## 2. Using Equations in Spreadsheets

This week you won't need to know how to use equations in a spreadsheet, but next week you will. If you are unfamiliar with how to do this, watch the video below.

:::Figure:Video
!(https://www.youtube.com/watch?v=Zi3H_8JV3jY)
:::


## 3. Preparation

::: Exercise
When you collect data for the lab next week you will preferably need two types of bouncy balls. Some examples include:

- Tennis Ball
- Marble
- Basketball
- Ping-pong Ball
- Super Bouncy Ball

If you absolutely can't find two types of bouncy balls, then you can use a single ball on two different surfaces.

::: Question
Take a picture of your two bouncy balls (or ball and two surfaces) and include it in your lab report.
:::
:::

## Part III: Conclusion

::: Exercise
1. Give a short summary of Newton's Experimental Law. 
2. Give a quick summary of the import parts of this lab.
:::
