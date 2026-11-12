## Claudiu Fugulin

I finished my Bachelor's in Robotics at Transilvania University of Brașov in 2026 and I'm now doing a Master's in Applied Informatics in Industrial Engineering at Politehnica Bucharest (FIIR).

Most of my projects mix mechanical, electrical and software work. For my thesis I designed the motor coupling in CATIA and 3D printed it, wired the stepper driver and power supply, and wrote the ESP32 firmware. I'm looking for work in robotics, embedded systems, industrial automation, electrical work, CNC machining or mechanical design.

### What I've built

**[Automatic guitar tuner](https://github.com/fclaudiu19/polyphonic-guitar-tuner-mechatronics)** (Bachelor's thesis)

An ESP32-S3 listens to a string through a microphone, finds the pitch with an FFT and turns the tuning key with a stepper motor until the string is within ±5 cents. The raw pitch readings jumped around too much to use, so I put them through median, IIR and Kalman filters. That brought the noise down from about 34 cents to about 5.

**[Robot arm dynamics and control](https://github.com/fclaudiu19/scara-robot-dynamics-control)**

Dynamic model of a two-axis arm (rotary base, lead-screw linear axis) in MATLAB, including the DC motors and gearboxes. In Simulink, computed torque control cut the tracking error about 30 times compared with independent joint PID, for the same motor effort.

**[Helical gearbox](https://github.com/fclaudiu19/industrial-gearbox-design)**

A single-stage speed reducer in CATIA V5, with the gear, shaft and bearing calculations, the full assembly and the manufacturing drawings.

### Tools I use

CATIA V5, SolidWorks, MATLAB/Simulink, C/C++, Python, ESP32, Git, 3D printing (Bambu Lab P1S)

On the electrical side I've drawn wiring diagrams, set up 12 V / 5 V power distribution and configured an industrial stepper driver (Nanotec C5-01). I also spent the summers of 2022 and 2023 as a technical inspection assistant, doing NDT (UT, MT, PT) and dimensional checks.

### Contact

fugulinflorian@gmail.com · [LinkedIn](https://www.linkedin.com/in/claudiufugulin) · Bucharest, Romania
