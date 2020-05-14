---
layout: post
author: Andi
title: "Negative Latency - Thoughts and possible impact"
tags: glasbowl opinion edge IT network cloud
---

We live in a world where we have basically two options to solve issues in the technology area. Most "old school" engineers (it's not meant to blame someone, but that is what good old German engineering does best for decades) always go with haptic and mechanical solutions.
We, the IT guys, support them probably with digital twins where we copy the physic into software to further optimize it, simulate situations or create predictions.
I do not want to leave unmentioned that mechanical user interfaces can be really good in critical environments. This goes against the trend a bit, and belongs in a future article ;-).
On the other hand we have companies like Tesla that start from the other direction: Software

Of cause software must be executed somewhere and we need interfaces to interact with it. So we create hardware with mostly focus on haptic and nice touch surfaces. Actual smartphones, evolved to a part of our being and are manufactored with awesome materials and outstanding interaction concepts, are a perfect example for "humanized" hardware.

Actual modern smartphones, PC, laptops, tablets and even cars and smartwatches are powerhouses with unbelievable potential. I do remember times when i had to buy a new PC every year to be able to execute actual software. Those times are basically over, actual Hardware is unbelievable powerful and able to survive multiple itterations of new software trends and concepts. 
On the back-end site we work a lot with modern cloud infrastructure and cost efficient horizontal scalability to provide low latency user experience. These trend is actually pushing even more "brutal" in the direction of moving whole data centers near to the human interface devices (Edge).

I wonder if that is the good old "German engineering" way of thinking. We do that cause our big centralized data centers are basically to far away and simple physics is limting us and our ideas with transport data via copper, fiber or air.
But it seems that there is something awaking that tackle those challenge with a more softwareisch approach. What if we use intelligent prediction algorithm and efficient compression methods to calculate compute intensive portions of our apps in central data centers while having the device only displaying the one best fit result?

There are actually at least two already existing products available that are implemented based on this ideas. The first one makes me as an IT engineer super exited every time i use it. I'm not necessarily a gaming guy, but every time i start my stadia i have to smile. Google is basically hosting the games for me and is only delivering in video signal to my devices. That sound so easy... When you already had the chance to play around with that technology you will recognize no latency between your input and the movement on your screen.
As a technician that must trigger you... A signal from my controller that is connected via BT with a cheap streaming stick send a signal, that signal is transported via my local wireless LAN to my router, transported to my provider, from there somehow through the internet into the next Google stadia data center. The Server there is taking the signal and handed over to the gaming session, the game reacts and google has to update the video stream. And all of that has to be as fast as 60Hz... With a significant bandwidth since the games can be consumed in 4k. How the hell can that work? 

Simple answer, it can't. Instead Googles engineers came up with a more software idea to make it happen. They predict your next interactions within the game and send them over to the device before they actually happen. Logic in the local device has to use the best fitting scene for my next interaction and simply update the screen. That change the game completely down to a simple bandwidth challenge instead of a latency problem.
Don't get me wrong, you better have a sufficient internet connection to really enjoy gaming with statia, but that ideas behind are super exiting and fully packed of potential future usage potential.

Another already existing implementation is puffinOS and the browser applications. Even if i do not recommend to use them cause of the big security and data privacy problems with their concept, the are exited as well. They claim to make use of a so called Avatar technology that allow them to basically run applications in their data centers and only send prerenderd content to end user devices. The advantages of that concept are speed in complex applications with lot of necessary requests to multiple services in their back-end (like and API gateway), network traffic protection in untrusted environments, less battery drain on mobile devices since they do not calculate content, no need for local storage, no installation time for applications,... 
The concept is unfortunately weak but as someone writing that post on a Nexdock with Samsung Dex on a Note10+ is can see the potential of getting rid of big local applications and all their implications.
Aren't reactive web apps doing the same? Yes, they are in general using the same concepts and ideas but on a way smaller scale.

All good? Interesting stuff am i right? Now let us put that into perspective of the hardware versus software aspect with what i'm started this post. Do we think Edge computing is really the best tool we have to answer actual challenges? Or do we use a hammer cause we always use hammers and everything looks like a nail for us?

What about bring back the VDI ideas, CITRIX concepts, reactive web apps, 5G and all the fancy prediction concepts from the game streaming community instead?


