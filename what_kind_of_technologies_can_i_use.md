# What kind of technologies can I use?

Creating a prototype usually means you are working on an artifact that will soon go through a series of iterations. As a consequence you won't probably focus on small details and finishings (unless they are specifically needed for testing purposes), and you will try to have a working version as soon as possible.

Most of the time rapid prototyping techniques will do the job to produce your prototype. A series of technologies will come in hand to rapid-prototype your idea:
* [3D printing](#3d-printing)
* [Laser cutting](#laser-cutting)
* Milling (coming soon)
* [Microcontrollers](#Microcontrollers)

### 3D printing
3D printing is a technology usedto create plastic shapes from 3D models.  There is a wide variety of 3D printers available, that start from as cheap as 150 Euro to as expensive as 10K Euro.  Stability, speed, and quality of finished product are all factors that control the price.    For simple prototyping we need a machine that can produce decent results, you can use the guide here for comparisons on which machine to buy https://www.3dhubs.com/best-3d-printer-guide and what results to expect.   
The file format for your files needs to be in STL, which you can generate using a wide variety of software, starting from commerical pro packages such as Solidworks, or other 3D alternatives such as Opencad, or for simple prints you can use a cloud service such as [Thingiverse](https://www.thingiverse.com/). 

### Laser cutting
Laser cutting is a technology used for cutting flat surfaces of wood, plastic, or cardboard and paper.  Metal and resins (and of course mirrors!) are not materials that you can use laser technology with, to work with those you can explore other technologies like milling.   Depending on the laser power of the machine you are using (form 40W to 100W mostly) you can adjust the laser power and speed to for perfect results with your material thickness.  Adjusting speed and power we can also use laser for engraving or itching, which is simply used for drawing on a surface. 
The machine operator is familiar with the adjustments needed for each machine based on experience, and guidebook. If you are using the machine for the first time, allow time for trial and error.    Laser cutting uses 2D files in different formats.  Below are a few links that include tips on how to use and fine tune your operation:
* http://www.instructables.com/id/10-Tips-and-Tricks-for-Laser-Engraving-and-Cutting/
* http://www.instructables.com/id/How-to-Use-a-Laser-Cutter/

### Microcontrollers
#####(Arduino, friends & cousins)
Technically a microcontroller is a

> "small computer [...] on a single integrated circuit containing a processor core, memory, and programmable input/output peripherals." 

https://en.wikipedia.org/wiki/Microcontroller

What non-professionals of the IT fields usually refer to when they talk about microcontrollers are actually microcontroller-based platforms that will let you connect electronic components like sensors and actuators and read/write data through the input and output ports of the chip.

Why are this piece of electronics interesting and useful? Simply put, they can make an artifact "smart":
- they can sense, process and react to events taking place in an environment
- they can make a human interact with a device on a deeper layer, for instance recalling different settings, programming it according to specific inputs or generating desired outputs

The list of electronic components you can connect to one of this boards is potentially infinite. For instance you can have:
- a light sensor trigger a motor when the sun has reached a certain position and moving a blind
- an accelerometer detect the fall of a person and trigger a phone call to a doctor

The most popular hardware prototyping platform to create physical interactive devices is probably [Arduino](http://arduino.cc). It features a hardware board where you can connect the electronic components, and a software you can use to program its behavior.

What made Arduino stand out is the accessibility and ease-of-use, in fact it was designed and developed to let non-programmers do a programmer work. Also, being an open source project it generated an environment of derivated boards, plugins and add-on modules. Using this modules and the examples provided sometimes you don't even need to know about electronics and programming at all.

Another platform growing in popluraity is [Raspberry Pi](https://www.raspberrypi.org/). The computational power on this platform is harder when compared to an Arduino, at the same time it requires higher programming skills.

**How to choose a microcontroller? -** Hard to say, it really depends on the needs of the project. Things to consider are:
- amount of inputs and outputs that are needed to connect all the sensors and actuators
- computational power
- size of the device
- destination of the device (eg. wearable device)
- your own programming and electronics skills
- particular tech needs (internet connection, audio processing capabilities etc...)
- cost

*Here are two useful articles to help you choose the right board for your project:*
* http://makezine.com/2014/02/07/which-board-is-right-for-me/
* http://makezine.com/comparison/boards/

|TIPS|
|-|
|**Power is nothing without control.** Do not aim for the most powerful boards just because more power is better. Try to find the best pick for your projects needs!|
|**Smaller is not always better.** If you have room, don't go for the smallest board just because it's cool, you might find yourself in need of adding more components while iterating on your prototype and you will need more inputs/outputs|
||