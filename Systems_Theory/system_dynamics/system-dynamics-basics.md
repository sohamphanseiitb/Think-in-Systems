# Basics of System Dynamics

By now, you must have realized that systems respond to stimuli differently based on the situation, time, and inherent structure. Systems evolve with time; even if they are made of inanimate objects, they tend to learn to respond optimally and display dynamic behavior. System Dynamics is a discipline that develops modeling methods for the inherent structure of the system to know more about how it works and make predictions based on hypothetical stimuli. 

Let's take a simple example of how a country's population, or, for that matter, the world population, behaves with time. To put this forward intuitively, we will use a lot of block diagrams and illustrations; I will describe each of them as we go along! Let's get started.

We usually use the so-called **Stock** and **Flow** diagrams to analyze how a system behaves with time. 

## What are Stocks, then?
You can think of stocks as inventories or storehouses of any product, be it a car, a bicycle, or a living being. If you are analyzing a system and taking a snapshot by freezing variables in time, stocks are the values of that variable. Consider a _bank account_; here, the account balance is a stock, and inflows and outflows are income and expenditure, respectively. Stocks needn't be of material quantities; abstract variables like happiness and emotions can also be represented in stocks. Stocks, in a more technical lingo, can be described as the history of changing flows within the system.

## What are Flows?
Flows are measured over an interval of time and are responsible for changing the stock values. Flows can be of 2 types, sources and sinks. For a storehouse, the source is the inflow of produce from the manufacturing units. The outflow is due to consumer demand, testing, market survey, etc. For instance, if the number of cars in a parking lot is in stock, the number of cars entering the lot every hour is the inflow, and the cars leaving each hour is the outflow. 

# The Population Model

![Basic Stock-Flow Population Model](https://sohamphanseiitb.github.io/Think-in-Systems/assets/system-dynamics/blog_population_model.jpg)

Consider this simple stock and flow model, representing a population of certain species - it can be humans, plants, or any other. Note that the model is very simplistic in nature and only serves at best to produce qualitative results. The **clouds** in the diagram lie beyond the system under consideration - or they can be considered as other stocks - however, we don't consider their dynamics - hence you might even want to consider them as infinite stocks. 

The model has 2 flows; the '**Birth Rate**' is the inflow, whereas the '**Death Rate**' is the outflow. They both increase or decrease the stock value and influence the dynamics. There are two more variables called '_Birth Rate constant_' and '_Death Rate constant_.' Note that I call them variables and not stocks. There are 2 reasons behind this premise:

1. The variables represent constant values within the model
2. They are deemed to be constant for this model since we are not interested to examine their dynamics because either that is out of scope or they don't influence the model that much to be considered relevant.

This can be better understood using the concept of Modeling Depth you are targeting to achieve within your model. We will talk about system modeling depth in detail later on.

; let's only consider the population stock and the filling and draining flows in the form of births and deaths, which alter the level of the stock. So, given a constant number of births (say, 100k per year) and deaths (say, 50k per year) (just assume it's not like it's real!) and 1000k to be the initial value of the population (i.e., at time t = 0, or whenever you start **observing** the system) the population stock varies with time as follows:

![Population Trends](https://sohamphanseiitb.github.io/Think-in-Systems/assets/system-dynamics/p2.png)

Now, in general, in complex systems, births, and deaths do not remain constant over time but are, in turn, dependent on the stock. We can have directly or inversely dependent flow magnitudes proportional to the stock magnitude. Just as in our population model (to a first approximation), we know the number of births is governed by the number of individuals capable of reproducing, which are directly proportional to the population, as is the number of deaths since a larger population means a more significant number of deaths. Of course, this simplistic model is not enough to fit real-world data and prove any practical use; however, it is a great learning tool to envision how large dynamical systems work and interact together.

Till now, the flows in our model were independent of the stock; however, in the real world, this is not the case; how do they then propagate the information and communicate with the stock? Stick around to find out -- the next time I post! 

---
- [Home Page](https://sohamphanseiitb.github.io/Think-in-Systems/index.html)
- [<< Previous Article - What is Systems Engineering?](https://sohamphanseiitb.github.io/Think-in-Systems/Systems_Theory/systems_engg/systems-engineering.html)
- [>> Next Article - Stocks and Flows](https://sohamphanseiitb.github.io/Think-in-Systems/Systems_Theory/system_dynamics/stocks_and_flows.html)
