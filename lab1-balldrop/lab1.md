# Lab 1: Coefficient of Restitution
---
### All Materials Needed:
- Two kinds of bouncy balls
- A hard, flat surface in an open space
- Phyphox "Sound stopwatch" or an audio recording device that shows sound amplitude

### Lab Goals:
- Learn to use Phyphox for data collection
- Investigate the properties of inelastic collisions
- Familiarize yourself with experimental error

---

# Part I: Kinematics, Collision and Energy Loss

You have likely mastered the basic kinematic relations that govern projectile motion and collisions in previous introductory physics courses. In this intro lab, we will now investigate inelastic collisions, and energy loss to the environment.

####
When you drop a ball from rest, you can easily calculate its height over time until it hits the floor: the usual routine of applying Newton's equations for constant acceleration will give you a fairly accurate account of the ball's trajectory. Once the ball hits the floor, however, it loses some amount of its total energy. This is evidenced by the fact that the ball will not bounce for the rest of eternity --- its successive heights quickly decline until it comes to rest.

####
With this phenomena in mind, we can now ask about how to characterize this energy loss, if we can predict the successive bounce heights, and what the mathematical description of this kind of motion looks like. Can we develop equations which will be predictive, i.e. precise and accurate?

####

:::Question
(a) You drop a ball from a height of 1m. Derive the equation that gives the ball's height over time, until it hits the floor. 

(b) Derive two equations that give the ball's kinetic and potential energy as a function of height.

(c) What is the ball's total energy? Its potential energy at its maximum height? Its kinetic energy at the point of impact?
:::

####
## 1. The Coefficient of Restitution
When a ball bounces, and hence loses energy, your first observation may be that the speed of the ball is reduced. This observation is what led Newton to propose "Newton's Experimental Law", which is now characterized by a quantity known as the coefficient of restitution. 

####

Newton's Experimental Law states the following:  given a pair of bodies in collision, the ratio of final relative speed to initial relative speed is always the same.
####

In our ball drop experiment, one of these bodies is "Earth" and the other is our ball. Since we are naturally measuring our ball's velocity with respect to Earth (with the Earth's velocity change due to a tennis ball being negligible, of course!), we obtain the following mathematical sentence:

:::Figure:Equation
$$
\epsilon = v_f/v_0
$$
:::

