#Lab 9 writeup

The first step this lab was getting a working data set, after a little bit of finagaling with the various data types
the titanic data type was finally in rstudio

![Rstudio with titanic data](https://github.com/pullao/CSCI2961/blob/master/Lab9/Screenshots/2015-11-06.png)




Next up was messing around with the rules a bit. I found that decreasing the minimum support or confidence resulted in a lot
more rules being generated, while doing the opposite removed rules. Increasing lift made it so rules involving smaller groups
were not represented. In the end however, I managed to get a good set of rules with the superflous ones weeded out

![Rules created, superfluous gone](https://github.com/pullao/CSCI2961/blob/master/Lab9/Screenshots/2015-11-06%20(1).png)


From here, I graphed this ruleset with a number of different graph types

Scatter Plot:
![Scatter Plot](https://github.com/pullao/CSCI2961/blob/master/Lab9/Screenshots/2015-11-06%20(4).png)

Grouped:
![Grouped](https://github.com/pullao/CSCI2961/blob/master/Lab9/Screenshots/2015-11-06%20(3).png)

And a couple of flavors of graph:
![Graph 1](https://github.com/pullao/CSCI2961/blob/master/Lab9/Screenshots/2015-11-06%20(2).png)
![Graph 2](https://github.com/pullao/CSCI2961/blob/master/Lab9/Screenshots/2015-11-06%20(5).png)


