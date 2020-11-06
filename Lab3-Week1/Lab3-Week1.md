# Lab 3: Simple Harmonic Motion Week 1
---
### All Materials Needed:
- Two kinds of rubber bands
- Ziplock bag
- Household baking goods and measuring cups, coins, or other objects of known masses.
- Scissors
- Tape
- Measuring tape or meter stick
- Pillow, couch cushion, or something similar.
- Somewhere to hang your spring, e.g., shower curtain rod, broomstick across two chairs, large table, etc. 
- Phyphox "Acceleration (without g)"

### Optional Materials

-Zip ties

-Super glue

### Lab Goals:
- ** Construct an apparatus **
	- Find two rubber bands of different widths.
	- Find a surface and location to hang your masses from; such as a table, shower rod, broom, etc.
- ** Data Analysis **
	- Understand the theory behind Hooke's Law.
	- Generate the equations that will be used to process the data.
	- Prepare spreadsheet for data analysis.

---

# Part I: Hooke's Law

Simple Harmonic Motion (introduction)?

#####

Most springs obey Hooke's Law: the magnitude of the force the spring exerts is proportional to the amount it is stretched. This is mathematically expressed as: 

:::Figure:Equation
$$
F = -k \Delta y
$$
:::

The ratio of the force ($F$) to the amount stretched from equilibrium ($\Delta y$) is the spring constant $k$; $k = \frac{F}{\Delta y}$. This principle applies to more than just springs, it also works when dealing with elastics such as rubber bands. 

Add Figure AVO


#####

One way to determine k for an elastic is to hang a mass $m$ from it. The force that mass is exerting on the rubber band is then mg, where g is the acceleration due to gravity - assume $g = 9.80 \frac{m}{s^2}$. We can then see how far the rubber band stretches.

#####

More quantitatively: 

:::Figure:Equation
$$
|F| = k |d|, \\|F| = mg, \\|d| = \frac{g}{k}m
$$
:::

If the graph of |$d$| vs $m$ (with m as the independent variable) approximates a straight line, then this is evidence that the rubber band obey's Hooke's Law. Furthermore, the slope of the line, $s$, will be $\frac{g}{k}$. You could determine $k$ if you found $s$: $k = \frac{g}{s}$.

:::Question
(a) Some conceptual question?

(b) Maybe another conceptual question?
:::


## Springs in Motion

The larger the spring constant $k$, the "stiffer" the spring or rubber band - as a matter of fact, the constant $k$ is often refered to as the stiffness of the band AVO. The angular frequency $w$ of a mass $m$ bouncing on a spring AVo is determined by $k$ and $m$: 

:::Figure:Equation
$$
w= \sqrt{\frac{k}{m}}
$$
:::

$w$ is in $\frac{radians}{s}$. Frequency $f$, in $\frac{vibrations}{s}$, is equal to $\frac{w}{2\pi}$. Period T, in $\frac{s}{vibrations}$, is equal to $\frac{1}{f}$. Thus: 

:::Figure:Equation
$$
T=\frac{2\pi}{w}
$$
:::

This applies to any simple harmonic motion. For all simple harmonic motion the restoring force is linear. For the case of a mass on a rubber band, substitution yields: 

:::Figure:Equation
$$
T = 2\pi \sqrt{\frac{m}{k}}
$$
:::

::: Question
a) For a given mass, a stiffer spring causes greater of lesser frequency? Period?

b) Why do you think that mass increases the period? Hint: Thing about this in terms of $F=ma$
:::

For a particular spring, $k$ is approximately constant within a given regime. Thus $T$ is equal to a constant times $\sqrt{m}$, or equivalently, $T^2$ is proportional to $m$. If you graph $T^2$ versus $m$ for a number of different masses, you should get a straight line with slope of $\frac{(2\pi)^2}{k}$:

:::Figure:Equation
$$
T^2=[\frac{(2\pi)^2}{k}]m
$$
:::

The most precise way to measure the period is to measure, say, 10 periods, and then divide by 10. That way any imprecision in your measuring process is spread out over a much greater time, and will have a much smaller overall effect. If $n$ is the number of periods you time, and $t_n$ is the time for all those periods, then:

:::Figure:Equation
$$
T=\frac{t_n}{n}
$$
:::

## Building Your Lab

In this lab you will be mounting a rubber band to a horizontal surface for two exercises. The first exercise will require you to attach a variety of masses to your rubber band, and the second will require you to attach your phone to your rubber band. Figure Guac shows a possible set up, the set up for both exercises will be similar.

:::Figure:Image
Image.jpeg
:::

:::Exercise 
In this experiment you will be using some masses and your phone to measure characteristics of simple harmonic motion. You will build an apparatus and take data for analysis. Be sure to include a picture of your set up if you can!


