# Basics of System Dynamics

You must have by now realized that systems behave to stimuli, differently, based on the situation, time and on their inherent structure. Systems evolve with time, even though made of inanimate objects, they tend to learn to respond in the most optimal way and display dynamic and changing behavior. System Dynamics is a branch of systems theory which outlines the methods with which we can model the inherent structure of the system, to know more about how it works and make predictions based on hypothetical stimuli. 

Let's us take a simple example of how a country's population, or for that matter the world population behaves with time. To put this forward in an intuitive way, let me make use of a lot of block diagrams and illustrations, I will describe each of them as we go along! Lets get started.

To analyse how a system behaves with time, we usually use the so-called 'Stock' and 'Flow' diagrams. You can think of stocks as inventories or storehouses of any product, be it a car, a bicycle, or a living being. Flows can be of 2 types, sources and sinks. For a storehouse, source is the inflow of produce from the manufacturing units and sink is the outflow due to consumer demand, testing, market survey, etc. Let's analyse how a storehouse operates in different scenarios. 

Before that, here are some conventions which we will follow. The storehouse is our system and we intend to analyse its behavior. It is a 1 stock and 2 flow (inflow and outflow) system. Other than that, we have labor, capital, controllers and other elements to complete the system. 

![Basic 1 Stock and 2 Flow Population Model](https://sohamphanseiitb.github.io/Think-in-Systems/assets/system-dynamics/p1.PNG)

The clouds are what lie beyond the system under consideration, at this point let us only consider the population stock and the filling and draining flows in the form of births and deaths, which alter the level of the stock. So, given a constant number of births of 100k per year and constant number of deaths of 50k (just assume, its not like its real!) and 1000k to be the initial value of the population (i.e at time t = 0, or whenever you start **observing** the system) the population stock varies with time as follows:

![Population Trends](https://sohamphanseiitb.github.io/Think-in-Systems/assets/system-dynamics/p2.png)

Now, in general in complex systems, births and deaths do not remain constant over time but are in turn dependent on the stock. We can have directly or inversely dependent flow magnitudes proportional to the stock magnitude of a function of the stock magnitude. Just as in our population model (to a first approximation), we know the number of births are governed by the number of individuals capable to reproduce, which are directly proportional to the population as are the number of deaths, since a larger population means a larger number of deaths. Of course, this simplistic model is not enough to fit real world data and of any practical use, however it is a great learning tool, to envision how large dynamical systems work, interact together.

Till now, the flows in our model were independent of the stock, however in the real world, this is not the case, how do they then propagate the information and communicate with the stock? Stick around to find out -- the next time I post! 

---
> [Home Page](https://sohamphanseiitb.github.io/Think-in-Systems/index.html)

> [<< Previous Article - What is Systems Engineering?](https://sohamphanseiitb.github.io/Think-in-Systems/Systems_Theory/systems-engineering.html)
