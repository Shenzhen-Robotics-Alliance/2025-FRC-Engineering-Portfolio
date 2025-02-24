# Engineering Portfolio
---
## Hardware
<br> 
This year, we designed a test robot similar to the one used in competition. The purpose of this robot is to help drivers gain experience before the competition, preventing them from starting to operate the robot at the last minute. Additionally, the programming team can gather valuable data regarding the robot’s performance. Compared to last year, we have successfully built two robots and assisted other teams near our school. Our efficiency has significantly improved, making us faster than ever before.

---


+ ### Intake & Shooter
<br>At the beginning of the new season, we explored various designs to optimize the intake system. Initially, we used a rubber wheel mechanism to intake Coral, which proved highly effective. Fortunately, the test results met our expectations, leading us to adopt this design for the intake system. To further enhance efficiency, we designed a curved structure that allows the system to intake both Coral and Algae.
<br>![coral](coral.jpg)
<br>
To increase the likelihood of successfully intaking Coral from the station, we installed a trapdoor with a funnel at the top of the robot to guide the Coral into the shooter. Once inside, the shooter takes over to complete the scoring process.
Considering that Algae is another game element placed on the reef, our robot needed a mechanism to remove it efficiently. We developed an innovative solution: the back of the shooter features a curved structure designed to grab the Algae from the reef. The rubber wheel in the shooter reverses its rotation to collect the Algae, which is then transferred using an "Elevator" mechanism that lifts it into the scoring net.
<br>![coral](algae.jpg)
<br>
To further enhance efficiency and accuracy, we integrated four cameras working in tandem with four Orange Pi devices to recognize QR codes on the field, enabling precise location tracking. When our robot approaches the reef, it identifies the optimal position for hanging the Coral, reducing the burden on the drivers. 
<br>![coral](orange.jpg)
<br>
Additionally, our shooter is designed to elevate to Level 4, allowing us to reach the highest scoring zones. The "Elevator" mechanism not only raises the shooter but also helps position the Algae for scoring in the net.

---
+ ### Climb
<br>Catching the cage in the competition is a crucial challenge. To address this, we designed two specialized mechanical hooks that securely lock onto the cage without requiring electricity.
The hooks are powered by rubber bands, utilizing a triangular structure that causes them to retract inward. When the robot approaches the cage and triggers the hooks, they will quickly snap into place, tightly locking onto the bottom beam of the cage. This process takes less than five seconds, significantly improving climbing efficiency and reliability.
<br>![coral](hook.jpg)
<br>
Additionally, we incorporated carbon fiber components to reduce the weight of the robot, ensuring it remains both strong and lightweight, providing better support for climbing.


---
## Software

+ ### Driving system & Auto
    In this season, we have focused our software development on simulation technology and the autonomous capabilities of robots. Before the machines were completed, we spent nearly a month developing a simulation engine capable of fully replicating the physical characteristics of real machines. Thanks to this special technology, we were able to develop a semi-autonomous driving system that almost frees up both hands and a stable, self-decision-making autonomous system within a week after the machines were completed.Simulation Technology



+ ### Simulation Technology
    Simulation technology refers to using physics engines to emulate the characteristics of real machines, allowing software testing to commence before the machine is finished. In FRC, it is not a new technology; many teams already use simulation to test program logic. However, currently, simulators can only handle relatively simple simulations, such as simulating the gravity of a single arm or lift. <br> And our simulator uses a more comprehensive open-source physics engine, dyn4j. It can not only simulate gravity and friction but also perform collision simulations for objects.![dyn4j](dyn4j.PNG) <br> Additionally, we use the open-source project AdvantageScope from Team 6328 in the USA.
    ![AdvantageScope](image.png)