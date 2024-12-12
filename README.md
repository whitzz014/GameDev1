# Gane Dev Exam 2 Review 

## Week 6-7 
### About Unity -- Chapter 1
---

- unity is a platform for 2d, 2d, vr and ar games and apps 
- easily connect to people on pc, consoles, web, mobile devices, home entertainment, embedded systems, head mount displays 

### tools and resources 
--- 
- Unity Asset Store 
- Unity cloud build 
- unity analytics
- unity ads 
- unity certification 

### Unity Facts 
* 85 billion downloads per month of apps built with unity since 2020
* 2.5 billion monthly active users who used unity to create content 
* forfront of the gorwing vr market 
    * 90% of samsung gear vr games and 53% of oculus Rift(at launch) were made with unity 

### Limitations 
---
* Asset Creation 
    * Modeling 
        * Blender 
        * Maya 
        * 3ds Max 
    * Texturing 
    * Sound and Music 
    
### Intro to GameObjects -- Chapter 2 
--- 
- models are converted to GameObjects
- everything in the __hierarchy__ is a GameObj

### Components -- Chapter 3 
---
- GameObj = noun -> component = verb 

#### RigidBody 
---
- main component that enables physical behavior for GameObj 
    - adding a **rigidbody** component auto opts GameObj to physics engine 
- __Rigidbody__ attached obj auto responds to gravity 
- one or more __collider__ components added, Obj moved by incoming collisions 
- can use script to change the transform properties of the GameObj 
- w/ __rigidbody__ generally apply forces to push GameObj and let physics engine calc results 
- some cases where you want a GameObj to have a __rigidbody__ w/o having physics engine 
    - you may want to contol a character directly from script code but still allow it to be detected by triggers 
    - non-physical motion produced from script is called _kinematic_ motion 
##### isKinematic 
- tells physics engine you are manually controlling GameObj 
- physics engine is still aware of where the GameOnj is and when it collides 
    - useful because it will tell you when 2 GameObjs collide and you can do something 

##### Gravity 
- allows __rigidbody__ to opt in/out of gravity on specific GameObj

### Into to Scripting 
--- 

