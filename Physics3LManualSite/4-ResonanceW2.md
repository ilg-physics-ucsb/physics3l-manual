# Lab 4: Speed of Sound - Week 2
---
## Required Materials
:::Materials

- One tube from a paper towel roll, ~28 cm long. 
- A second, same-sized, paper towel tube, (may or may not have paper towels attached)
- Scissors
- Tape
- Measuring tape, meter stick, or ruler

## Optional Materials

- Laptop
- Headphones

:::

## Lab Goals

- **Construct an apparatus**
	- Create a variable-length tube
- **Data Analysis**
	- Understand the theory behind resonance
	- Determine resonance length
	- Determine frequency to be used for experiment
---


# The Experiment

## The Experiment

For this lab you will build a telescoping cardboard tube with a variable length you can manually change. Using phyphox to generate a constant-frequency tone, place your phone&rsquo;s speaker at the end of the tube. You will then adjust the length of the tube until a standing wave forms in the tube and it resonates. When this happens, you will hear a significant increase in the volume of the sound.

:::Figure
![Amplitude Plot](../imgs/lab4/AmplitudePlot.png)
::: 

Figure 7 shows a plot of sound intensity as a function of tube length for the fundamental frequency in an open-open pipe. This is an **example** plot of an adjustable pipe of approximately $1$ meter with a frequency of $171.5$ Hz playing.  Notice that there is a background volume of the speaker playing, but as the length of the pipe nears the length of 1 m, the volume increases dramatically.

The simulation below will allow you to experiment with this.
 
:::Simulation
<iframe src="https://kapawlak.github.io/PhDemoJS/Apps/TubeResonance/index.html" width="100%" height="800"></iframe>
:::

## What will you be doing?

In last week&rsquo;s lab you derived an equation for a pipe of length $L$ as a function of the number of segments $n$. 

You will play a frequency from phyphox into your tube, and by sliding the inner tube out of the inner tube (from its position all the way inside the outer tube), adjust the length of the tube until it resonates. Then you will  measure the length. Without changing the frequency, you will increase the length of your tube by sliding the inner tube further out of the outer tube. When you hit another resonance you will measure the length of tube again.  You will do this for five lengths at which the tube assembly resonates.

You will then make a plot of $L$ vs. $n$ and determine the speed of sound from that plot.

:::Question
What is the equation that you derived last week, for length as a function of the number of segments?
:::

:::Question
If you were to create a plot of $L$ vs $n$ and fit a line to it, what would the expression for the slope be?
:::

::::::Exercise
In this exercise you will determine what frequency is needed to have five resonances over the change in length of your pipe.

1. If you have a thermometer or other way of measuring the temperature inside of your room, record the value. Otherwise, assume that it is about $20^{\circ}$C inside. Then determine the speed of sound in your room based on temperature. We will call this measurement of the speed of sound $v_T$ since it is from temperature, as opposed to measurement you will be making later for resonance.

The uncertainty in the speed of sound based on temperature is given by the following:

:::Equation
$$
\delta v_T = 0.6 \delta T
$$
:::

::: Question
1. What temperature is your room, and how did you measure/estimate it?

2. What is the uncertainty in the temperature?

3. What is the speed of sound in your room with uncertainty?
:::

2. Determine the length over which you are able to adjust your pipe. Use last week&rsquo;s lab for help.

:::Question
1. What did you use to measure the length?

2. What is the length over which you can adjust your pipe (*i.e.*, the length of the inner pipe)? Include uncertainty.
:::

3. Collecting five data points means you will need five segments to fit within the tube&rsquo;s change in length. Use the same calculation you used last week to determine what frequency is needed to get five segments.

:::Question
What frequency should you use? Show your work.
:::

4. Take the frequency you calculated in Question 5 and add $100$ Hz to it. Use this frequency for the experiment.

:::Question
Why should we add $100$ Hz to the frequency that you calculated? 
Hint: What assumptions did you make when making that calculation? What about your apparatus might make it hard to get all five standing waves?
:::

::::::

::::::Exercise
In this exercise you will collect data.
Use your phone to play the frequency you found in Question $5$, and listen for resonances. When you hear a resonance, you will measure the length of your pipe. Then adjust the length and repeat.

1. Open the phyphox app and select *Tone Generator*. Enter the frequency you determined from Exercise $2$. 
2. Locate and place your phone&rsquo;s speaker on the edge of a table.
3. Put the tube right up against the phone and then hit play on the *Tone Generator* function.

:::Note
You can start with a lower volume, but if you have trouble finding the resonance you may need to increase it. 
:::

4. The sound coming out of the tube may or may not resonate. Spend some time *slowly* sliding the inner tube out. Listen closely for changes in volume.

:::Note
This can be slightly challenging to hear. If you change the tube length too quickly or too slowly, this will increase the difficulty. We have found that for a frequency of $3200$ Hz, a change in length of $2-4$ cm/s is a good speed. 
:::

5. Once you are confident that you can identify the resonances, push the inner tube completely inside the outer tube. 
6. Slide the inner tube out until you hear the first resonance. Spend a moment trying to make sure you that are really at the maximum volume by slightly adjusting the length.
7. Measure the length of your tube.

::: Question
1. Is the uncertainty larger, smaller, or the same as that for a direct length measurement of the tube? (i.e. How does the uncertainty of the length of the tube while resonating, compare to the uncertainty in your measuring tool?) **Hint:** How certain are you that you have length *exactly* at a resonate boundary condition?

2. What factors contribute to the uncertainty?

3. What is the uncertainty in your resonate length measurement?
:::

8. In a table, record the length of the tube and the segment. This first segment will just be $n=1$.
9. Repeat steps $6$ - $8$, measuring the tube at each resonance and increasing $n$ by one. Do this until you have fully extended your telescoping pipe.

9. In a table record the length of the tube and the segment. This first segment will just be $n=1$.
10. Repeat steps $6$ - $8$ measuring the tube at each resonant and increasing $n$ by one. Do this until you have fully extended your telescoping pipe.

::::::

::::::Exercise
In this exercise you will analyze your data and determine the speed of sound in your room. 

1. Create a plot of $L$ vs. $n$.
2. Fit a line to your plot.
3. Take the slope of the line, $s$, and use your answer to Question $2$ to determine the speed of sound $v_R$ as measured by resonance.

:::Question
Even though you have labeled the segments $n=1, 2, 3, 4, 5$, there are more than that number of segments in your entire pipe. 

For measuring the speed of sound, why does it not matter that we are not starting the count at the actual number of segments inside the entire length of the tube?
:::

Typically, most sound producing devices have very small uncertainties in the frequencies they produce. For the purposes of this lab, we will assume that the uncertainty in the frequency is small compared to the uncertainty in your length measurements (which will lead to larger uncertainties in your slope).

In order to find the uncertainty in the speed of sound as measured by resonance, $v_R$ that arises from the uncertainty in the slope, $s$, use the following equation: 

:::Equation
$$
\delta v_R = \frac{v_R}{s} \delta s
$$
:::

:::Question
What is the speed of sound in your room as measured by resonance? Include the uncertainty in your response.
:::

::::::



## Conclusion
:::Question
1. How does the speed of sound compare in your two measurements?

2. What is the percent difference between the two?

3. Is the difference explained by random error or systematic error? Justify your reasoning.

4. What might be some sources of systematic error in this experiment?
:::
::: Exercise
Write a short conclusion discussing what you did in this lab and what you found about the speed of sound.
:::