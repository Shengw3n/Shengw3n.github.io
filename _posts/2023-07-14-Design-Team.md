---
layout:     post
title:      My First Year Design Team Experience
subtitle:   at UBC Rocket
date:       2023-07-14 12:00:00
author:     "Steven"
header-img: "img/rockets.jpg"
catalog:    true
mathjax: false
streamableId: v4dg4o
tags:
    - UBC Engineering
---

Engineering design teams are similar to your typical high school FIRST Robotics team, except they are bigger, better, and richer. People join them to design cool stuffs, learn technical skills, and build a strong resume for co-ops.

## Why I joined UBC Rocket
There are currently [34 design teams](https://teams.engineering.ubc.ca/the-teams/) at UBC at the time of writing. There is **[UBC Aerodesign](https://www.ubcaerodesign.com)**, which makes RC airplanes; **[Formula UBC](https://www.formulaubc.com)**, which makes Formula One cars; and of course **[UBC Rocket](https://www.ubcrocket.com)**, which makes rockets.  I wanted to join UBC Rocket because rockets are cool and they go brrrrrrr 🚀 🚀 🚀 . Here is a UBC Rocket 2023 clip:
{% include streamablePlayer.html id=page.streamableId %}
## My experience
UBC Rocket is currently divided into 3 teams working on 3 different rockets:  **Whistler Blackcomb**, a 100km liquid-fuel rocket; **Beauty and the Beast**, a 2 stage solid-motor rocket; and **Thrust Vector Rocket**, a thrust vector controlled rocket capable of 3d maneuvering and powered landing.  

I was on the mechanical and manufacture team for the Thrust Vector Rocket, focusing on the design, source, and manufacture of the landing system. What the heck is a rocket landing system?

After researching and discussing with my teammates, I decided on a straight legged design and began SolidWorking:
![img](/img/R0.png)
<p align="center">
Landing Legs V1 (tweaked from a design of a previous member)
</p>
In this design, springs were placed on top of the leg joints to act as suspension, which help absorb shock when the rocket lands.

Once everyone was done with their initial design we inputted all our CAD files together and realized we were overweight, and hence began revision #1.

## Revision #1
Where can I cut weight in my design? 

![img](/img/R1.JPG)
<p align="center">
Landing Legs V2
</p>
In this design, I used a 3 legged system instead and made its length shorter but enough for it to be functional. 

Now that the weight issue is solved, let’s start building!

![img](/img/3D.JPG)
<p align="center">
3D printing materials
</p>
![img](/img/PP1.JPG)
<p align="center">
Physical Prototype #1
</p>
The landing leg is made out of carbon fibre rod with its tensile strength calculated, the rest 3D printed.  The connections are secured using dowel pins and set screws. 

Unfortunately PHYS 170 was taught too late, as I failed to realize the forces on the landing legs did not distribute to the suspension system. 

![img](/img/Fail.JPG)
<p align="center">
Force distribution failure
</p>
## Revision #2
What design can distribute most of the force to the suspension system? (It’s impossible for 100% distribution given the suspension and the landing impact are not within the same axes.)

![img](/img/R3.jpg)
<p align="center">
Landing Legs V3
</p>
In this design the force distribution is fixed along with various optimization for the leg joints and feet. 

Alright let’s start building again :) 

![img](/img/PP2.jpg)
<p align="center">
Physical Prototype #2
</p>
Now everything will work just fine…right? 

## The Drop Test
The suspension system is working properly, it’s time for the drop test! 

If the code works properly, the rocket will only drop when it’s 10 cm away from the ground. However, given how the landing system did not hold any weight yet, we decided to do drop test at 10cm, 50cm, and 100 cm. 

![img](/img/Drop.JPG)
Ye the feet broke at the 100 cm drop…

## Revision #3
Although the landing system failed the drop test, there was only failure on the feet. Everything else survived, especially the leg joints, which failed back in revision #1.

This gave me confidence in my overall design and I began optimizing the feet. 
![img](/img/feet.png)
<p align="center">
New Foot Design 😎
</p>

![img](/img/3D1.JPG)
<p align="center">
We bought a new printer!
</p>

![img](/img/Foot.JPG)
<p align="center">
The three generation of foot design.
</p>

## What’s next?
Unfortunately I did not have enough time to build the third physical prototype for a second drop test as I will be going back to China. My work will be carried on by my teammates as we are set to compete in August 2023 for the Launch Canada Competition. 

## Conclusion 
In conclusion,  I really enjoyed working at UBC Rocket. We met every Sunday morning to afternoon and I learned a lot of valuable technical skills in the process. The team environment was also very friendly and positive and my teammates were always there when I was stuck. Definitely recommend! 




