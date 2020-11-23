# Lab 4: Speed of Sound - Week 1
---
### All Materials Needed:
- One tube from a paper towel roll, ~28 cm long. 
- A second, same-sized, paper towel tube, (may or may not have paper towels attached)
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
	- Understand the theory behind resonance
	- Determine resonance length
	- Determine frequency to be used for experiment
---

# Part I: Sound, Waves, & Resonance

### Sound

Sound is caused by a disturbance in the surrounding medium — air. Air is an elastic medium, meaning that it returns to its original shape once forces stop acting on it. Consider a single audio speaker. When music is playing the speaker vibrates, alternately compressing and expanding the volume in front of it, thus periodically pushing the air molecules in front of it.

:::Figure:Figure
![Speaker](imgs/Speaker.gif)
:::

When the speaker moves outward, it pushes out surrounding air molecules, and that push causes a chain of disturbances that propagate through the air. When the speaker moves inward, it creates more space for air particles to move, starting with the air molecules closest to the speaker. This is known as positive and negative displacement.

:::Figure:Figure
![SpeakerOut](imgs/SoundPulse.gif)
:::

Figure 2 shows column of air set in motion by a speaker at the left vibrating at some frequency. You can see compression waves traveling to the right. Notice, though, that any one particle (some have been highlighted in red) doesn&rsquo;t actually move to the right but just oscillates back and forth.

### Speed of Sound

The speed of sound results from the inertia and elastic properties of the material it travels through. The greater the mass of individual particles of the medium, the less responsive they are to the interactions between neighboring particles, and the slower the wave. All other things being equal, a sound wave travels faster in a less dense material than in a more dense material. For instance, a sound wave travels nearly three times faster in Helium as it does in air. A sound wave travels faster in a medium with greater restoring force than in one that provides a lesser restoring force. Sound (technically acoustic) waves travel extremely fast in metals, which have stiff crystal structures to restore individual particles to their original positions.

Sound waves propagate at velocity $v_s$. The speed of propagation is determined by the medium through which the wave propagates.

The speed of sound in air can be expressed by the following equation:

:::Figure:Equation
$$
v_s = 331+ 0.6  T
$$
:::

where T is the temperature of the air in degrees Celsius.

:::Question
What are the units of the 0.6 constant in Equation 1?
:::

:::Question
If it is $20^\circ$C in your room what is the speed of sound?
:::


### Speed of Waves

The speed of waves is a slightly tricky concept. It does not refer to how fast any one given particle is moving. Rather, it refers to how fast the wave &ndash; the disturbance &ndash; propagates through the medium. If you were to pick a point on the wave, say one of the positive displacements, and watch it move, the speed of its progress would be the speed of sound. It is the measure of how fast the disturbance moves through a medium. 

The speed of the wave is determined by the frequency, $f$, and the wavelength, $\lambda$. The equation is:

::::Figure:Equation
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


### Resonance


The word resonance comes from Latin words for ‘echo’ and ‘resound’. Resonance is illustrated by a swing on a playground; if you push a friend on the swing and wait for it to return to you, the swing will fall into a rhythm, a natural interval. As long as you push the swing in time with its natural frequency, the swing can go quite high. The natural frequency is the frequency at which it would oscillate if there were no resistive forces present. If,  however, you attempt to push the swing at a frequency that is different from this natural frequency, the maximum height of the swing will be much lower  (and you might hurt yourself).

As you might guess from the swing analogy, resonance occurs when you drive a system at its natural frequency of oscillation.  In the case of the paper towel tube apparatus that you are about to make, this means setting the conditions so that you form a **standing wave** inside the tube. That is, a wave that forms a pattern of nodes and antinodes that is fixed in space.  This happens when the wave reflected from the end of the tube comes back in phase with the outgoing wave. You can produce a standing wave, and therefore make something resonate, when you meet the proper boundary conditions. For a standing wave to form, there needs to be an antinode at any open end of a pipe, and a node any closed end.

To get resonance conditions we can do this in two ways. 

1. We can adjust the driving frequency. Since the speed of sound is constant at a particular temperature, adjusting the frequency changes the wavelength. When the wavelength is such that it meets the boundary conditions, the tube will resonate.
2. We can adjust the tube length while keeping the frequency constant. At some length(s), the wave inside the tube will match the boundary conditions, and the tube will resonate.

The lowest resonant frequency is called the **fundamental frequency**, or the 1$\rm^{st}$ harmonic. A harmonic is a positive integer multiple of the fundamental frequency.  By increasing the frequency, and thus shortening the wavelength, we can find higher harmonics for which the tube resonates.

Air columns in cylinders for which both ends are open can produce all harmonics of the fundamental frequency. They allow all harmonics that have an antinode at each end of the cylinder.  These are all half-wavelength harmonics. Cylinders with one closed end and one open end produce only those harmonics that have a node at the closed end and an antinode at the open end. These are all odd quarter-wavelength harmonics.


:::Exercise
:::Figure:Figure
![Resonant Conditions](imgs/ResonanceTubes.png)
:::

As noted above, the boundary conditions for a standing wave require that there is a node at any closed end and an antinode at any open end. In Figure 3, the top tube is open on both ends (open-open), and the bottom tube is open at one end and closed at the other. Drawn in each is the first standing wave that can form in either tube. 