Which, in ideal circumstances, applies to all collisions between these two bodies. The $\epsilon$ here is our definition of the [coefficient of restitution](https://en.wikipedia.org/wiki/Coefficient_of_restitution). 

:::Question
(a) Rewrite equation 1 in terms of the ball's kinetic energy before and after collision.

(b) From Question 1, if $\epsilon=0$, what is the ball's energy after the first bounce? What is its next maximum height?

(c) If $\epsilon=1$, what is the ball's energy after the first bounce? What is its next maximum height?
:::

# Part II: Experiment
## 1. Overview
Our job in this lab will be to verify Newton's Experimental Law, calculate $\epsilon$ for different balls, hypothesize what affects this constant, and use our results to make and test a prediction.




## 2. Force on current-carrying &ldquo;wire&rdquo; near a magnet
### Materials needed:
- Neodymium magnet
- 1 Wire 
- One AA battery
- Steel screw
- Thin strip of Aluminum foil, approximately 15 cm long
- Tape
- Paper towel roll or similar, cut into a 1-in and 2-in section
- Piece of paper (optional)


Most of us don&rsquo;t have access to beams of charged  particles in free space (or methods to observe them easily), making a demonstration of Lorentz's force law similar to the simulation above quite impossible. Luckily for us, the force law is ubiquitous, and equally applies to the moving electrons in *materials* -- such as current-carrying wires. 

In a wire, a current is carried by many electrons moving along its length due to the voltage difference between its ends -- recall that, in this case,

:::Figure: Equation
$$
\vec I = q_e n A\vec v 
$$
::: 

where $n$ is the number of electrons per unit volume, $q_e$ is the charge of an electron,  $A$ the cross sectional area of the wire, and $\vec v$ is the electron drift velocity. When a current-carrying wire is brought close to a magnetic field source, these electrons will be subject to the Lorentz force, whose magnitude and direction is determined by the electron velocities and the external magnetic field. In the following experiment, you will demonstrate and verify the Lorentz force by generating a current though a wire and observing the effect of a magnetic field. 

:::Question
(a) Sketch a picture of a simple wire with a voltage difference across its length, indicating the $+$ and $-$ ends explicitly.  Draw an arrow indicating the direction of the current.

(b) What direction does the velocity vector, $\vec v$, point? Draw an arrow indicating this direction. (Recall the charge of the electron)
:::






::: Exercise
In this experiment, we will tape a strip of aluminum foil, which behaves as a &ldquo;wire,&rdquo;  so that it runs perpendicular to the field generated by our magnet. When you connect the foil to the terminals of a battery, such that a current is generated, you will observe and record the effects of the Lorentz force, and explain if it matches your expectations based on the &ldquo;right hand rule.&rdquo; The reason for using foil is its thickness -- it is much easier to observe &ldquo;bending&rdquo; in foil vs. stiffer wire. 
:::Figure:Figure
  ![](imgs/foilsetup.jpg)
:::
***Foil Circuit:***
1. Tape the aluminum foil strip to the 1-in roll section so that it runs across the diameter, leaving a small amount of slack. The foil shouldn’t be so taught that it can&rsquo;t bend slightly.
2. Place this, with the foil upwards, on a piece of paper (or table) and use tape to fasten the aluminum foil to the paper on either side, being sure to leave an exposed region to connect to the battery.
3. On one side, tape the exposed wire lead to the aluminum foil.
4. Attach the magnet to the flat end of the screw, noting the orientation of the magnet. (Its faces should be labeled from the previous lab.)
5. Place the 2-in tube parallel to the foil and push the screw through it so that the magnet sits just perpendicular to the foil strip.
6. Hold the battery on the exposed foil, and briefly touch the opposite terminal with the wire to close the circuit.
7. Note the orientation of the magnet and the direction of current and record these and the direction of motion of the foil. (See the next step.)
8. Repeat this experiment for all four combinations of magnet orientation and battery orientation. Make a table similar to the following to record your results for each magnet and battery orientation, the prediction for the force direction given by the right hand rule and the observed direction of foil movement:
:::Figure:Table
| Magnet Orientation | Battery Orientation | RHR |Foil Direction |
| --------  | --------      | --------     |--------     |
| (N/S) toward foil  |    (+/-) up   |  (up/down)    |           (up/down)    |               
|$\:$         |               |              |          |
|$\:$         |               |              |           |
|$\:$         |               |              |           |
:::
######

**(! IF YOU HAVE NOT RECEIVED YOUR IOLAB YET AND DON'T KNOW THE ORIENTATION OF YOUR MAGNET FROM LAB 0, PLEASE LABEL THE MAGNET SIDES 'A' AND 'B' AND VERIFY AFTER YOUR DEVICE HAS ARRIVED !)**

::: Question
(a) Are your observations consistent with the right hand rule?

(b) How does the motion of the foil change after you switch the battery orientation? Why?
:::



:::Question
The Lorentz force acts on the electrons in the foil. Try to explain why the *entire* foil moves, and not just the electrons.
:::
:::


## 3. The Rotating Motor
### Materials needed:
- Neodymium magnets
- Wire Leads (stripped)
- One AAA battery
- One screw

In this setup, we will be creating a simple homopolar motor. Homopolar motors, first constructed by Michael Faraday in 1821, prior to the discovery of electromagnetism, operate based on the Lorenz force: A conductor with a current flowing through it, when placed in a magnetic field that is perpendicular to the current, feels a force in the direction perpendicular to both the magnetic field and the current. This force provides a torque around the axis of rotation.



In this exercise we will construct this direct current (DC) motor using a battery as our voltage source and our neodymium magnet as the conductor and perpendicular field source. The magnet will be connected with the battery by means of a screw, whose sharp point has minimal friction and allows for free rotation. When wire leads are used to close the circuit, the current running from the magnet’s outer surface to the screw at its center, in conjunction with the magnetic field, will result in a force on the moving *electrons* inside the magnet, causing it to rotate rapidly!

:::Question
![](imgs/Currentdisk.png)

The above image shows a disk with a conductive surface connected to a circuit with current $I$. Sketch the path that electrons might take, with arrows indicating the direction of the velocity.
:::

By noting the direction in which the current is flowing, as well as the direction of the field of the magnets (found in Lab 0 and verified in the previous exercise), we can apply the right-hand rule to determine the direction of the magnetic force, and verify that our results are consistent with the observed direction of rotation.



::: Exercise
With the knowledge of the magnet&rsquo;s orientation from the previous lab, we will now construct a simple homopolar motor by following these steps:

***Homopolar Motor Construction:***
1. Strip the plastic from both ends of the wire, exposing the copper strands, allowing the wire to conduct. 
2. Place the flat head of your screw on top of the neodymium magnet, with the north (⨀) pole facing upward. The screw should now also be magnetized so that picking it up also picks up the magnet beneath it.
3. Holding the battery in the air with the positive terminal facing up, touch the negative terminal to the pointed end of the screw. The magnetization should allow you to pick up the screw + magnet by lifting the battery.
4. Hold one end of your exposed wire against the battery’s positive terminal.
5. Once everything is connected, gently touch the other end of the wire lead to the side of the magnet (ie, perpendicular to the magnet’s surface)
6. If you do this correctly, the screw should rotate.

::: Figure:Figure
![motor](imgs/1.png)
:::
######

You have now completed the motor setup for one of four possible orientations of the magnet and battery. Recall from our previous discussion that when these fields are perpendicular, $F= q vB= I L B$, and the direction of the force is given by the right-hand rule. Because this current is localized to the region of the magnet connecting the wire to the nail, the force acting upon  the individual electrons results in a torque that spins the entire magnet. You will use the right-hand rule to predict the direction that the magnet will spin based upon the orientation of both the battery and the magnet.

Make a table like the one below and record your results for all four possible combinations of your battery and magnet orientations, prediction based on the right hand rule (RHR), and the observed direction of rotation:

:::Figure:Table
| Magnet Orientation | Battery Orientation | RHR|Rotation Direction |
| --------  | --------      | --------     |--------     |
| (N/S) up  |    (+/-) up   | (CW/CCW)  | (CW/CCW)    |                    
|$\:$         |               |              |  |
|$\:$         |               |              | |
|$\:$         |               |              | |
:::

**(! IF YOU HAVE NOT RECEIVED YOUR IOLAB YET AND DON'T KNOW THE ORIENTATION OF YOUR MAGNET FROM LAB 0, PLEASE LABEL THE MAGNET SIDES 'A' AND 'B' AND VERIFY AFTER YOUR DEVICE HAS ARRIVED !)**


::: Question
Sketch an illustration showing each of the 4 possibilities. Include arrows to show the direction of the magnetic force from the right-hand rule, and labels to indicate the direction of current flow. 
:::
:::

## Part III: Write-up
 - For Part I, give a short summary of the Lorentz Force and the Right-Hand Rule. 
 - For Part II, write a short paragraph describing the procedure taken and any important observations for each Exercise. Be sure to summarize your results and reasons why you believe your data are precise and accurate. If you do not think your data are accurate, explain why, and how it could be fixed in a future lab.
 - You are encouraged to attach images of your plots,  data, and setup -- doing so may allow you to regain partial or full credit even if your experiment fails.
 - At the end of your write-up, please include the answers to all questions, clearly numbered. Show your work if applicable.