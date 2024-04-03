# ambiens-sc1-ctrl-board

The Ambiens SC1 Control Board is the heart of a smart heated 3D printer chamber designed to create an optimal environment for 3D printing by precisely controlling temperature and air quality. It continuously monitors the air quality inside the chamber using two BME680 sensors to assess the Indoor Air Quality (IAQ). Depending on the IAQ levels, a PWM fan is activated, working in conjunction with a HEPA filter and activated charcoal filters to purify the air.

To maintain the ideal temperature for different printing materials, the chamber utilizes a generic 12V PTC heater (120W) paired with a fan. The system's safety is enhanced by a 100k NTC sensor embedded in the PTC heater to monitor its internal temperature, alongside a thermal fuse to prevent overheating by automatically cutting off the heater if temperatures exceed safe levels.

The control board is powered by an ATX PSU and interfaces with a Raspberry Pi 3B via I2C, offering a smart, modular solution for 3D printing enthusiasts looking to optimize their printing environment for quality and safety.
