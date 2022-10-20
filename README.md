# R-Project-Estimating-Pareto-Distribution
Estimating the distribution of a Pareto by simulation of random Paretos and using estimation functions calculated by hand. 

In summary, we simulate 1000 random paretos and plot a histogram of these random samples against their density.
The red line on the histogram is the distribution function of paretos taking values in xvals with parameters 2 and 15.
These parameters are the parameters of our assumed Pareto. 

We then create an estimation distribution function which is the proportion of items seen in the random sample 
Then we pass our xvals into this estimation function and plot the result of this.
We also plot on the same graph the true distribution function with the parameters we know. 

Finally, we plot an estimate of the quantiles to the true quantile function. 