The process of building your spring AVO experiment will be similar to the apparatus you made in your previous lab: Pendulum. You can also build this with many different variations. Please read through all of the instructions before considering alternate steps.

1. Collect all of the materials you will need for this set up: rubber bands, tape, scissors, zip-lock bags, makeshift weights (sugar, flour, salt, cornstarch, coins).

2. Find the location where you will build your apparatus. You should be fine with building this wherever you build your pendulum from the previous lab.

In this lab you will have your phone oscillating on a rubber band, so you will want to make sure your phone is not suspended too high, and that you can place a cushion underneath it.

3. Cut your rubber band so you have one long piece instead of a ring.
4. Secure the top of your rubber band to your mounting point using tape and/or zip-ties. 
5. Secure the bottom of your rubber band to your zip-lock bag. That can be done by punching a hole into the bag, running the rubber band through and tying it. You can also zip-tie the band on the bag. 

Once you have your set up it should look something like this: IMAGE AVO

6. Now repeat steps 1-5 for your second rubber band. AVO do we want them to do 2?

Note: You will want to place a cushion under your apparatus in case the rubber band breaks or you masses or phone slip.

:::


## Making your Spreadsheets

With your apparatus built we will want to prepare the masses and your data tables.
You will be collecting data in two experiments, one with only masses, and one with your phone and other masses.

At this point your apparatus should look like this:
Image.jpeg AVO

:::Exercise
Making your data tables now will help organization and reduce workload for next week. 

Make a table in Google sheets as seen below for the first experiment.

| Length | Delta y | Mass | Mass Description | Force | k | 
| -------- | -------- | -------- | -------- | -------- | -------- |
|      |      |      |

Make another table in Google Sheets as seen below for the second experiment.


| Mass | $time_i$ | $time_f$ | Delta $t$ | number of periods | T | k | 
| -------- | -------- | -------- | -------- | -------- | -------- | -------- |
|      |      |      |

:::

## Figuring out your Masses

:::Exercise

Now we want to figure out what masses you can use with your apparatus.

You can use any household item you can weigh for this, however, we have several recommendations: Coins, Batteries, Water, Flour, Sugar, and Salt.

The mass range you will want to be looking at is anywhere from about 20g to 1000g depending on how thick your rubber bands are. Most small rubber bands should only get about 350g, while thicker ones can hold over 1000g.

Mixing and matching materials for your masses is certainly fine. Please note however, that certain items should not be combined, such as water and batteries. Below are tables for how much each of your recommended materials weigh.

US Coins:

| Dollar | Half Dollar | Quarter | Dime | Nickle | Penny |
| -------- | -------- | -------- | -------- | -------- | -------- |
| 8.1g | 11.3g | 5.7g | 2.3g | 5.0g | 2.5g |

Batteries:

| | AA | AAA | 9V | D | C |
| -------- | -------- | -------- | -------- | -------- | -------- | 
| Alkaline | 23g | 11.5g | | 135g | 65g | 
| Lithium | 15g | 7.6g | | | | | 
|Rechargable Ni-MH | 31g | 14g |  | 105-160g | 80g |
|Energizer Alkaline|  |  |  |  |
|Energizer Lithium|  |  |  |  |
|Duracell Alkaline|  |  |  |  |
|Duracell Lithium|  |  |  |  |
|Amazon Basic|  |  |  |  |


Household goods: 

| Amount | Amount Metric | Water | Flour (All Purpose) | Flour Sugar | Salt | Water |
| -------- | -------- | -------- | -------- | -------- | -------- |
| Density |  - | 
| 1 cup     |  120ml    |      |     |  | 
| $\frac{1}{2}$ cup     |      |   75g   |     |
| $\frac{1}{3}$ cup     |      |      |     |
| $\frac{1}{4}$ cup     |      |      |     |
| 1 teaspoon     |      |      |     |
| 1 tablespoon     |      |      |     |

Using a second zip-lock bag would be great. This way you do not have to get the bag attached to your rubber band dirty. Note that your phone will go in that bag later. So ideally you will fit your mass bag into your first bag AVO WORDING.

1. Find your available materials and roughly thing about how you can distribute your masses to have 10 - 15 different mass values between 20g and 500g. Measure out your available materials and make a mass plan for each mass value you want to test. Mass values of roughly 20g, 50g, 100g, 150g, 200g, 250g, 300g, 350g, 400g, 450g, 500g would be great.
2. Write out your chosen masses and what breakdown of what materials are used for them in the table you made for experiment 1.

Note that 20g is a good starting point so that your rubber band starts out taught. 
:::

## Conclusion

::: Exercise
1. Give a short summary of Hooke's Law. 
3. Give a quick summary of the import parts of this lab.
:::
