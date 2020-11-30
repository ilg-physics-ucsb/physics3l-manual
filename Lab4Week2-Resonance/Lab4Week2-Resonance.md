# Lab 4: Speed of Sound - Week 2
---
### All Materials Needed:
- One tube from a paper towel roll approximately $28$ cm long. 
- A second paper towel tube of the same size (may or may not have paper towels attached)
- Scissors
- Tape
- Measuring tape, meter stick, or ruler

### Optional Materials

- Laptop
- Headphones

### Lab Goals:
- ** Construct an apparatus **
	- Create a variable-length tube
- ** Data Analysis **
	- Measure the speed of sound in your room.
---

# Part I: Building the Apparatus

::: Exercise

1. Start by collecting all of the materials listed at the top of the lab.

::: Figure:Figure
![Image of Materials](imgs/Materials.jpg)
:::

::: Note
If you don't have paper towel rolls, you can tape multiple toilet paper rolls together or use a different type of cardboard tube. You can use one from a roll of aluminum foil or saran wrap. In a pinch, rolled up printer paper, card stock, or cardboard should also work. You just need two that are the same diameter or one that fits perfectly inside the other already. If you already have a tube that fits perfectly inside of another one, you are done with the apparatus. 
:::
#####
2. Take your empty cardboard tube, and cut it down its length.

:::Figure:Figure
:::row
:::column
![Cutting the Tube](imgs/CuttingTube.jpg)
Cut the tube down its length.
:::

:::column
![Cutting the Tube](imgs/CutTube.jpg)
This is what it should look like after being cut.
:::
:::
:::
#####
3. Fold one part of the seem under the other as shown in the figure below.

:::Figure:Figure
![Rolled Over Tube](imgs/RolledOverTube.jpg)
:::
#####
4. Slide the cut tube into your second tube. Leave approximately a tape's width sticking out of the outer tube.
5. Wrap the portion of the inner tube that is sticking out of the outer tube in tape. Don't wrap it multiple times and don't wrap it so tightly that it reduces the size of the tube too much. You want it to fit snugly inside the other tube, while allowing it to slide in and out fairly easily.

::: Figure:Figure
:::row
:::column
![Tube Inside Other Tube](imgs/TubeStickingOut.jpg)
Make sure to leave a little piece sticking out.
:::

:::column
![Tape Wrapped End](imgs/SealedEnd.jpg)
Don't wrap the tape too tightly.
:::
:::
:::
#####
6. Push the other end of the inner tube out of the other side of the outer tube and do the same thing. Once the inner tube is taped on both ends, slide the inner tube out of the outer tube.
7. Use tape to secure a few more sections along the tube to ensure it keeps its cylindrical shape.

:::Figure:Figure
:::row
:::column
![Roll pulled out](imgs/SealedTube1.jpg)
This is what it should look like after Step $6$.
:::

:::column
![Finished Inner Roll](imgs/SealedTube2.jpg)
This is the completed inner tube.
:::
:::
:::
#####
8. Slide the inner tube into the outer tube. You are done!

:::Figure:Figure
![Completed Apparatus](imgs/CompletedTube.jpg)
Finished telescoping tube.
:::

:::


# Part II: The Experiment



## The Experiment

For this lab you will build a telescoping cardboard tube with a variable length you can manually change. Using Phyphox to generate a constant-frequency tone, place your phone's speaker at the end of the tube. You will then adjust the length of the tube until a standing wave forms in the tube and it resonates. When this happens, you will hear a significant increase in the volume of the sound.

:::Figure:Figure
![Amplitude Plot](imgs/AmplitudePlot.png)
::: 

Figure 7 shows is a sketch of sound intensity as a function of tube length for the fundamental frequency in an open-open pipe. This is an **example** plot of an adjustable pipe of approximately $1$ meter with a frequency of $171.5$ Hz playing.  Notice there is a background volume of the speaker playing, but as the length of the pipe nears the length of 1 m the volume increases dramatically.

The simulation below will allow you to experiment with this.
 
:::Figure:Simulation
embed src="https://kapawlak.github.io/PhDemoJS/Apps/TubeResonance/index.html" width="100%" height="800"
:::

### What will you be doing?

In last weeks lab you derived an equation for a pipe of length $L$ as a function of the number of segments $n$. 

You will play a frequency from Phyphox into your tube and adjust its length until it resonates. Then you will  measure the length. Without changing the frequency you will increase the length of your tube by sliding the inner tube out of the outer tube. When you hit another resonance you will measure the length of tube again.

