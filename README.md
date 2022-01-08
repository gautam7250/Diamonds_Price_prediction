# Diamonds_Price_prediction
A new company, Intelligent Diamond Reseller (IDR), wants to get into the business of 
reselling diamonds. They want to innovate in the business, so they will use predictive
modeling to estimate how much the market will pay for diamonds. Of course, to sell
diamonds in the market, first they have to buy them from the producers; this is where 
predictive modeling becomes useful. Let's say people at IDR know ahead of time that they
will be able to sell a specific diamond in the market for USD 5,000. With that information,
they know how much to pay when buying this diamond. If someone tries to sell that
diamond to them for USD 2,750, then that would be a very good deal; likewise, it would be
a bad deal to pay USD 6,000 for such a diamond. So, as you can see, for IDR it would be
very important to be able to predict the price the market will pay for diamonds accurately.
They have been able to get a dataset (this is actually real-world data) containing the prices
and key characteristics of about 54,000 diamonds; here we have the metadata about the
### dataset:
* Number of attributes: 10
> * Feature information: A DataFrame with 53,940 rows and 10 variables:\
> * price: Price in US dollars\
> * carat: Weight of the diamond\
> * cut: Quality of the cut (fair, good, very good, premium, ideal)\
> * color: Diamond color, from J (worst) to D (best)\
> * clarity: A measurement of how clear the diamond is (I1 (worst), SI2, SI1, VS2,\
VS1, VVS2, VVS1, IF (best))\
> * x: Length in mm\
> * y: Width in mm\
> * z: Depth in mm\
> * depth: Total depth percentage = z / mean(x, y) = 2 * z / (x + y)\
> * table: Width of the top of the diamond relative to the widest point
