---
layout: post
title: Interactive Objects and Environments: Project 1 Process
permalink: /intobjp1/
---

<br>

![image](/images/21.jpg)

<br>

## Group Members

* Bruno Akune
* Emily Betts
* Michael Westlake

<br>

-----

## Design Statement

In this project, our focus was to experiment and understand how to build circuits. We used different methods of building circuits, using conductive fabric/velostat, copper tape, graphite, and fruits. These resulted in a broader understanding of how circuits worked but what things that could be made from. Using conductive fabric and velostat produced flexible sensors, that could be used for clothing applications. Using fruits resulted in using them for batteries, if connected in parallel, for an LED. In addition to these experiments, further work was done to understand how the Arduino communicates to P5.

In this process document (or exploration), the focus on primarily on flex sensors and how to use conductive fabric/velostat to create something interesting. The experiments that were done previously, provided an understanding of how these things worked and gave a confidence boost in using handmade sensors in everyday things. In the end, the project was to learn, and it was something we got a lot with. The learning we did will be used in further projects, as well as building upon that foundation we created at the beginning of the semester.

<br>

-----

## Experimentation, experimentation, and more experimentation

<br>

![image](/images/1.jpg)

<br>

At the beginning of the project, I (along with my group members) were lost on how to start. We decided to try the fruit experiment that was demoed in class, on a weekend, and see if we could figure that out. Although, we couldn’t get it working (due to us not having specific materials) - We learned:

* Specific metals are conductive like copper and zinc. Other metals like nickel (we tried a quarter), didn't work too well, even though it had a small amount of copper in it. We tried other metals like brass, aluminum, and steel, these didn't conduct enough current to power the led.
* From a bit of exploring, we learned that it was a chemical reaction with the citric acid from the fruit along with the metal to conduct electricity. That was neat.
* I tried other fruits like grapefruit, lemon, lime, and an orange. It was very dependent if the fruit was ripe or have enough juice, for it to work.

<br>

![image](/images/2.jpg)

<br>

-----

## Flex sensors and the challenges

After the fruit experiments, I decided to try out making my flex sensors based on the YouTube tutorials that were posted by Doug. I found it rather interesting to create and use but I saw limited potential in how the flex sensor could be used.

<br>

![image](/images/6.jpg)

<br>

I decided to see if I could use the flex sensor to output a few things like LEDs or sound. After a few more experiments, I was able to use the flex sensor with a led and a speaker. The concept here is, when you bend the sensor the led lights up or the speaker will output a tone. Since I didn't use an mp3 shield (foreshadowing here), I was able to use basic tones rather than something like music.

<br>

<iframe width="560" height="315" src="https://www.youtube.com/embed/aWp9E93Of5M" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<br>

Afterward, I remembered that I still had the Adafruit Wave Shield from the first semester - I was curious if I could make it work with the flex sensor. Initially, it was a bit difficult to get it working due to how I wired it - I had to de-soldier (and re-solider) a few things due to it being used in a previous project, but eventually, I got it working with just the flex sensor and it outputting a wav file.

<br>

<iframe width="560" height="315" src="https://www.youtube.com/embed/rQ10yC5-6K8" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<br>

The next step was seeing if I could output an led as well, this was fairly simple in code and wiring but there was a significant delay when the flex sensor is bent. The sound seems to be played first and then the led will turn on, I think this could be a code fix but I decided to leave it as is while I experiment on other things.

<br>

<iframe width="560" height="315" src="https://www.youtube.com/embed/7ypI4DzrfJw" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<br>

-----

## Even more experiments!

Most of my learning came from looking at my group member's experiments. A few of them were:

Bruno experimenting with graphite and the p5 serial app.

<br>

<iframe width="560" height="315" src="https://www.youtube.com/embed/El28MCZSujE" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<br>

![image](/images/7.png)

<br>

![image](/images/8.png)

<br>

Mike doing a few experiments with copper tape, conductive fabric, wire wrapping, and using the multi-meter.