You will then make a plot of $L$ vs $n$ and determine the speed of sound from that plot.

:::Question
What is the equation you derived last week that has length as a function of number of segments?
:::

:::Question
If you were to create a plot of $L$ vs $n$ and fit a line to it, what would the expression for the slope be?
:::

:::Exercise
In this exercise you will determine what frequency is needed to have five resonances over the change in length of your pipe.

1. If you have a thermometer or other way of measuring the temperature inside of your room, record the value. Otherwise, assume it is about $20^{\circ}$C inside. Then determine the speed of sound in your room.

The uncertainty in the speed of sound based on temperature is given by the following:

:::Figure:Equation
$$
\delta v_s = 0.6 \delta T
$$
:::

::: Question
a) What temperature is your room and how did you measure/estimate it?

b) What is the uncertainty in the temperature?

c) What is the speed of sound in your room with uncertainty?
:::

2. Determine the length over which you are able to adjust your pipe. Use last week's lab for help.

:::Question
a) What did you use to measure the length?

b) What is the length over which you can adjust your pipe (i.e. the length of the inner pipe)? Include uncertainty.
:::

3. Collecting five data points means you will need five segments to be inside of the tube's change in length. Use the same calculation used last week to determine what frequency is needed to get five segments.

:::Question
What frequency should you use? Show your work.
:::

4. Take the frequency  calculated in Question 5 and add $100$ Hz to it. Use this frequency for the experiment.

:::Question
Why should we add $100$ Hz to the frequency you calculated? 
Hint: What assumptions did you make when making that calculation? What about your apparatus might make it hard to get all five standing waves?
:::

:::

:::Exercise
In this exercise you will collect data.
Use your phone to play the frequency you found in Question $5$ and listen for resonances. When you hear a resonance you will measure the length of your pipe. Then adjust the length and repeat.

1. Open the Phyphox app and select *Tone Generator*. Put the frequency you determined from Exercise $2$. 
2. Locate and place your phone's speaker on the edge of a table.
3. Put the tube right up against the phone and then hit play on the *Tone Generator* function.

:::Note
You can start with a lower volume, but if you have trouble finding the resonance you may need to increase it. 
:::

4. The sound coming out of the tube may or may resonate. Spend some time *slowly* sliding the inner tube out. Listen closely for changes in volume.

:::Note
This can be slightly challenging to hear. If you move it too fast or slow it will be increase the difficulty. We have found for a frequency of $3200$ Hz that moving it $2-4$ cm/s is a good speed.  
:::

5. Once you are confident that you can identify the resonances, push the inner tube completely inside the outer tube. 
6. Slide the inner tube out until you hear the first resonance. Spend a moment trying to make sure you are really at the maximum volume by slightly adjusting the length.
7. Measure the length of your tube.
8. In a table record the length of the tube and the segment. This first segment will just be $n=1$.
9. Repeat steps $6$ - $8$ measuring the tube at each resonant and increasing $n$ by one. Do this until you have fully extended your telescoping pipe.

::: Question
a) What is the uncertainty in your resonate length measurement?

b) Is it larger, smaller, or the same as a direct measurement of the tube?

c) What factors contribute to the uncertainty?
:::

:::

:::Exercise
In this exercise you will analyze your data and determine the speed of sound in your room. 

1. Create a plot of $L$ vs $n$.
2. Fit a line to your plot.
3. Get the slope of the line and use your answer to Question $1$ to determine the speed of sound.

:::Question
Even though you have labeled the segments $n=1,2,3,4,5$, there are more than that number of segments in your entire pipe. 

For measuring the speed of sound, why does it not matter that we are not starting the count at the actual number of segments inside of the entire tube?
:::

Typically, most sound producing devices have very small uncertainties in the frequencies they produce. For the purposes of this lab, we will assume the uncertainty in the frequency is small compared to the uncertainty in your length measurements (which will lead to larger uncertainties in your slope).

In order to propagate the error from the slope to the speed of sound, $v_s$ use the following equation: 

:::Figure:Equation
$$
\delta v_s = \frac{v_s}{s} \delta s
$$
:::

:::Question
What is the speed of sound in your room as measured by resonance? Include the uncertainty in your response.
:::

:::



## Conclusion
:::Question
a) How does the speed of sound compare in your two measurements?

b) What is the percent difference between the two?

c) Is the difference explained by random error or systematic error? Justify your reasoning.

d) What might be some sources of systematic error in this experiment?
:::
::: Exercise
Write a short conclusion discussing what you did in this lab and what you found about the speed of sound.
:::