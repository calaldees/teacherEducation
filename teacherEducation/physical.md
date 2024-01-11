Physical Computing - Tangible Computing
=======================================

A different slant on computing. 
Manifest your code in the real world!
Vital for young people seeing the [[culturallyRelevantComputing]]

There are a range of small computer boards that are programmable with c/python/etc that can attach to LEDs/Motors/Sensors.
These educational tools take code off the desktop screen and into the physical world.



* TODO
    * [Program Comprehension with Physical Computing: A Structure, Function, and Behavior Analysis of Think-Alouds with High School Students](https://dl.acm.org/doi/10.1145/3430665.3456371) 2020
    * [The Cambridge Handbook of Computing Education Research: Chapter 22 Tangible Computing](https://www.cambridge.org/core/books/cambridge-handbook-of-computing-education-research/tangible-computing/3BE6A6D5D94493EF725C46896DACD46C) 2019
        * Younger learners - conceptual metaphor theory - more manifestation - (Like Early Turtle)
        * Manifest in real world - art

* [Are There Differences in Learning Gains When Programming a Tangible Object or a Simulation?](https://dl.acm.org/doi/10.1145/3304221.3319747) ITiCSE '19: Proceedings of the 2019 ACM Conference on Innovation and Technology in Computer Science EducationJuly 2019
    * > we aimed to determine whether the programming of a tangible object or its digital simulation yields significantly different learning gains.
    * > no significant difference was found when comparing the learning gains between the two groups.

* [NCCE - Quick Read: Physical computing](https://blog.teachcomputing.org/quick-read-physical-computing/)
    * ![quick-read-physical-computing diagram](https://blog.teachcomputing.org/content/images/2021/09/QR_16_Diagram_A.png) Hodges Sentence, Finney and Ball 2020

* [Program Comprehension with Physical Computing: A Structure, Function, and Behavior Analysis of Think-Alouds with High School Students](https://dl.acm.org/doi/10.1145/3430665.3456371) Jayathirtha & Kafia 2021
    * (See [[block_model]] "Behaviour" for understanding of the terms)
    * ("Interactive" in the context of this article means interacting with the physical object. "Active" means seeing/observing )
    * we qualitatively analyzed think-aloud interview videos of 22 high school students individually comprehending a given text-based Arduino program while interacting with its corresponding functional physical artifact 
        * 1. How do novices comprehend the given text-based Arduino program? 
        * 2. What role does the physical artifact play in program comprehension?
    * We found that novices mostly approached the program bottom-up, initially comprehending structural and later functional aspects, along different granularities. 
    * The artifact provided two distinct modes of engagement, active and interactive, that supported the program's structural and functional comprehension. However, behavioral comprehension i.e. understanding program execution leading to the observed outcome was inaccessible to many. 
    * Our findings extend program comprehension literature in two ways: 
        * (a) it provides one of the very few accounts of high school students' code comprehension in a physical computing context, and, 
        * (b) it highlights the mediating role of physical artifacts in program comprehension. 
    * Further, they point directions for future pedagogical and tool designs within physical computing to better support students' distributed program comprehension.
    * > . For the most part, the abstract run-time program behavior i.e. comprehending data and control flow was inaccessible to the novices
    * the invisible abstract program behavior was hard to comprehend. This points to a need to explicitly support novices in computing classes to understand run-time program behavior. Guiding students to understand program dynamics at appropriate levels of abstractions, also called [[notional-machine]]
    * Their limited success with reasoning program behavior calls for explicit integration of [[notional-machine]] within programming education




### Lego Mindstorms - Robotics

* [Lego Mindstorms](https://www.lego.com/en-gb/themes/mindstorms)
    * £300 a kit
* [FIRST Lego League](https://www.firstlegoleague.org/)
    * [Institute of Engineering and technology - Find a tournament near you! - FIRST® LEGO® League programmes FIRST® LEGO® League Challenge (9-16)](https://education.theiet.org/first-lego-league-programmes/challenge/find-a-tournament-near-you/)
        * Hosted at the University of Kent
    * [2020 Challenges description video](https://www.youtube.com/watch?v=QeN0hkyF5XQ) (6min)
        * [405pt](https://www.youtube.com/watch?v=OVtsmME6S9Q) (2min)
        * [305pt](https://www.youtube.com/watch?v=iIAiIwWNcas) (2min 30sec) actual competition
    * Lots of time/money/logistics investment (only a handful of students benefit)
    * Extra curricular only
    * Looks AMAZING at open evening
    * Hello World 30min Podcast [Are computing competitions worth the effort?](https://web.archive.org/web/20221210024231/https://helloworld.raspberrypi.org/articles/are-computing-competitions-worth-the-effort)
* See also
    * Battlesnake, yare.io, [[_software]]
    * YouTube: Veratasium [MicroMouse](https://www.youtube.com/watch?v=ZMQbHMgK2rw) 25min mini documentary



### Micro-boards

#### Microbit

* [[microbit]]
TODO: Magic trick - on shake send message - move image to another microbit

* [Introduction to micro:bit: sensors, buttons and lights!](https://projects.raspberrypi.org/en/pathways/microbit-intro)

* Possible use for whole class teaching because of good web simulators
    * You don't need physical devices for every student (they can share - in non covid times)
* Block + Python + Javascript
    * Differentiation + Progression

TASK 10min?
* From your async task exploration - possible project ideas?


#### Arduino



#### TinkerCAD

* [TinkerCAD](https://www.tinkercad.com/) (Arduino + Electronics)
    * Breadboards and circuit design. Combine code and electronics
    * `C` in the browser. Blocks for beginners
    * Suitable for whole class teaching
    * Surprisingly high skill ceiling! Used at universities for teaching electronic design


TASK: Spend 20min attempting to recreate the first steps of this project
* [Program an LED Light Show](https://www.tinkercad.com/lessonplans/program-an-led-light-show)


#### Other Arduio IDE's

* [xod.io](https://xod.io/) - A [[visual-programming]] language for microcontrollers - browser IDE


#### Arduino - Adafruit Circuit playground

* [[arduino_adafruit]]

All in one

* Physical device needed - whole class set required
* Good introduction to `C`




### Raspberry Pi

Extra curricular - not really suitable to full class teaching

* Need access to keyboard, mouse, monitor, power
    * Some schools have 'all in one' machines so screens can't be reused
    * USB ports (for keyboard/mouse) may not be accessible for school machines
    * Frequent use of USB ports can damage with ports (kids are fairly heavy handed)

* Network use in a school
    * MAC address's of devices may be blocked or applied to quarantined network
    * School WiFi may not be possible (passwords?)
        * Separate wifi?
        * Your own reconfigured router? (no internet?)
    * Your own physical network (They LOVE this)
        * Consider your own DHCP server (use an old home wireless router?)
            * problems with genuine external access
                * To install packages + reach documentation
        * Manual entry of IP address's and subnets

* £70? Machine only
    * £60 Raspberry Pi 5 (4gb)
    * £10 Heatsync
    * £5 power
    * £10ish per pupil XD-card/USB3-storage
* Need screen and keyboard


Cool hardware
-------------

Just having tech around the school

* Barcode scanners
    * Checkout project demo?
    * [The Barcode Pony, or: How To Actually Scan A Zebra](https://www.youtube.com/watch?v=3VcgW_AdDPw) YouTube 3h
* Thermal receipt printers
    * Used for rewards
* Thermal camera
* USB microscope
* RFID reader (coupled with thermal printer!!)
* Magnetic card reader/writer
* Head tracking
    * YouTube [Head Tracking for Desktop VR Displays using the WiiRemote](https://youtu.be/Jd3-eiid-Uw?si=WnKNrPQIBs9KP0SN) 6min
* leap motion (£40)
    * https://www.ultraleap.com/leap-motion-controller-whats-included/
    * https://www.youtube.com/watch?v=xzn-mLEjRZw
* etextiles - wearables - fassion
    * Strips of LEDs
    * https://learn.adafruit.com/gemma-led-sneakers
    * https://learn.adafruit.com/category/led-strips
    * https://learn.adafruit.com/cardboard-obsidian-sword
* Bus [Flip Disc Display](https://en.wikipedia.org/wiki/Flip-disc_display)
* VR?

* [The Basics Of Persistence Of Vision Projects](https://hackaday.com/2019/10/29/the-basics-of-persistence-of-vision-projects/)


Discussion
----------

* What are the drawbacks of physical computing?
    * Why is this so fragmented? why as few schools investing in this?
* Should we have a SOW using physical/extra hardware?
    * What year group?
    * For what?
    * Why?
* Year 9 - get them buzzed!


[//begin]: # "Autogenerated link references for markdown compatibility"
[culturallyRelevantComputing]: culturallyRelevantComputing.md "Culturally Relevant Computing"
[block_model]: block_model.md "block_model"
[notional-machine]: notional-machine.md "Notional Machine"
[_software]: _software.md "Education Software"
[microbit]: microbit.md "Microbit"
[visual-programming]: visual-programming.md "Visual Programming"
[arduino_adafruit]: arduino_adafruit.md "Arduino Adafruit"
[//end]: # "Autogenerated link references"