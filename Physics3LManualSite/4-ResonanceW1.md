# Lab 4: Speed of Sound - Week 1
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

# Theory: Sound, Waves, & Resonance

## Sound

Sound is caused by a disturbance in the surrounding medium — air. Air is an elastic medium, meaning that the air particles experience a restoring force which pushes them back towards their equilibrium positions. When music is playing on a speaker, the speaker vibrates, alternately compressing and expanding the volume in front of it, thus periodically pushing the air molecules.

When the speaker moves outward, it pushes out surrounding air molecules, and that push causes a chain of disturbances that propagate through the air. When the speaker moves inward, it creates more space for air particles to move, starting with the air molecules closest to the speaker. This is known as positive and negative displacement.

:::Figure
![SpeakerOut](../imgs/lab4/SoundPulse.gif)
:::

Figure 1 shows column of air set in motion by a speaker at the left vibrating at some frequency. You can see compression waves traveling to the right. Notice, though, that any one particle (some have been highlighted in red) doesn&rsquo;t actually move to the right but just oscillates back and forth around its equilibrium position.

## Speed of Sound

The speed of sound results from the inertia and elastic properties of the material it travels through. The greater the mass of individual particles of the medium, the less responsive they are to the interactions between neighboring particles, and the slower the wave. All other things being equal, a sound wave travels faster in a less dense material than in a more dense material. For instance, a sound wave travels nearly three times faster in Helium as it does in air. A sound wave travels faster in a medium with greater restoring force than in one that provides a lesser restoring force. Sound waves travel extremely fast in metals, which have stiff crystal structures that quickly restore individual particles to their equilibrium positions.

Sound waves propagate at velocity $v_s$. The speed of propagation is entirely determined by the medium through which the wave propagates. The speed of sound in air is also influenced by the temperature of the air, the air pressure, and the relative humidity. If we consider dry air (zero relative humidity) and atmospheric pressure, the dependence of the speed of sound on the temperature of the air can be expressed by the following equation:

:::Equation
$$
v_s = 331+ 0.6  T
$$
:::

where T is the temperature of the air in degrees Celsius.

:::Question
What are the units of the 0.6 constant in Equation 1?
:::

:::Question speedTemp
If it is $20^\circ$C in your room what is the speed of sound?
:::


## Speed of Waves

The speed of waves is a slightly tricky concept. It does not refer to how fast any one given particle is moving. Rather, it refers to how fast the wave &ndash; the disturbance &ndash; propagates through the medium. If you were to pick a point on the wave, say one of the positive displacements, and watch it move, the speed of its progress would be the speed of sound. It is the measure of how fast the disturbance moves through a medium. 

The speed of the wave is determined by the frequency, $f$, and the wavelength, $\lambda$. The equation is:

:::Equation
$$
v=\lambda f
$$
:::

:::Question
If you heard a 440-Hz A note played on a guitar in your room right now, what would the wavelength be? 
:::

:::Question
If the frequency of the sound increases, what happens to the wavelength? Justify your answer.
:::


## Resonance


The word resonance comes from Latin words for ‘echo’ and ‘resound’. Resonance is illustrated by a swing on a playground; if you push a friend on the swing and wait for it to return to you, the swing will fall into a rhythm, a natural interval. As long as you push the swing in time with its natural frequency, the swing can go quite high. The natural frequency is the frequency at which it would oscillate if there were no resistive forces present. If,  however, you attempt to push the swing at a frequency that is different from this natural frequency, the maximum height of the swing will be much lower  (and you might hurt yourself).

As you might guess from the swing analogy, resonance occurs when you drive a system at its natural frequency of oscillation.  In the case of the paper towel tube apparatus that you are about to make, this means setting the conditions so that you form a **standing wave** inside the tube. That is, a wave that forms a pattern of nodes and antinodes that is fixed in space. Antinodes are regions of maximum amplitude, and nodes are points where the amplitude is zero. A depiction of a standing wave, with nodes and anti-node labeled can be seen in Figure 2 below.

:::Figure
![Image of nodes](../imgs/lab4/Nodes.png)
:::

Such a pattern is formed by the superposition of the wave with its reflection at the end(s) of the tube, and can happen only if the phase relationship between the wave and its reflection(s) is appropriate. At an open end, the reflected wave has the same phase as the outgoing wave. At a closed end, the reflected wave is 180&deg; out of phase with the outgoing wave. Only if the reflections occur at the right points in the sound wave, can a standing wave form.

