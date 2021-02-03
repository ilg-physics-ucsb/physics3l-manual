# Lab 1: Coefficient of Restitution Week 1
---
## Materials
You don&rsquo;t actually need these materials for this week, but if you haven&rsquo;t procured these items you need to do that before next week.
::: Materials
- Two kinds of bouncy balls
- A hard, flat surface in an open space
- Phyphox &ldquo;Acoustic Stopwatch&rdquo; or an audio recording device that shows sound amplitude
:::

## Lab Goals

- **Construct an apparatus**
	- Find two &ldquo;bouncy&rdquo; balls that can bounce off a surface at least six times.
	- Find a surface and location with plenty of room to bounce a ball.
- **Data Analysis**
	- Understand the theory behind Newton&rsquo;s Experimental Law (of restitution).
	- Generate the equations that will be used to process the data.

---

:::Note
In this lab and subsequent labs, you must show all your work and justify your answers to receive full credit. 
:::

# Theory: Kinematics, Collision and Energy Loss

You have mastered the basic kinematic relations that govern projectile motion and collisions in previous introductory physics courses. In this lab, we will investigate inelastic collisions, and energy loss to the environment.

Assume that you drop a ball from a given height, and the ball is initially at rest. The ball&rsquo;s position over time until it hits the floor can be calculated by means of the kinematics formulas for constant acceleration. These formulas will give you a fairly accurate account of the ball&rsquo;s trajectory.

::: Note
As a reminder, the kinematics formulas for motion under constant acceleration are:

$$v(t)=v_0+at$$

$$y(t)=y_0+v_0t+\frac{1}{2}at^2 , $$

where  $y_0$ and $v_0$ are the initial position and velocity, and $a$ is the constant acceleration. Depending on how you define your coordinate axis, the acceleration $a$ can be positive or negative.
:::
 Once the ball hits the floor and bounces, it loses some amount of its total energy. This is evidenced by the fact that the ball will not bounce for the rest of eternity &ndash; its successive heights quickly decrease until the ball comes to rest.

With this phenomenon in mind, we can now ask about how to characterize this energy loss, if we can predict the successive bounce heights, and what the mathematical description of this kind of motion looks like. Can we develop equations that will be predictive?


## 1. The Coefficient of Restitution
When the ball from our previous example bounces off the floor, it loses energy during the collision. Your first observation may be that the speed of the ball has decreased. This observation is what led Newton to propose what is now known as &ldquo;Newton&rsquo;s Experimental Law.&rdquo;

:::Note
**Newton&rsquo;s Experimental Law** states that for a specified pair of bodies in collision, the ratio of the final relative speed to initial relative speed is always the same.

The ratio of these two speeds is called the coefficient of restitution, and has the symbol $\epsilon$. This value is constant for a given pair of bodies.
:::

In our ball drop experiment, one of these bodies is &ldquo;Earth&rdquo;, and the other is our ball. Since we are naturally measuring our ball&rsquo;s velocity with respect to Earth (with the Earth&rsquo;s velocity change due to a tennis ball being negligible, of course!), we obtain:

:::Equation
$$
\epsilon = v_f/v_i ,
$$
:::

where $v_f$ is the speed of the ball after the bounce, and $v_i$ is the speed of the ball before the impact with the floor. Note that $\epsilon$ is defined in terms of speed, not velocity, so it will always be positive.

