
# Week 1 -  Getting started with PHYPHOX; Grappling with uncertainty in measurement
---

:::Note
There are four videos in this document. Sometimes the Safari browser has issues playing them. Try switching to Chrome or Firefox. Additionally, sometimes if you click the pop-out button it will play for you even though it wouldn't play within the webpage.
:::

---
## INTRODUCTION

Welcome to the first-ever offering of **PHYS 3L for physics majors** on-line!  This week you will practice using the Phyphox app and performing some basic data analysis.    Phyphox is an app that turns your phone into a scientific sensor.  It is available for Android and iOS through Google Play and the App Store.  Through the app, you can make many advanced measurements and save your data in a .csv file for a more rigorous analysis. 

This week, and every week, your work will be evaluated based on the notes you take *while you are working*.  Note that it is less important that you "get the right answer" than it is that you "show your work".  If you haven't already, please read about Note-Taking under the Course Information the tab on GauchoSpace.  Make sure your notes explain the questions you come up with and the answers  you get **in your own words**.

---

## PART 1: PHYPHOX

Phyphox is an app that allows you to collect data from all of the different sensors in your phone. Almost all smart phones have accelerometers, cameras and microphones in them. Your smartphone may have other sensors available to Phyphox, such as a pressure gauge, temperature sensor, or light sensor. You should feel free to use whatever is available to you in your experiments.   

Here is an exercise to help you become familiar with Phyphox.  It is also an opportunity to practice describing your work in your notes.

### Determining the Axes of your accelerometer

:::Exercise
 Start by determining the three axes of the accelerometer in your phone. Begin by defining a coordinate system for your phone in your notes.  For example, you might include a figure like the following in your notes.
 
:::Figure:Figure
 ![](imgs/PhoneAxis.png)
:::

Do not copy and paste, or even refer to this figure in your notes.  Make your own, as if you were working without a lab guide.  It doesn't have to be a fancy photograph like this one.  A hand-drawn sketch or simple line diagram in which the phone is just a rectangle will do.

Next, use the "Accelerometer with g" sensor on your phone and determine how the coordinate system you defined corresponds to the one reported by Phyphox.  Here is a video to show you how you might do so. 
 
:::Figure:Video
!(https://www.youtube.com/watch?v=NrAygsCGgA4)
:::

Again, don't copy and paste, or even refer to this video in your notes.  Just describe what you do (even if it is exactly the same is what the video says).  

Finally, describe what you find.  Use words as well as a sketch or diagram to convey how the three phone axes map to the accelerometer's axes.
:::

### Measuring Acceleration Due to Gravity (g) with Phyphox

:::Exercise
 
Now measure *g* using the accelerometer in your phone as reported by the "Acceleration With g" function in Phyphox. Ccollect data in each direction along all three axes (*e.g.* with the phone both face up and face down). 

Here's another video with a suggestion for how you might perform the experiment. You may follow the video exactly, but you should feel free to make any improvements to the procedure.  Either way DO NOT refer to this video in your notes.  Just describe what you do in your own words.  
:::Figure:Video
!(https://www.youtube.com/watch?v=b2t__LSNqn8)
:::

Next, describe what you observe.   Supplement your description with a screenshot of the three plots, x, y, and z, that Phyphox produces.  If your findings raise any questions in your mind, note those as well.  Be detailed  in your descriptions, and let your thoughts flow freely in your notes.  No need to edit.

Finally, when you're done working and thinking, and you have a result take a moment to write it down concisely.  Put a box around it so that this "conclusion" is easy to find when looking back through your notes.
:::


## PART 2: ANALYZING DATA
Physics is the study of the laws of nature through observation and experiment.  Much of the observation involved in physics experiments is quantitative.  After designing measurements and collecting data, the physicist seeks to interpret the data by discerning mathematical relationships between variables.  As Eugene Wigner famously noted,  the language of mathematics is miraculously well suited for the formulation of the laws of physics.  This is truly miraculous because math is perfect, while measurement never is.  Understanding, and accurately reporting the limitations of measurements is essential to reliably test, improve upon or discover new mathemtical descriptions of nature.

## Uncertainty in measurement

When you measure a quantity, how can you know if you got the right value?   

First you have to accept that the right value, the "true value", is a mathematical construct. Suppose you want to measure the length of a pencil. If you are careful and thoughtful in your measurement, you will get a length close to the true length, your **best estimate**. The most honest way to report your measurement to others is to provide your best estimate and a window of values about that estimate in which the true length is likely to fall. This window is called your **uncertainty**. You would typically write down the length of the pencil in the following format:

$$
62.33 \pm 0.05 \text{ cm}
$$

Here, 62.33 cm is your best estimate, and the 0.05 cm is characterizes the extent of your uncertainty.  You think it more likely that the true value lies within the range than outside it.  How much more likely?  About two times more likely.  That is the convention among physicists.  In the medical sciences, or in precision engineering, where lives or large systems are on the line, the convention is different, closer to a factor of 10.  

:::Note
**UNCERTANTY IS UNAVOIDABLE IN EVERY MEASUREMENT.**
:::

## Sources of Error

Error in a measurement is any deviation from the true value that is being measured. Error does not mean that you made a mistake.

There are two main types of errors: **systematic** and **random**.

**Systematic errors** arise from improper use of the measurement equipment and  improper experimental techniques. Systematic uncertainties are consistent between measurements: if you repeat the experiment, you'll get the same error. 

For example, when you measure the length of the pencil, if the ruler you use is  of a material that has a large coefficient of thermal expansion and the temperature of the room is very different from the temperature at which the ruler was inscribed, the ruler might be "off".  It might actually be shorter than it should be, and your best estimate for the length of the pencil made using that ruler, will always be larger than its true value.

Another systematic error would be introduced if you didn't take care to keep your line of sight perpendicular to the ruler when measuring the pencil length.

Systematic errors can be completely eliminated with enough work, by calibrating and checking the equipment and using proper measurement techniques. 

**Random error**
 
If you repeat a measurement, and the value of the measured quantity differs from time to time, the values will be randomly distributed around a mean value.  The mean value is your best estimate of the true value.  The amount by which your individual measurements differ from the mean value is the "random error" in your measurement.

It is not possible to eliminate random errors, but you can minimize them by using precise instruments and by collecting a  large data, which reduces the uncertainty in your average measurements. 

***Random error is the fundamental source of uncertainty in any measurement. ***


The video below shows an example of random error you have already seen in this lab. 

::: Figure:Video
!(https://www.youtube.com/watch?v=EyucI5jm0Bs)
:::

:::Note
Systematic error should be eliminated as a source of error in measurement.

Random error, can be mininized, but is inherently unavoidable and defines the uncertainty in measurement.
:::

 Think about the errors present in your Phyphox measurement and write your thoughts in your notes.
 
:::Exercise
Now analyze the data from the accelerometer you collected above. The video below will walk you through determining the mean and standard deviation of your measurements using google sheets.

:::Figure:Video
!(https://www.youtube.com/watch?v=qAm8PiWqerQ)
:::

Include a table like the one described in your notes. Discuss the accuracy of the accelerometer's measurement of $g$ in each direction along each axis, referencing the accepted value $g = 9.807$ m/s$^2$.  Remember to make all your calculations in your notes. Consider whether the accepted value for $g$ falls within one standard deviation from the mean for your measurements? Do you know what this means? If not, give a guess.  Finally share any ideas you have about how you might do the measurement differently if you were to do it again, and why.

:::
