# Wikipedia_star
Weekend project... see how much different stars in the sky are read on wikipedia.

The data of coordinates and magnitude is from HYG database, while the page views is scraped off wikipedia (technically Wikimedia). The two were matched using Henry Draper Catalogue (HD). see [blog post](https://blog.matteoferla.com/2019/07/wikipedia-datamining.html) for the details of the wikipedia datamining —not much went into this set though.

I did not trust wiki data as it was written by humans for humans. Procyon had incorrect details —fixed in the graphs.

While 19 Lyrae was recently added so the data is messed up.
The Crux constellation also has some oddity —redirect change? Not sure.

Here is animation going from star chart to wiki vs. magnitude.

![wiki vs map](stars2.gif)


## Jupiter notebook

The HTML conversion of the notebook can be found [here](http://users.ox.ac.uk/~bioc1451/wikistars.html).

## Series

This is part of a series of graphs.

[GitHub repo](https://github.com/matteoferla/Wikipedia_Mars)

Previously I have looked at planets in the solar system:

![Planets wiki](https://github.com/matteoferla/Wikipedia_Mars/blob/master/planets.png)

Which showed that Pluto was more popular than Mars. Which prompt the question of whether places on Mars are more read or sub topics, such as water on Mars, colonisation etc. When these are factored in Mars beats Pluto.

Martian places are not highly read, but still interesting:

![Mars places wiki](https://github.com/matteoferla/Wikipedia_Mars/blob/master/mars.jpg)

Previously, I looked at [planes](https://github.com/matteoferla/Wikipedia_planes), which was based on wiki searches and category scraping, but unreleased to astronomy.





