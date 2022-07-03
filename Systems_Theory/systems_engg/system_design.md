# Systems Engineering is great, but how do they do it?

> ``Systems Engineering - is an art of creating and managing complex designs."

Okay, so that's basically something I made up myself, but yeah, y'all know people don't value what one says, until its quoted in double quotes, which kinda makes people feel its special. Enough of it, back to the question. 

Valid question, if you expect a short but sweet answer, then it's basically this: standardized procedures combined with lots of experience. A longer but detailed answer? Well, keep reading. 

So there are a lot of standardized procedures and models which come in handy to design, conceptualize, deploy and retire real world systems. One of the most common yet powerful methods is called the **V-model** approach. It might sound daunting, but believe me, its simple and quite intuitive. Check out the snippet below, it details the procedures carried out in a particular sequence, which resembles the letter **V.**

The left arm signifies the problem breakdown procedure - defining the problem statement, enlisting requirements, expanding the design space and converging onto a single solution along with the high level design and architecture. The base signifies the design process - designing components, parts, sub-assemblies, assemblies and then eventually the whole system. The right arm tests and integrates the whole system from the parts. If you watch carefully, the **V** is divided into two parts - the upper section consider the demand side parameters while the lower section focusses on the designer's side. 

The process starts with defining the problem at hand - say, for instance, implementing a national railway transportation system, or constructing a dam for irrigation purposes, or as simple as desiging a lawnmover for farming and gardening. Then, you need to address the problem - in the sense what all aspects of a problem will your system be addressing. Say, the railways will only cater to goods and cargo ans not for passengers, or the lawnmover cannot be used on mountanious terrain. You might find them too trivial - but believe me, even the tiniest details can affect the design significantly. 

So, here's the deal. You have zeroed in onto a particular problem you want to address - say, implementing some system to transport goods and passengers from one point to another - let't not care about how are you gonna do it, we will come to it at a later part. Now, start thinking about the peripherals - What about the finances? Who is gonna provide the funds and how much? What is the timeframe for the project completion? Where do you intend to deploy and use the system? Terrain? Weather? Whether you will use existing public infrastructure?

These are some of the most important questions a person designing a transportation system might ponder upon, there are obviously many more, and they will be different in your case. They set a nice backdrop, a portfolio and foundation on top of which you will base and design the system. Now comes the next important question - which design should you pick? In our case, cars, ships, airplanes, trains, trams (hyperloops? ummm, maybe not now :P) can all transport goods as well as passengers. So, which one do you pick? Here, the questions which you asked before starting the design come in very handy, say, your place has an intricate and widespread network or rivers and tributaries - water channels basically, then the most obviuos way would be constructing a system of water vessels, docks and on/offloading service centres. So, its the parameters - available funds, geography actually decide what kind of system should be deployed. 

Formally, this is named - **concept selection**, and is executed with a variety of tools - called as the **Pugh Matrix** or the **concept selection matrix** (if you find these words complicated, you might as well just call them - **Decision Matrices**, tools which help you compare pros and cons of the candidate solutions and help you make decisions. 

Let me show you a quick example - suppose you want to deploy an autonomous air surveillance systems on the international borders - to monitor illegal tresspassing activities, and you have decided it to be based on Unmanned Aerial Vehicles (commonly known as **drones**). There are many kinds of drones - helis, multi-copters, fixed wings, tilt rotors which ones should you use? Here's how a decision matrix can help you do that (courtesy of me and my colleagues (and dear friends): Neilabh Banzal, Karan Jagdale and Mohit Dhaka from IIT Bombay):

![Decision Matrix](https://sohamphanseiitb.github.io/Think-in-Systems/assets/system_engg/decision%20matrix.png)

All in all the process is simple, its just that first you expand your design/solution space - i.e think about all the different solutions which you can implement to solve the problem/satisfy the purpose and then converge onto a single solution - which is the most optimal.

The topic also sees light in the modern management - the theory of decision making, or **TRIZ** - theory of inventive problem solving. These are pretty advanced topics and you might want to have a look at them, you will find good resources on the internet. If you ask me, currently I will be focusing on the fundamentals, maybe in time I might drop an article or two about it!

Hope that the concept was clear, its been long, let's take a break here, we will talk about the details of system design - the system architecture, the design aspects and production.

Stay tuned till then!

---

- [Previous Article (System Hierarchy)](https://sohamphanseiitb.github.io/Think-in-Systems/Systems_Theory/systems_engg/hierarchy.html)
- [Home Page](https://sohamphanseiitb.github.io/Think-in-Systems/index.html)