:::Question
What is the wavelength for the fundamental frequency of an open-open tube in terms of the tube length $L$?
:::

:::Question
a) For an open-open tube, draw the next two harmonics that would form for a tube of the same length $L$.

b) What is the wavelength for each of those two harmonics in terms of the tube length $L$?

c) Based on the fundamental, and the next two harmonics, what is the wavelength for the $n\rm^{th}$ harmonic?
:::

For a tube with both ends open, we will say that there is one segment inside the tube resonating at the fundamental.

:::Question
a) For an open-open tube, draw the next two standing waves that would form in a longer tube, assuming that the frequency is kept constant.

b) How many segments are in each tube?

c) What is the length, $L$, of the tube in terms of the wavelength $\lambda$ for each of the two new pipes?

d) Based on the fundamental, and the next two standing waves, what is length of a tube with $n$ segments inside of it.
:::

:::



## The Experiment

For this lab you will build a cardboard tube whose length you can change. You will then use phyphox to generate a constant-frequency tone, and place your phone&rsquo;s speaker at the end of the tube. You will then adjust the length of the tube until a standing wave forms in the tube and it resonates. When this happens, you will hear a significant increase in the volume of the sound.

:::Figure:Figure
![Amplitude Plot](imgs/AmplitudePlot.png)
:::

Figure 4 shows is a sketch of volume as a function of tube length for the fundamental in an open-open pipe. Notice there is a background volume of the speaker playing, but as the length of the pipe nears the length of 1 m the volume increases dramatically.

The simulation below will allow you to experiment with this.
 
:::Figure:Simulation
<embed type="text/html"src="https://kapawlak.github.io/PhDemoJS/Apps/TubeResonance/index.html" width="100%" height="800">
:::

:::Exercise

You will be able to change the tube&rsquo;s length gradually from $L$ to $2L$. Thus you are able to adjust the length of the pipe by $L$. Over that length you will want to measure five standing waves (have your tube resonate five times).

Thus you need to choose a frequency that will allow this. Let&rsquo;s make that calculation now.

1. Determine the separation between any two standing waves.

:::Question
Assume you have a pipe of length $L$, and that with a set frequency $f$, this corresponds to the $n\rm^{th}$ standing wave. You increase the length of your pipe by $\Delta L$ to the $(n+1)\rm^{th}$ standing wave without changing the frequency.

What is $\Delta L$ in terms of wavelength?
:::

2. You now know the separation between two standing waves. We will increase our pipe length by $L$, with five standing waves forming over that change.

:::Question
What is the separation between five standing waves (*i.e.*, if you call the one at which you are starting the first one, from that one up to the fifth one)?
:::

:::Question
If you increase the length of the pipe by $L$, and five standing waves occur over that change in length, what is the length, $L$, in terms of wavelength, $\lambda$?
:::

2. In order to get five standing waves over the length increase you will need to select the correct frequency. 

:::Question
Assuming the speed of sound is what you calculated in Question 2, that you can change your pipe over a length $L$, and that you want to get five standing waves over that change, what frequency should you use?
:::

:::Question
Assuming you are using a paper towel roll of standard length, $28$ cm, what is the frequency you need to get five standing waves?
:::

:::



# Part II: Building the Apparatus

::: Exercise
In this exercise you will build the resonant cavity that you will use in next week&rsquo;s lab. Basically, we want to construct one tube that fits perfectly inside of another one. That way we can slide the inner tube out of the outer tube to make a longer tube.

1. Start by collecting all of the materials listed at the top of the lab.

::: Figure:Figure
![Image of Materials](imgs/Materials.jpg)
:::

::: Note
If you don&rsquo;t have paper towel rolls, you can tape multiple toilet paper rolls together or use a different type of cardboard tube. You can use one from a roll of aluminum foil or saran wrap. You just need two that are the same diameter, or one that fits perfectly inside the other already. If you already have a tube that fits perfectly inside of another one, you are done with the apparatus. (Rolled up printer paper, card stock or cardboard should also work.)
:::

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

3. Take the cut tube and fold one part of the seem under the other as shown in the figure below.

:::Figure:Figure
![Rolled Over Tube](imgs/RolledOverTube.jpg)
:::

4. Slide the cut tube into your second tube. Leave just about a tape&rsquo;s width sticking out of the outer tube.
5. Then wrap the piece that is sticking out in tape. Don&rsquo;t wrap it multiple times, and don&dsquo;t wrap it so tightly that it reduces the size of the tube too much. You want it to fit snugly inside the other tube, but to slide fairly easily.

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

6. Now push the other end out and do the same thing. Then slide the inner tube out.
7. Tape over a couple more parts on the tube to make sure it stays cylindrical.

:::Figure:Figure
:::row
:::column
![Roll pulled out](imgs/SealedTube1.jpg)
This is what it should look like after Step 6.
:::

:::column
![Finished Inner Roll](imgs/SealedTube2.jpg)
This is the completed inner tube.
:::
:::
:::

8. Now slide the inner tube into the outer tube. You are done!

:::Figure:Figure
![Completed Apparatus](imgs/CompletedTube.jpg)
Finished tube.
:::

:::
