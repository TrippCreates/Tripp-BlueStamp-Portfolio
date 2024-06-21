# Foam RC Airplane
My first large-scale project was the Foam RC Airplane that I built from scratch. The biggest challenge of this project came when trying to make the plane balanced and easily flyable. I was a worse pilot than I was an engineer. Even so, I knew almost nothing about aerodynamics and any physics overall going into this, but that made the experience much better because I learned so much from it. The biggest takeaway is that integration is really hard. I easily put together the electronics and then in turn, the hardware, which was just a foam plane design I made up, but integrating the two and getting them to work well together took literal months, where every night I was attempting to get the two opposing forces to come together in harmony

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Tripp T. | Los Gatos High School | Aerospace/Mechanical Engineering | Junior

## [Back To Homepage](./index.md)


<!--**Replace the headshot below with a picture with the plane. Follow the guide [here](https://tomcam.github.io/least-github-pages/adding-images-github-pages-site.html) if you need help.**-->

![Crash](./images/Crash.jpeg)



# Third/Final Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/_G9nHn8xFMI?si=Z0ufIZd0SuiaE42G" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

This was the last milestone for my plane project, which was a successful flight of around 15-20 seconds. My original stated goal for the venture was to take off and land; however, my piloting skills were so bad that it really just came down to proving my design was flyable. A much better pilot than myself would have likely thrived with my plane. However, I am not a pilot. So, for my fifth iteration of the plane, I was satisfied with what I got and figured through all the hardship, late nights, and endless YouTube tutorials, I could call it a win. 

My biggest challenge for this part of the project was just creating consistent conditions for myself so that I could get better at flying without damaging the plane. 

For this part of my project, I learned a lot about resilience. I knew that the design that I held in my plans worked; it really just came down to myself becoming a better flying and figuring out a way to do that without constantly crashing my plane. 

This was my first true engineering project. It was a wonderful experience and spurred me to continue pursuing my passion and fervor for the subject. While it was hard to stay persistent, I learned a lot about creating things and even more about what I love. 


# Second Milestone
<!---For your second milestone, explain what you've worked on since your previous milestone. You can highlight:
- Technical details of what you've accomplished and how they contribute to the final goal
- What has been surprising about the project so far
- Previous challenges you faced that you overcame
- What needs to be completed before your final milestone--> 
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZehPrCIDyY8?si=jOcj3EqlN-hbe0HE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

This is the second milestone of my foam RC Plane. For this milestone I am making solid attempts at flight, but still struggling to get consistently up in the air.

So far, the most surprising part of the project is how simple yet complicated it is. The things that I thought would be hard like building the hardware, or setting up the arm to be wireless, turned out to be easier than I originally predicted. But the stuff I thought would be simple, like wiring, batteries, and LEDs, became much harder. For example, while simple, the LED was so difficult to handle because of their flimsy legs, and I ended up using a lot more LEDs than I thought I ever would since they were so hard to deal with. 

Before I can say I have completed my third and final milestone, I need to be able to control my arm wirelessly. Whether with Bluetooth on the phone like I showcased here or with Radio Control or something different. I do not know how difficult it will be to go from controlling an LED wirelessly to controlling a whole robotic arm, but I am excited about that challenge. 

# First Milestone
<iframe width="560" height="315" src="https://www.youtube.com/embed/JJNtc4UcqHM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For my first Milestone, I present my Robotic Arm Claw. It is controlled by two Potentiometers that send inputs to the nano, which process them as outputs for the servos. I faced many challenges while trying to complete this milestone. Let's go over a few.

While building the arm itself, I realized multiple servos I was using were not working, so I had to take a bunch of them out, do a lot of testing, and then try and find enough servos that worked to make my project work. I found a code that made finding out which servos worked easy, so this greatly streamlined my process.

While trying to wire the arm, I discovered how detail-oriented I needed to be. If even one wire were out of place, nothing would work. I spent so much time trying to find what I did wrong with my project and why some things would work and others would not, and it turned out my wires were not in the right place.

The main challenge I faced was dealing with the voltage. When I finally had everything wired correctly and all servos working, I tried booting up the arm code, and the arm would start going crazy. I poured over the code and looked at every little line trying to find out what went wrong. Finally, I looked at the manual and it turns out that the arm works with 7-8 volts, and I was using a 9-volt battery to power it. So, I switched batteries, and finally, the arm worked perfectly with the potentiometer joystick, and my first milestone was done. 

# RC Wiring Diagram
![Wiring Diagram](./images/Schematic.jpeg)



# Bill of Materials

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:| 
|Brushless RC Motor|It is the motor for the car|$16.99| <a href= "https://www.amazon.com/FLASH-HOBBY-Brushless-Multicopters-Helicopter/dp/B089YN9WM9/ref=sr_1_4?crid=2N1L4C3VMAL3L&keywords=rc%2Bmotor&qid=1689274087&s=toys-and-games&sprefix=rc%2Bmoto%2Ctoys-and-games%2C163&sr=1-4&th=1"> Link </a>|
| 30A ESC | To Have Speed Control over the Car | $16.99 | <a href= "https://www.amazon.com/RC-Brushless-Electric-Controller-bullet/dp/B071GRSFBD/ref=pd_bxgy_sccl_1/130-2510493-2350145?pd_rd_w=Tpt7i&content-id=amzn1.sym.26a5c67f-1a30-486b-bb90-b523ad38d5a0&pf_rd_p=26a5c67f-1a30-486b-bb90-b523ad38d5a0&pf_rd_r=BWF4MRYYFR352B441YN7&pd_rd_wg=c4Kas&pd_rd_r=55405d14-455a-41be-95ae-b7396496c584&pd_rd_i=B071GRSFBD&psc=1"> Link </a> |
|Cokoino Robotic Arm|It is the Robotic Arm Project|$49.99| <a href= "https://www.amazon.com/LK-COKOINO-Compliment-Engineering-Technology/dp/B081FG1JQ1"> Link </a>|
|3 in 1 IoT/Smart Car| Wheels, Servos, Chassis, and misc. parts| $89.99 | <a href="https://www.amazon.com/SunFounder-Compatible-Tutorials-Including-Controller/dp/B0B778L1DZ"> Link </a> |
| Various 3D Printed Parts | Check Schematics | N/A | N/A |


# Other Resources/Examples
Here Are Some Resources I used to create my Final Project.
-
-
