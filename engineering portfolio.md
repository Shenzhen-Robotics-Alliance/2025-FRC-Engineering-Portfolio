# Engineering Portfolio
---
## Hardware
This year, we designed a test robot, similar to the one used in the competition. The purpose of this robot is to help drivers gain experience before the competition, preventing them from starting to operate the robot just before the event. Additionally, the programmer can gather valuable data regarding the robot’s performance. Compared with last year, we have finished 2 robots and also help other teams which are near our school. Our efficiency is significantly enhanced faster than ever before. 
---


+ ### Intake & Shooter
    <br>At the beginning of the new season publicize, we explored various schemes to optimize the intake system. Initially, we used a rubber wheel to intake the Coral, which proved highly effective. Fortunately, the test part meets our expectations, and we decided to use this design for the intake part. Building on this, we designed a curved structure to intake so that this component is able to catch both Coral and Algae. 
    <br>![coral](coral.jpg)

<br>To increase the probability of intaking coral from the station, we installed a trapdoor with a funnel that captures the Coral at the top of the robot. Once the funnel intakes the Coral, it is sent directly to the shooter, which handles the scoring action. Considered there are another game elements –Algae which is put on the reef and should our robot remove it from the reef. We have found an innovative way to solve this problem. The back of the shooter is curved to grab the Algae from the reef. The rubber wheel in the shooter will reverse its rotation to get this game element. With the help of “elevator”, the help can put the Algae to the net. 
<br>![coral](algae.jpg)

<br>To further enhance efficiency and accuracy, we integrated four cameras working with four Orange Pi devices to recognize the field's QR Codes, allowing for precise location tracking. When our robots close to the reef, the robot will locate the correct location which is suitable to hang the coral with the help of coding. It greatly reduces the pressure on drivers. 
<br>![coral](orange.jpg)

<br>Furthermore, we included an "Elevator" mechanism that raises the shooter to Level 4, giving us access to the highest point in the competition. Additionally, the shooter is equipped to drop the Algae into the net. In addition, we included an "Elevator" mechanism that raises the shooter to Level 4 and up to the net, giving us access to the high points in the competition. 

---
+ ### Climb
    <br>Catching the cage presented a tough challenge. Therefore, we designed two hooks to securely latch onto the cage. This is a special structure which does not need electricity to work. The shape of two hooks is like a triangle, thus making the cage will not escape from the hooks. During this process, two hooks will come together until the hook locks the cage. It will only take less than 5 seconds. Before catching the cage, the trapdoor opens, raising the hooks to help lift our robot off the ground and achieve the Climbing score. 
    <br>![coral](hook.jpg)

    <br>At the same time, we used a number of carbon fiber components to reduce the weight of the robot, making it both lightweight and strong for the task. 

---
## Software

+ ### Driving system & Auto
    In this season, we have focused our software development on simulation technology and the autonomous capabilities of robots. Before the machines were completed, we spent nearly a month developing a simulation engine capable of fully replicating the physical characteristics of real machines. Thanks to this special technology, we were able to develop a semi-autonomous driving system that almost frees up both hands and a stable, self-decision-making autonomous system within a week after the machines were completed.Simulation Technology



+ ### Simulation Technology
    Simulation technology refers to using physics engines to emulate the characteristics of real machines, allowing software testing to commence before the machine is finished. In FRC, it is not a new technology; many teams already use simulation to test program logic. However, currently, simulators can only handle relatively simple simulations, such as simulating the gravity of a single arm or lift. <br> And our simulator uses a more comprehensive open-source physics engine, dyn4j. It can not only simulate gravity and friction but also perform collision simulations for objects.![dyn4j](dyn4j.PNG) <br> Additionally, we use the open-source project AdvantageScope from Team 6328 in the USA.
    ![AdvantageScope](image.png)