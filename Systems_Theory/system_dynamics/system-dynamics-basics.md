# Basics of System Dynamics

By now, you must have realized that systems behave to stimuli differently, based on the situation, time, and inherent structure. Systems evolve with time; even though made of inanimate objects, they tend to learn to respond optimally and display dynamic behavior. System Dynamics is a discipline that develops modeling methods for the inherent structure of the system to know more about how it works and make predictions based on hypothetical stimuli. 

Let's take a simple example of how a country's population, or, for that matter, the world population, behaves with time. To put this forward intuitively, we will use a lot of block diagrams and illustrations; I will describe each of them as we go along! Let's get started.

We usually use the so-called 'Stock' and 'Flow' diagrams to analyze how a system behaves with time. You can think of stocks as inventories or storehouses of any product, be it a car, a bicycle, or a living being. Flows can be of 2 types, sources, and sinks. For a storehouse, the source is the inflow of produce from the manufacturing units. The sink is the outflow due to consumer demand, testing, market survey, etc. Let's analyze how a storehouse operates in different scenarios. 

Before that, here are some conventions which we will follow. The storehouse is our system, and we intend to analyze its behavior. It is a 1 stock and 2 flow (inflow and outflow) system. We also have labor, capital, controllers, and other elements to complete the system. 

![Basic 1 Stock and 2 Flow Population Model](https://sohamphanseiitb.github.io/Think-in-Systems/assets/system-dynamics/p1.PNG)

At this point, the clouds lie beyond the system under consideration; let's only consider the population stock and the filling and draining flows in the form of births and deaths, which alter the level of the stock. So, given a constant number of births (say, 100k per year) and deaths (say, 50k per year) (just assume, it's not like its real!) and 1000k to be the initial value of the population (i.e., at time t = 0, or whenever you start **observing** the system) the population stock varies with time as follows:

![Population Trends](https://sohamphanseiitb.github.io/Think-in-Systems/assets/system-dynamics/p2.png)

Now, in general, in complex systems, births and deaths do not remain constant over time but are, in turn, dependent on the stock. We can have directly or inversely dependent flow magnitudes proportional to the stock magnitude. Just as in our population model (to a first approximation), we know the number of births are governed by the number of individuals capable of reproducing, which are directly proportional to the population as are the number of deaths since a larger population means a larger number of deaths. Of course, this simplistic model is not enough to fit real-world data and prove of any practical use; however, it is a great learning tool to envision how large dynamical systems work and interact together.

Till now, the flows in our model were independent of the stock; however, in the real world, this is not the case; how do they then propagate the information and communicate with the stock? Stick around to find out -- the next time I post! 

---
- [Home Page](https://sohamphanseiitb.github.io/Think-in-Systems/index.html)
- [<< Previous Article - What is Systems Engineering?](https://sohamphanseiitb.github.io/Think-in-Systems/Systems_Theory/systems_engg/systems-engineering.html)
- [>> Next Article - Stocks and Flows](https://sohamphanseiitb.github.io/Think-in-Systems/Systems_Theory/system_dynamics/stocks_and_flows.html)
