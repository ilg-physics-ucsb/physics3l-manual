# Lab 3: Simple Harmonic Motion Week 1
---

# Intro

## Required Materials
:::Materials

- An extension spring
- One or two zip-lock bags
- Paper clip
- Household baking goods and measuring cups, coins, batteries, or other objects of known mass.
- Tape
- Fork
- Large textbook (or a stack of books)
- Countertop
- Phyphox &ldquo;Acceleration (without g)&rdquo; preferred, or &ldquo;Acceleration (with g).&rdquo;
:::

## Lab Goals

- **Construct an apparatus**
  - Gather all the components and build your apparatus.
- **Data Analysis**
  - Understand the theory behind Hooke's Law.
  - Write the equations that will be used to process the data.
  - Prepare a spreadsheet for data analysis.

---

# Hooke&rsquo;s Law

## Theory
Most springs obey Hooke's Law: the magnitude of the force  that the spring exerts is proportional to the amount it is stretched. This is mathematically expressed as: 

:::Equation hookeslaw
$$
F_{sp} = -k\Delta y
$$
:::

Where $F_{sp}$ is the force exerted by the spring, $\Delta y$ is the displacement from the spring&rsquo;s unstretched position, and $k$ is the spring constant. The larger the spring constant $k$, the &ldquo;stiffer&rdquo; the spring.  As a matter of fact, the constant $k$ is often referred to as the stiffness.

