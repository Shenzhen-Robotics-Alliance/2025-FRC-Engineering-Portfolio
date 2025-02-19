# Engineering Note
---
## Hardware

+ ### Intake&Shooter

    In the beginning, we tested many schemes to test the intake part, and we tried many schemes. <br> At first, we used a rubber wheel to intake the Coral. The effect is good, on this basis we designed a curved structure, it is also able to intake the Algae. inthe toop of the  robot, we install a trapdoor with a funnel that take the Coral from the station. <br> In addtion, the Intake will take the Algae off the reef. This special structure ensures we can intake both game elements. At the same time, it could reverse rotating and become shooter to hang the Coral. To enhance our efficiency of getting scores, we installed 4 cameras Cooperate 4 orange pi to recognize the Code in the field. <br> Also, we install an "Elevator" to risse the shooter to reach the Level 4 which offer the highest point in the competition. 



+ ### Climb
    Catching the cage is also a giant challenge, we designed two hooks to catch the cage. Before catch the cage, the trapdoor will open so that the catch will rise to help our robot leave the ground and get the Climbing score.  


#

---
## Software

+ ### Driving system&Auto
    In this season, we have focused our software development on simulation technology and the autonomous capabilities of robots. Before the machines were completed, we spent nearly a month developing a simulation engine capable of fully replicating the physical characteristics of real machines. Thanks to this special technology, we were able to develop a semi-autonomous driving system that almost frees up both hands and a stable, self-decision-making autonomous system within a week after the machines were completed.Simulation Technology



+ ### Simulation Technology
    Simulation technology refers to using physics engines to emulate the characteristics of real machines, allowing software testing to commence before the machine is finished. In FRC, it is not a new technology; many teams already use simulation to test program logic. However, currently, simulators can only handle relatively simple simulations, such as simulating the gravity of a single arm or lift. <br> And our simulator uses a more comprehensive open-source physics engine, dyn4j. It can not only simulate gravity and friction but also perform collision simulations for objects. <br> Additionally, we use the open-source project AdvantageScope from Team 6328 in the USA.123456789