You can produce a standing wave, and therefore make something resonate, when you meet the proper boundary conditions. For a standing wave to form, there needs to be an antinode at any open end of a pipe, and a node at any closed end.

To get resonance conditions we can do this in two ways. 

1. We can adjust the driving frequency. Since the speed of sound is constant at a particular temperature, adjusting the frequency changes the wavelength. When the wavelength is such that it meets the boundary conditions, the tube will resonate.
2. We can adjust the tube length while keeping the frequency constant. At some length(s), the wave inside the tube will match the boundary conditions, and the tube will resonate. In this lab we will call the part of the standing wave between two resonant boundary conditions a **segment**. i.e. For an open-open pipe this would be the part of the wave between two antinodes.

The lowest resonant frequency is called the **fundamental frequency**, or the 1$\rm^{st}$ harmonic. A harmonic is a positive integer multiple of the fundamental frequency.  By increasing the frequency, and thus shortening the wavelength, we can find higher harmonics for which the tube resonates.

Air columns in cylinders for which both ends are open can produce all harmonics of the fundamental frequency. They allow all harmonics that have an antinode at each end of the cylinder. Cylinders with one closed end and one open end produce only those harmonics that have a node at the closed end and an antinode at the open end.

In the simulation below you can investigate what happens when you change the parameters of an open-open tube. You can adjust the length until you see resonance under any given conditions. You can change the speed of sound in the medium, the driving frequency, and the amplitude of  the wave. When you hit a resonant condition you should see that an orange "Resonance" appear below the wavelength. Finally you can move forward in time to see the wave oscillate. 

Use this to gain some intuition about how different parameter will affect when the tube resonates.

:::Simulation
<iframe sandbox="allow-scripts" src="https://www.desmos.com/calculator/xqvx4ovjj0" width="100%" height="800px" style="border: 1px solid #ccc" frameborder=0></iframe>
:::

::::::Exercise

:::Figure
![Resonant Conditions](../imgs/lab4/ResonanceTubes.png)
:::

As noted above, the boundary conditions for a standing wave require that there is a node at any closed end and an antinode at any open end. In Figure 3, the top tube is open on both ends (open-open), and the bottom tube is open at one end and closed (open-closed) at the other. Drawn in each is the first standing wave that can form in either tube. 



:::Question
1. What is the wavelength for the fundamental frequency of an open-open tube in terms of the tube length $L$?

2. What is the wavelength for the fundamental frequency of an open-closed tube in terms of the tube length $L$?
:::

For this lab we will only be adjusting the length of the pipe, and therefore we will focus on the second way to make something resonate described above. 

For a tube with both ends open, we will say that there is one segment inside the tube resonating at the fundamental. For this exercise, we will call this length $L_1$.

:::Question

1. Draw a picture of an open-open tube resonating at its fundamental frequency. Label the length of the pipe $L_1$

2. For an open-open tube, draw the next two standing waves that would form in a **longer** tube, assuming that the frequency is kept constant. Label the lengths of the tubes $L_2$ and $L_3$. Try to draw you diagram to scale ($L_2$ and $L_3$ should be appropriately proportional to $L_1$).

3. How many segments are in each tube?

4. What are the lengths, $L_2$ and $L_3$, of the tube in terms of the wavelength $\lambda$ for each of the two new pipes?

5. Based on the fundamental, and the next two standing waves, what is length, $L_n$, of a tube with $n$ segments inside of it.
:::

::::::



# The Experiment

## Explanation

For this lab you will build a cardboard tube whose length you can change. You will then use phyphox to generate a constant-frequency tone, and place your phone&rsquo;s speaker at the end of the tube. You will then adjust the length of the tube until a standing wave forms in the tube and it resonates. When this happens, you will hear a significant increase in the volume of the sound.

:::Figure
![Amplitude Plot](../imgs/lab4/AmplitudePlot.png)
:::

Figure 4 shows is a sketch of sound intensity as a function of tube length for the fundamental in an open-open pipe. This is an **example** plot of an adjustable, around 1 meter, pipe, with a frequency of 171.5 Hz playing.  Notice there is a background volume of the speaker playing, but as the length of the pipe nears the length of 1 m the volume increases dramatically.

