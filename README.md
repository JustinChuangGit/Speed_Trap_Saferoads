# Portfolio Project: Speed Trap 

![image](https://github.com/JustinChuangGit/Speed_Trap_Saferoads/assets/80928888/bf566e9a-907d-4da6-8061-9a4ca8ab7f16)
![image](https://github.com/JustinChuangGit/Speed_Trap_Saferoads/assets/80928888/96849f6a-e682-495b-8aa2-25999100ee1b)


## Project Description 
Saferoads Engineering's research and development division is responsible for designing highway safety products. This involves conducting crash tests to assess the effectiveness of these products. My primary role in the organization included both conducting these tests and constructing devices to facilitate their execution. To maintain consistency across various crash labs, standardized protocols, Manual for Assessing Safety Hardware (MASH), are in place. A critical variable in these tests is the collision speed, leading to my assignment of developing a system to precisely measure the instantaneous speed at impact.

## My Contributions
I engineered a speed trap employing two infrared light beams. Upon interruption of these beams, the time is recorded, followed by a straightforward velocity calculation using the formula v=d/t. The resulting speed is then displayed on the screen. For the IR emitter, I utilized a 555 timer to generate a frequency matching the expectation of the IR receiver. I first simulated this setup in Microcap and later validated the actual product using my oscilloscope. The computation and display processes were powered by an ESP32. The housing and mounts were designed using Solidworks and subsequently produced through 3D printing.

## Results 
The speed trap was successfully able to record speed data inside, however, when placed outside, the pollution of IR light from the sun led to incorrect readings. To fix this I would have printed the housing using a dark filament to minimize the amount of light hitting the sensor. 

*Note: I am unable to post the code for this project as it is owned by Saferoads Engineering
