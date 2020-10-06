---
layout: post
title: Interactive Objects Project 1 Process Doc
permalink: /intobjp1/
---

![image](/images/posts/journey1.jpg)

## Design Statement

In this project, our focus was to experiment and understand how to build circuits. We used different methods of building circuits, using conductive fabric/velostat, copper tape, graphite, and fruits. These resulted in a broader understanding of how ciruits worked but what things that could be made out of. Using conductive fabric and velostat produced flexible sensors, that could be used for clothing applications. Using fruits resulted in using them for batteries, if connected in parallel, for an LED. In addition to these experiments, further work was done to understand how the Arduino communicates to P5.

In this particular process document (or exploration), the focus on primarly on flex sensors and how to use conductive fabric/velostat to create something interesting. The experiments that were done previously, provided an understanding how these things worked and gave a confidence boost in using handmade sensors in everyday things. In the end, the project was to learn and it was something we got a lot with. The learning we did will be used in further projects, as well building upon that foundation we created at the beginning of the semester.

-----

## Experimentation, experiementation, and more experimentation

![image](/images/posts/journey1.jpg)

At the beginning of the project, I (along with my group members) were quite lost in regards to how to start or how circuits even worked. We decided to try the fruit experiement that was demoed in class, on a weekend, and see if we could figure that out. Although, we weren't able to get it working (due to us not having specific meterials) - We learned:

* Specific metals are conductive like copper and zinc. Other metals like nickel (we tried a quarter), didn't work too well, even though it had a small amount of copper in it. We tried other metals like brass, alumnum, and steel, these didn't conduct enough current to power the led.
* From a bit of exploring, we learned that it was a bascially a chemical reaction with the citric acid from the fruit along with the metal to conduct electricity. That was pretty neat.
* I tried other fruits like a grapefruit, lemon, lime, and an orange. It was very dependent if the fruit was ripe or have enough juice, in order for it to work.

![image](/images/posts/journey1.jpg)

## Flex sensors and the challenges

After the fruit experiements, I decided to try out making my own flex sensors based on the YouTube tutorials that were posted by Doug. I found it rather interesting to create and use but I saw limited potential in how the flex sensor could be used.

![image](/images/posts/journey1.jpg)

I decided to see if I could use the flex sensor to output a few things like leds or sound. After a few more experiements, I was able to use the flex sensor with a led and also a speaker. The concept here is, when you bend the sensor the led lights up or the speaker will output a tone. Since I didn't use an mp3 shield (foreshadowing here), I was able to use basic tones rather than something like music.

![image](/images/posts/journey1.jpg)

Afterwards, I remembered that I still had the Adafruit Wave Shield from first semester - I was curious if I could make it work with the flex sensor. Initially, it was a bit difficult to get it working due to how I wired it - I had to desoldier (and resolider) a few things due to it being used in a previous project, but eventually I got it working with just the flex sensor and it outputting a wav file.

![image](/images/posts/journey1.jpg)

The next step was seeing if I could output an led as well, this was fairly simple in code and wiring but there was a significant delay when the flex sensor is bent. The sound seems to be played first and then the led will turn on, I think this could possibly be a code fix but I decided to leave it as is while I experiment on other things.

![image](/images/posts/journey1.jpg)

## Even more experiements!

Most of my learning came from looking at my group member's experiments. A few of them were:

Bruno experimenting with graphite and the p5 serial app.

Mike doing a few experiements with copper tape, conductive fabric, wire wrapping, and using the multi-meter.

Emily playing around with the button sketch with the p5 serial app.

I learned quite a bit in how different materials can be used to create circuits and also the possibilities that there are to create wearables. I think it's defintely possible to create interesting things but I feel it's very limited depending on what can be done on your own versus a large manufacturer that has an engineering team. For example, looking a conductive fabric, I feel that you can't do much outside of pressure/flex sensors in the realm of DIY. The P5 serial stuff is really interesting and Bruno did quite a few interesting things but I can see it using it for games or even creating an one handed controller from an Arduino.

## Going back to the flex sensor

I decided to focus on the flex sensor as I was very interested in pushing it further. I had a few ideas in mind, such as using it to create an hat the emits led or something wearable related.

* I had one idea where you use the flex sensor as an button to turn on specific leds on to a hat. The leds would indicate if you can be approached to chat or tell the person to "go away, I want to be alone".

* Another idea was to create a flashlight using a glove. Leds would be sewed on to the fingertips of the glove, using conductive thread and then depending on how you bent your fingers - You can active specific leds.

My eventual idea was to use flex sensors that are sewed into a glove to produce a specific sound when a specific gesture is made. For example, if you make a gun gesture, it would play a bang noise. I felt this idea was doable but wiring all this up and planning would be a bit challenging, regardless, I pushed full steam ahead in seeing if this idea worked.

![image](/images/posts/journey1.jpg)




Poole is the butler for [Jekyll](http://jekyllrb.com), the static site generator. It's designed and developed by [@mdo](https://twitter.com/mdo) to provide a clear and concise foundational setup for any Jekyll site. It does so by furnishing a full vanilla Jekyll install with example layouts, pages, posts, and styles.

This demo site was last updated {{ site.time | date: "%B %d, %Y" }}.

There are currently two themes built on Poole:

* [Hyde](http://hyde.getpoole.com)
* [Lanyon](http://lanyon.getpoole.com)

Learn more and contribute on [GitHub]({{ site.github.repo }}).

## What's included

Poole is a streamlined Jekyll site designed and built as a foundation for building more meaningful themes. Poole, and every theme built on it like this one, includes the following:

* Complete Jekyll setup included (layouts, config, [404]({{ '404.html' | relative_url }}), [RSS feed]({{ 'atom.xml' | relative_url }}), posts, [archive page]({{ 'archive' | relative_url }}), and [example page]({{ 'about' | relative_url }}))
* Mobile friendly design and development
* Easily scalable text and component sizing with `rem` units in the CSS
* Support for a wide gamut of HTML elements
* Related posts (time-based, because Jekyll) below each post
* Syntax highlighting, courtesy Jekyll's built-in support for Rouge

Additional features are available in individual themes.

## Browser support

Poole and its themes are by preference a forward-thinking project. In addition to the latest versions of Chrome, Safari (mobile and desktop), Firefox, and Edge.

## Download

These themes are developed on and hosted with GitHub. Head to the [GitHub repository]({{ site.github.repo }}) for downloads, bug reports, and features requests.

Thanks!
