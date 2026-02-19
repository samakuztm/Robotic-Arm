**About This Project**



This is a 3D printed robotic arm I built using PETG for strength and durability. The idea was to make something that’s actually functional, not just a display model. PETG was chosen because it holds up better under stress than PLA and doesn’t crack as easily when the arm is moving or lifting small loads.



The arm uses a stepper motor for the base so it can rotate smoothly and accurately, and high-torque servos (40kg and 25kg) for the main joints to handle the weight and movement without struggling. Everything is controlled by an ESP32, which keeps the setup simple while still being powerful enough for wireless control and future upgrades.



Power comes from a 3S LiPo battery, making the arm portable and able to deliver enough current for the motors and servos without voltage drops.



**Hardware**



Here’s what the build is based on:



* PETG 3D printed structural parts



* ESP32 (main controller)



* Stepper motor (base rotation)



* 40kg high-torque servo (shoulder)



* 25kg servo (elbow / wrist depending on config)



* 3S LiPo battery



* External power distribution / regulator (recommended)



**Why PETG?**



I went with PETG instead of PLA because the arm experiences constant mechanical stress. PLA can work, but it tends to get brittle over time, especially around joints and mounts. PETG has just enough flexibility to absorb shock while still being strong, which makes it a better choice for moving parts and load-bearing sections.



**How It Works**



The base is driven by a stepper motor to allow controlled rotation and positioning. The stepper motor is geared down 1:30 so that it has more torque and is able to move the weight. The main arm movement is handled by high-torque servos so it can lift and hold positions without slipping. The ESP32 handles all motor control and can be programmed for manual control, presets, or even wireless control if needed.



The 3S LiPo powers the system to ensure the servos get enough current during movement, since high-torque servos can draw a lot under load.