The simulation below will allow you to experiment with this.
 
:::Simulation
<iframe src="https://kapawlak.github.io/PhDemoJS/Apps/TubeResonance/index.html" width="100%" height="800"></iframe>
:::

## Determining Frequency

::::::Exercise

You will be able to change the tube&rsquo;s length gradually from $L$ to $2L$. Thus you are able to adjust the length of the pipe by $L$. Over that length you will want to measure five standing waves (have your tube resonate five times). This is equivalent to saying that we want five segments over the change of length of the pipe.

Thus you need to choose a frequency that will allow this. Let&rsquo;s make that calculation now.

:::Note
If you have exactly $n$ segments in the first half of your pipe you will have $n$ segments over the second half.
:::

1. The note above will make the calculations much more simple. It means that if we can determine the frequency that will fit five segments in the first half of the tube, it will fit five segments in the second half.

:::Question fivelambda
If you have exactly 5 segments over the length $L$ of the pipe, what is the wavelength of the sound?
:::

:::Question
Using the speed of a wave and your response to [Qu](#Qu-fivelambda) write an equation for the frequency of the sound.
:::

:::Question
Assuming you are using a paper towel roll of standard length, $28$ cm, and the speed of sound you calculated in [Qu](#Qu-speedTemp), what is the frequency you need to get five segments in the second half of the tube?
:::

::::::



# Building the Apparatus

::::::::::::Exercise
In this exercise you will build the resonant cavity that you will use in next week&rsquo;s lab. Basically, we want to construct one tube that fits perfectly inside of another one. That way we can slide the inner tube out of the outer tube to make a longer tube.

1. Start by collecting all of the materials listed at the top of the lab.

::: Figure
![Image of Materials](../imgs/lab4/Materials.jpg)
:::

::: Note
If you don&rsquo;t have paper towel rolls, you can tape multiple toilet paper rolls together or use a different type of cardboard tube. You can use one from a roll of aluminum foil or saran wrap. You just need two that are the same diameter, or one that fits perfectly inside the other already. If you already have a tube that fits perfectly inside of another one, you are done with the apparatus. (Rolled up printer paper, card stock or cardboard should also work.)
:::

2. Take your empty cardboard tube, and cut it down its length.

:::::::::Figure
::::::row
:::col
![Cutting the Tube](../imgs/lab4/CuttingTube.jpg)
Cut the tube down its length.
:::

:::col
![Cutting the Tube](../imgs/lab4/CutTube.jpg)
This is what it should look like after being cut.
:::
::::::
:::::::::

3. Take the cut tube and fold one part of the seem under the other as shown in the figure below.

:::Figure
![Rolled Over Tube](../imgs/lab4//RolledOverTube.jpg)
:::

4. Slide the cut tube into your second tube. Leave just about a tape&rsquo;s width sticking out of the outer tube.
5. Then wrap the piece that is sticking out in tape. Don&rsquo;t wrap it multiple times, and don&dsquo;t wrap it so tightly that it reduces the size of the tube too much. You want it to fit snugly inside the other tube, but to slide fairly easily.

:::::::::Figure
::::::row
:::col
![Tube Inside Other Tube](../imgs/lab4/TubeStickingOut.jpg)
Make sure to leave a little piece sticking out.
:::

:::col
![Tape Wrapped End](../imgs/lab4/SealedEnd.jpg)
Don't wrap the tape too tightly.
:::
::::::
:::::::::

6. Now push the other end out and do the same thing. Then slide the inner tube out.
7. Tape over a couple more parts on the tube to make sure it stays cylindrical.

:::::::::Figure
::::::row
:::col
![Roll pulled out](../imgs/lab4/SealedTube1.jpg)
This is what it should look like after Step 6.
:::

:::col
![Finished Inner Roll](../imgs/lab4/SealedTube2.jpg)
This is the completed inner tube.
:::
::::::
:::::::::

8. Now slide the inner tube into the outer tube. You are done!

:::Figure
![Completed Apparatus](../imgs/lab4/CompletedTube.jpg)
Finished tube.
:::

::: Question
Take a picture of your apparatus and include it in lab report.
:::

::::::::::::

# Conclusion

::: Exercise
Write a short conclusion highlighting the important parts of resonance and the speed of sound, and how they apply to the measurement you will be making. 
:::