In ideal circumstances, the coefficient of restitution is the same for all collisions between these two bodies (our particular ball and the Earth). The $\epsilon$ here is our definition of the [coefficient of restitution](https://en.wikipedia.org/wiki/Coefficient_of_restitution). 

# The Experiment

## 1. Overview
In this lab we will investigate Newton&rsquo;s Experimental Law by observing a ball bounce off the floor multiple times. Simulation 1 provides a simplified demonstration of the lab. The simulation shows the height of the ball (as measured from the bottom of the ball) over time. You can adjust the coefficient of restitution to see how different values of $\epsilon$ will affect the ball&rsquo;s bounces.

:::Simulation

1. Press the &ldquo;Play&rdquo; button by the $t$ slider. Watch what happens.
2. Adjust the $\epsilon$ slider, slide $t$ back to $0$, and hit play again.

<iframe src="https://www.desmos.com/calculator/1hpdupmzuc" width="100%" height="800px" style="border: 1px solid #ccc" frameborder=3px></iframe>
:::

We will calculate $\epsilon$ for two different balls, understand how energy is lost to the environment during each collision, and use our results to predict subsequent bounce heights.

While your first instinct may be to make a video recording of a ball bouncing, we will approach these tasks in a perhaps unexpected way: we will instead use only the sound of the the ball hitting the floor to make our measurements.

The reason for doing this is quite simple: sound data are &ldquo;cheap&rdquo; and easy to analyze. Unlike video, which requires an immense number of pixels (and thus data) in order to obtain a good sampling rate and accuracy, sound data are one dimensional. This enables us to have a suitably fast sampling rate to make precise measurements, with far fewer data than would be necessary for video. In this experiment, we really need only a few numbers: the times between bounces of the ball. We can calculate all other quantities of interest by knowing only the times between bounces. Sound is more than adequate for this task, and video would waste resources on capturing information about the entire environment, colors, lighting etc., which we will ultimately toss out.

This approach is actually critical to real experimental physics: often experiments are limited by data quality and equipment costs, so a bit of creative problem solving goes a long way in a real lab. Measure only what you need to!

A brief demonstration of the data collection portion of the lab can be seen in Video 1.

:::Video
![Ball Being Dropped](../imgs/lab1/droppingball.gif)
:::

:::Note
**Summary**

- You will drop a ball and use Phyphox to record the time between two bounces (the &ldquo;time of flight&rdquo;).
- From the time of flight you will calculate the coefficient of restitution, maximum height per bounce, and the percent energy loss per bounce.
- You will use the three calculated values above to check if your ball obeys Newton&rsquo;s Experimental Law.
- You will use your results to make a prediction about the height of the ball on its second bounce and verify your prediction.

:::

:::Note
In the following three sections you will get prepared to calculate the coefficient of restitution, the maximum height of the bounce, and the percent energy loss in week 2 of this lab.
:::


## 2. Time of flight

Consider a ball being dropped from a height $h_{0}$ above the floor. 

The time between subsequent bounces will be referred to as **time of flight**. The time between the first bounce and second bounce will be denoted by $t_1$, the time between the second bounce and third bounce will be denoted by $t_2$, and in general, the time between the $n\rm^{th}$ and $(n+1)\rm^{th}$ bounce will be denoted by $t_n$.

::::::Exercise
We want to find the coefficient of restitution $\epsilon$ between the ball and the floor.  We will be able to measure the time of flight between subsequent bounces, but not the velocities before and after each impact.

:::Question
1. Using the kinematics equation for position, find a relationship between the time of flight $t_n$ and the velocity of the ball after the $n\rm^{th}$ bounce. You should obtain a quadratic equation that has two solutions for the time $t_n$, but only one of them represents the time of flight.

2. Using the kinematics equation for velocity and the relationship determined in the previous step, find the relationship between the velocity right after the $n\rm^{th}$ bounce and the velocity right before the $(n+1)\rm^{th}$ bounce?

3. Given your answers to the previous parts of this question and the definition of $\epsilon$, find the coefficient of restitution $\epsilon$ in terms of the subsequent times of flight $t_n$ and $t_{n+1}$.
:::
::::::

:::Note
The times of flight between bounces are the only raw data you will collect. 
:::

## 3. Maximum height after each bounce
After the ball is initially dropped from height $h_0$ and bounces the first time, it reaches a **maximum height** $h_{1}$. Subsequent bounces achieve maximum heights $h_2, h_3, ...$. After the $n\rm^{th}$ bounce, the ball reaches maximum height $h_n$.

:::Figure
![Bounces](../imgs/lab1/bounces_plot.png)
:::

::::::Exercise 
We would like to predict the maximum height that the ball reaches after each bounce.

:::Question
Using kinematics, find the maximum height $h_n$ in terms of the time of flight $t_n$.

:::
Now let us try to construct a mathematical formula for the maximum heights $h_n$ as a function of the bounce number $n$.


:::Question
1. Rewrite the coefficient of restitution $\epsilon$ in terms of the consecutive maximum heights $h_n$ and $h_{n+1}$.

2. Using your equation for $\epsilon$ in terms of maximum bounce heights, derive an equation that gives the height of the ball after the $n\rm^{th}$ bounce in terms of the maximum height $h_1$ and $\epsilon$. 

**Hint**: What is $h_2/h_1$  in terms of $\epsilon$? What is $h_3/h_2$ in terms of $\epsilon$? What is $(\frac{h_3}{h_2})(\frac{h_2}{h_1}) = \frac{h_3}{h_1}$ in terms of  $\epsilon$?
:::
::::::

Notice that we don&rsquo;t have any information before the first bounce, so we cannot determine $h_0$ or $t_0$.

## 4. Energy loss during collisions
The coefficient of restitution can be thought of as a measure of the energy lost during the collision, since the velocity of the ball has decreased, and $\epsilon$ is a measure of the change in velocities.

::::::Exercise
The ball loses energy only during the collisions. Energy is conserved between collisions. We will denote the total energy of the ball after the first collision as $E_1$, the total energy of the ball after the second collision as $E_2$, and in general, $E_n$ will represent the total energy of the ball after the $n\rm^{th}$ collision.

Consider the floor to be the reference for zero potential energy.

:::Question
1. Find the coefficient of restitution in terms of the ball&rsquo;s kinetic energy just before and just after the $n\rm^{th}$ collision ($n\geq2$).

2. If the coefficient of restitution is $\epsilon=0$, what does that imply about the energy lost during the collision? 

3. If the coefficient of restitution is $\epsilon=1$, what does that imply about the energy lost during the collision? 
:::

We know that the total energy of the ball is purely kinetic when it bounces off the floor, and the energy is purely gravitational when the ball reaches maximum bounce height.

We will focus on the percent energy loss during each collision. The percent energy loss is the energy lost during the collision divided by the initial energy of the ball.
The percent energy lost during the $n\rm^{th}$ collision is denoted by $PEL_n$.

:::Equation
$$PEL_n=\frac{E_{n-1}-E_{n}}{E_{n-1}}\times 100$$
:::

:::Question
Derive an equation that determines the percent energy loss after the $n$th bounce in terms of the maximum bounce heights $h_{n}$ and $h_{n-1}$. 
:::

::::::

Answer the following numerical question to make sure you know how to calculate the relevant quantities for your experiment:

:::Question

1.  If the time between two consecutive bounces was 2 seconds, determine the maximum height reached by the ball in this period.

2.  If the time to the next consecutive bounce was 1 second, calculate the maximum height during this time period.

3. Calculate the percent energy lost after the second bounce, using the heights determined above.

4. What is the coefficient of restitution of this ball when it bounces off the floor?
:::


## 5. Preparation

:::::: Exercise
When you collect data for the lab next week, it will be preferable for you to have two types of bouncy balls. Some examples include:

- Tennis Ball
- Marble
- Basketball
- Ping-pong Ball
- Super Bouncy Ball

If you absolutely can&rsquo;t find two types of bouncy balls, then you can use a single ball on two different surfaces.

::: Question
Take a picture of your two bouncy balls (or ball and two surfaces) and include it in your lab report.
:::
::::::

Be sure that you can get access to and use the &ldquo;Acoustic Stopwatch&rdquo; module. This module conveniently reports the time between &ldquo;loud&rdquo; sounds, so you don&rsquo;t even have to look at the graphs yourself.



# Conclusion

::: Exercise
1. Give a short summary of Newton&rsquo;s Experimental Law. 
2. Give a quick summary of the important parts of this lab.
:::