For the purpose of this lab, we will define the origin, the zero point, as spot at the end of the spring when it is hanging in its relaxed state. (See [Fi](#Fi-hookeslawimg) below.)

:::Figure hookeslawimg
![Hooke's Law Image](../imgs/lab3/HookesLaw.png)
:::

Hooke&rsquo;s law is an excellent description for the behavior of springs, but it often applies to other things besides springs. It is also sometimes accurate for elastic materials such as rubber bands.

If we were to hang a mass, $m$, from a spring, and wait for the system to come to equilibrium (stop moving), we could determine the spring force by using Newton&rsquo;s second law and the force of gravity. 

:::Figure freebody
![Free Body Diagram of spring mass system](../imgs/lab3/FreeBodyDiagram.png)
:::

We will define the downward direction as positive. See [Fi](#Fi-freebody) for a free body diagram. Putting this together we have:

:::Equation freebody-eq
$$
\begin{aligned}
\sum F = F_{sp}+F_g &= F_{sp}+mg =0 \\\\
\implies F_{sp}&=-mg
\end{aligned}
$$
:::

where in the first line of the equation we recognized that for a system in equilibrium, the acceleration is zero.

Thus we can use the mass and gravity to measure the spring force. From this we can measure the spring constant of the rubber band.

:::Question freebody-qu
Use [Eq](#Eq-hookeslaw) and [Eq](#Eq-freebody-eq) to solve for the spring constant.
:::

## The First Experiment

:::Figure measurement
![Sugar in bag hanging on spring](../imgs/lab3/Measurement.png)
:::

A better way to determine the spring constant would be to vary the mass and measure the stretch for each mass. From many data points we could create a plot and perform a fit.

For this lab you will hang a zip-lock bag on a spring, and add mass to the bag. You will measure the length of the spring as you add more and more mass.

:::Question
1. Rewrite your answer to [Qu](#Qu-freebody-qu) to have stretch, $\Delta y$, as a function of mass $m$.

2. If you were to create a plot of stretch vs. mass, what would be the expression for the slope?

3. How would the slope change with stiffness of the spring?
:::

# Springs in Motion (More Harmonic Motion)

Another way to determine the spring constant is to hang a single mass from the spring. If you were to displace the mass from its equilibrium position slightly and release it, you would see the mass oscillate around the equilibrium position. This should sound **very** familiar.

In fact, this is another form of a simple harmonic oscillator. 

In order to show this mathematically, we must first determine the net force on the mass when it is slightly displaced. 

:::Figure smalldisplacement
![Image of Mass in Three positions](../imgs/lab3/SHMDerivation.png)
:::

[Fi](#Fi-smalldisplacement) shows the spring in three different positions, labeled 1, 2 and 3. Position 1 shows the unstretched spring. Position 2 is the mass hanging from the spring in its equilibrium position, which is what we will call the zero position. Position 3 shows the mass when it has been displaced by an amount $y$ from equilibrium. 

We already know that in position 2 the spring force is given by:

:::Equation hookeslaw2-eq
$$
F_{sp2} = -k\Delta y = - mg 
$$
:::

Then, if you look at the net force on the mass in position three you see that:

:::Equation displacedSpring
$$
\begin{aligned}
\sum F &= -k(y+\Delta y)+mg \\\\
\sum F &= -ky
\end{aligned}
$$
:::

where when we distribute the first part of [Eq](#Eq-displacedSpring) and use [Eq](#Eq-hookeslaw2-eq) we find that the two forces cancel out.

:::Question acceleration
Use Newton&rsquo;s second law and [Eq](#Eq-displacedSpring) to determine the acceleration felt by the mass, $a_y$. 
:::

:::Question
Is the oscillating mass a simple harmonic oscillator? Use your response to [Qu](#Qu-acceleration) to help justify your answer. **Hint:** Look back at Lab 2 Week 1 if you need help.
:::

:::Question
1. What is the expression for the angular frequency, $\Omega$, of this simple harmonic oscillator?

2. What is the period of oscillation?
:::

::: Question
1. For a given mass, does a stiffer spring cause the oscillations to have greater or lesser frequency? Period?

2. Why do you think that increasing the mass increases the period? **Hint:** Think about this in terms of $F=ma$.
:::


## The Second Experiment

:::Figure shmApparatus
![GIF of moving phone](../imgs/lab3/SHM.gif)
:::

The second experiment for next week will involve your putting your phone in the zip-lock bag and then setting it in motion. You will use the &ldquo;Acceleration without g&rdquo; to measure the acceleration experienced by your phone. You will then use the acceleration to measure the period, and the spring constant of your spring.

As we do for a pendulum, we typically talk about the period of the position and not the acceleration. You will be measuring acceleration. Since we know that the mass on a spring is also a simple harmonic oscillator, we know that the position as a function of time looks like the following:


:::Equation
$$
y = A\sin(\Omega t)
$$
:::

where $A$ is the amplitude or the initial displacement, and $\Omega$ is the angular frequency.

:::Question
Does the acceleration experienced by the mass have the same period as the position? Justify your answer. **Hint:** Think back to the pendulum lab.
:::

# Apparatus

In this lab you will be hanging your spring from a fork that is held down to a horizontal surface for two exercises. The first exercise will require you to attach a variety of masses to your spring, and the second will require you to attach your phone to your spring. [Fi](#Fi-measurement) and [Fi](#Fi-shmApparatus) show the two setups. Note that the setup for both exercises will be similar. @fa-tools@

## @fa-cog@ Construction

::::::Exercise 
In this experiment you will be using some masses and your phone to measure characteristics of simple harmonic motion. You will build an apparatus and take data for analysis.

The process of building your experiment will be similar to the procedure you used to make apparatus for your previous lab, &Ldquo;Pendulum.&rdquo; There is a variety of ways in which you could build this apparatus. Please read through all of the instructions before considering alternate steps.

1. Collect all of the materials you will need for this setup: spring, tape, paper clips, zip-lock bags, textbook(s), makeshift weights (sugar, flour, salt, cornstarch, coins). 

2. Find the location where you will build your apparatus. We recommend the edge of a counter, table, or chair.

:::Figure 
![Empty Assembly](../imgs/lab3/Desk2.png)
:::

In this lab you will have your phone oscillating on a spring, so you will want to make sure your phone is not suspended too high, and that you can place a cushion underneath it.



3. Place a fork on your surface so that the prongs are hanging off the edge of the table.

4. If you have tape available tape the fork to the surface.

5. Get a heavy textbook (or similar weighted object) and place it on top of the fork. You should now be safe to hang some stuff from the edge of the fork.
::: Figure fork s
![Fork On Table](../imgs/lab3/Fork.png)
![Fork On Table](../imgs/lab3/ForkTape.png)
![Fork On Table](../imgs/lab3/ForkTapeBook.png)
:::
:::Warning
Don't use Scotch tape on wooden or painted surfaces. It might ruin the surface when you remove the tape.
:::

::: RFigure ziploc xs
![Ziploc Pierce](../imgs/lab3/Bag1.png)
![Ziploc Pierce](../imgs/lab3/Bag2.png)
Click to enlarge
:::

6. Now take your zip-lock bag and attach your paper clip to it. It is best if you can secure the bag by using only one side, so that you can have easier access to the inside of the bag.

7. If possible make it so that an open side of the paperclip is facing down. This will make it easier to hook onto the spring.

8. Now slide your spring over 1 or 2 of the prongs of the fork.

9. Then attach the paperclip and bag to the fork.


---
Once you have your setup, it should look something like this:

:::Figure:Figure
![Empty Assembly](../imgs/lab3/Apparatus.png)
:::

You may consider alternate mounting methods if you have a solution that is better for your space.

:::Warning
It is **strongly** recommended you put a pillow or cushion under your apparatus when you hang your phone from the spring.
:::

::: Question
Include a picture of your apparatus in your lab report.
:::

::::::


## @fa-table@ Making your Spreadsheets

With your apparatus built, you will want to prepare the masses and your data tables.
You will be collecting data in two experiments &mdash; one with only masses, and one with your phone and other masses.

::::::Exercise
Making your data tables now will help organization and reduce workload for next week. 

Make a table in the google sheet provided. Follow the example shown below for the first experiment.

:::Table
| Length (m) | $\Delta$y (m) | Mass (kg) | Mass Description | Force (N)| k (N/m)| 
| -------- | -------- | -------- | -------- | -------- | -------- |
| @fa-pencil@     |        |      |      |    |      |
| @fa-pencil@ |        |      |      |    |      |
:::

Make another table in Google Sheets as shown below for the second experiment.

:::Table

| Mass (kg) | $\Delta t$  (s) | # of periods | T  (s) | k (N/m)| 
| -------- | -------- | -------- | -------- | -------- |
|@fa-pencil@    |      |      |      |      |      |      |
:::


::::::

## @fa-balance-scale@ Figuring out your Masses

::::::Exercise

Now we need to figure out what masses you can use with your apparatus.

For this you can use any household item that you can weigh, but we have several recommendations: coins, batteries, water, flour, sugar and salt.

The mass range you will want to use is anywhere from about 20 g to 500 g, depending on how stiff your spring is.

::: Warning
Adding too much mass to your spring can permanently deform it!
:::

:::Note
Mixing and matching materials for your masses is certainly fine. Please note, however, that certain items should not be combined, such as water and batteries. Below are tables for how much each of your recommended materials weighs.
:::



### US Coins
:::Table
| Dollar | Half Dollar | Quarter | Dime | Nickel | Penny |
| :--------: | :--------: | :--------: | :--------: | :--------: | :--------: |
| 8.1g | 11.3g | 5.7g | 2.3g | 5.0g | 2.5g |
:::

### Batteries
:::Table
| | AA | AAA | 9-V | D | C |
| -------- | :--------: | :--------: | :--------: | :--------: | :--------: | 
| Alkaline | 23g | 11.5g |45g | 135g | 65g | 
| Lithium | 15g | 7.6g | 37g| -|- | 
|Rechargable Ni-MH | 31g | 14g |-  | 160g | 80g |
:::

### Household goods
:::Table
|  | Metric equivalent (ml) | Water | All Purpose Flour | Granulated White Sugar | Table Salt |
| -------- | :--------: | :--------: | :--------: | :--------: | :--------: |
| Density (g/ml) |   | 1g/ml |  0.6g/ml |  0.92g/ml    |  1.26g/ml  | 
| 1 cup     |  237ml    |   237g   |  130g   | 200g | 273g | 
| 1 teaspoon     |  4.9ml    |   4.9g   |   3.3g  | 4g | 5.7g |
| 1 tablespoon     |  14.8ml    |   14.8g   |   8.5g  | 12.6g | 17g |
:::

1. Find your available materials and think about how you can distribute your masses to have 10 - 15 different mass values between 20 g and 500 g. Measure out your available materials, and make a plan for how to achieve each mass value you want to test. Mass values of roughly 20 g, 50 g, 100 g, 150 g, 200 g, 250 g, 300 g, 350 g, 400 g, 450 g, 500 g would be great.

2. Write out your chosen masses and what proportions of which materials you use for them in the table you made for experiment 1.

Because your zip-lock bag is mounted via a paper clip, you can easily replace your bag when you move on to experiment 2. This will be useful if you are using messy masses such as flour or water.

:::Warning
If you are using messy household goods, you can use two bags. Put your masses into a separate bag, then place that bag with your phone in the main bag as shown in [Fi](#Fi-masswithphone). 
:::

:::Figure masswithphone
![Final Apparatus](../imgs/lab3/MassWithPhone.png)
:::

::::::

## Conclusion

::: Exercise
1. Give a short summary of Hooke&rsquo;s Law. 
2. Give a quick summary of the important parts of this lab.
:::