<br>

![image](/images/9.jpg)

<br>

![image](/images/10.jpg)

<br>

![image](/images/11.jpg)

<br>

![image](/images/16.jpg)

<br>

Emily playing around with the button sketch with the p5 serial app: She expermented with using the buttons to manipulate the circles, making them in different sizes.

<br>

(She didn't provide any screenshots or pictures)

<br>

I learned quite a bit about how different materials can be used to create circuits and the possibilities that there are to create wearables. I think it's possible to create interesting things, but I feel it's very limited depending on what can be done on your own versus a large manufacturer that has an engineering team. For example, looking at a conductive fabric, I feel that you can't do much outside of pressure/flex sensors in the realm of DIY. The P5 serial stuff is interesting and Bruno did quite a few interesting things, but I can see it using it for games or even creating a one-handed controller from an Arduino.

<br>

-----

## Going back to the flex sensor

I decided to focus on the flex sensor as I was very interested in pushing it further. I had a few ideas in mind, such as using it to create a hat the emits led or something wearable related.

* I had one idea where you use the flex sensor as a button to turn on specific LEDs onto a hat. The LEDs would indicate if you can be approached to chat or tell the person to "go away, I want to be alone".

* Another idea was to create a flashlight using a glove. LEDs would be sewed onto the fingertips of the glove, using conductive thread, and then depending on how you bent your fingers - You can active specific LEDs.

My eventual idea was to use flex sensors that are sewed into a glove to produce a specific sound when a specific gesture is made. For example, if you make a gun gesture, it would play a sound. I felt this idea was doable but wiring all this up and planning would be a bit challenging, regardless, I pushed full steam ahead in seeing if this idea worked.

My experiments and tinkering showed that it can be done but the flex sensors proved to be very unreliable. One challenge was that the flex sensors that I created for each finger varied regarding its output in the serial monitor. I think because I was using packaging tape to bind everything together, so it was stiff. The variance between each sensor was different because since it was hand made, it wasn't consistent in how I cut the strips of fabric.

<br>

<iframe width="560" height="315" src="https://www.youtube.com/embed/sG61J8xhMNw" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<br>

There was still lots to do at this point:

* Finish creating the rest of the sensors for each finger
* Sewing on the sensors onto the glove
* Testing and building the circuit
* Debugging and figuring out the sensor values for each finger
* Mapping each finger to a specific value so it triggers the sound when activated

I tested out with two sensors at first and it seemed to work. I used if statements and it triggered the sound when it hit a certain point. For example, for the index finger, when it was straight it was at a value of 350 then when bent to a 90-degree angle, it would hit around 700-800. By using if statements and the && operator, when two flex sensors are bent at 90, it would trigger a different sound.

<br>

<iframe width="560" height="315" src="https://www.youtube.com/embed/NMkPzGQyIZY" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<br>

Although, the final product was as straightforward as I anticipated... With five fingers, it was difficult to map as it was very sensitive when it was worn. The slightest movement would trigger something so after playing around, I triggered the sound with specific fingers on specific actions: For example, a gun gesture would have the index straight and the thumb vertically, while the other three fingers are bent towards the palm. By just enabling the index finger to be the trigger, this made it easier to use other fingers as a trigger for other noises.

<br>

![image](/images/15.jpg)

<br>

It wasn't an elegant solution, but it worked regardless of the final product:

<br>

<iframe width="560" height="315" src="https://www.youtube.com/embed/SYoiBo7qgPc" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<br>

The final circuit diagram from Fritzing:

<br>

![image](/images/20.jpg)
(Do note that the Adafruit Wave Shield is suppose to be on top, I couldn't find an image in Fritzing)

<br>

-----

## The takeaways

I learned quite a bit about wearables and from my group's experiments in building circuits with different things and understanding how p5 serial works. Even though it's a bit basic I'm rather excited to see what is next with the projects and how I can incorporate what I've learned in this project into the next one.
