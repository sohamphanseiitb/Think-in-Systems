# The Systems Zoo - One Stock Systems

Lets take the instance of the amount of money deposited in a bank as a stock.  Lets take theannual rate of expenditure to be a% of the total amount of money.  Let b% be the annual rateof interest earned.  We try to model this simple 1 stock system with the help of preliminarydifferential equations and the models represented above.  Let the initial amount deposited inthe account be c. 

![Principal-Interest-Expenditure System Model - One Stock System](https://sohamphanseiitb.github.io/Think-in-Systems/assets/system-dynamics/interest-model.PNG)

Based on the above model we formulate the governing equation for the same. Let x(t) be the total amount of money in the account at time t (in years, t=0 corresponds to base year)

<script>
MathJax = {tex: {inlineMath: [['$', '$'], ['\\(', '\\)']]}, svg: {fontCache: 'global'}};
</script>
<script type="text/javascript" id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-svg.js">  </script>

$$ x(t) = x(t-1) + x(t-1)\times\frac{b-a}{100}\hspace{10pt} t>0 $$
$$ x(t) = x(0) \hspace{10pt} t=0 $$

We  propagate  our  model  by  calculating  values.   By  considering  different  expenditure  andinterest rates for the same initial amount we can inspect the behaviour of the stock level.

![Stock Level Behaviour in different scenarios](https://sohamphanseiitb.github.io/Think-in-Systems/assets/system-dynamics/interest-model-pythons.PNG)

Based on the figure we can conclude that when the ROI (Rate of Interest) and ROE(Rate of Expenditure) are equal the stock level will be maintained at a constant rate. We explore the stock level behaviour when either of the ROI or ROE are zero.  When we have a zero ROE and a finite ROI, we can see exponentialgrowth in the stock levels, thus we can conclude that in such an event it is the reinforcing loopthat regulates the behaviour of the stock level and causes such exponential growth.  Whereasin the event of zero ROI but finite ROE, we can see that the decline is very slow as comparedto the earlier case, hinting that there is a balancing loop regulating the behaviour.  In the firstcase, more amount creates more interest, which results into more amount – inducing a couplingand eventually exponential nature.  In the second case, less amount means less expenditurewhich results into better retention of the available amount – displaying the balancing nature.

![Balancing and Reinforcing Feedback loops at play](https://sohamphanseiitb.github.io/Think-in-Systems/assets/system-dynamics/interest-model-2.png)

We have used the tools to simulate a system's response in different conditions. Here, being a single stock system, it was easy to calculate and get the results. Systems get complicated when there are multiple stocks, feedbacks and external factors affecting stock level and flows. 

- [Home Page](https://sohamphanseiitb.github.io/Think-in-Systems/index.html)
- [<< Previous Article (Causal Loop Diagram)](https://sohamphanseiitb.github.io/Think-in-Systems/Systems_Theory/system_dynamics/cld.html)
