# Wikipedia_star
Weekend project... see how much different stars in the sky are read on wikipedia.

The data of coordinates and magnitude is from HYG database, while the page views is scraped off wikipedia (technically Wikimedia). The two were matched using Henry Draper Catalogue (HD). see [blog post](https://blog.matteoferla.com/2019/07/wikipedia-datamining.html) for the details of the wikipedia datamining —not much went into this set though.

I did not trust wiki data as it was written by humans for humans. Procyon had incorrect details —fixed in the graphs.

While 19 Lyrae was recently added so the data is messed up.
The Crux constellation also has some oddity —redirect change? Not sure.

Here is animation going from star chart to wiki vs. magnitude.

![wiki vs map](stars2.gif)

This is fun/naff, but not informative. The plotly interactive version can be found on the HTML conversion of the notebook, which can be found [here](http://users.ox.ac.uk/~bioc1451/wikistars.html) —right at the bottom of the page.

## Series

This is part of a series of graphs.

[GitHub repo](https://github.com/matteoferla/Wikipedia_Mars)

Previously I have looked at planets in the solar system:

![Planets wiki](https://github.com/matteoferla/Wikipedia_Mars/blob/master/planets.png)

Which showed that Pluto was more popular than Mars. Which prompt the question of whether places on Mars are more read or sub topics, such as water on Mars, colonisation etc. When these are factored in Mars beats Pluto.

Martian places are not highly read, but still interesting:

![Mars places wiki](https://github.com/matteoferla/Wikipedia_Mars/blob/master/mars.jpg)

Previously, I looked at [planes](https://github.com/matteoferla/Wikipedia_planes), which was based on wiki searches and category scraping, but unreleased to astronomy.

## Labels

named|con|mag|dec|ra|dist|wikiviews
---|---|---|---|---|---|---
Sirius|CMa|-1.44|-16.716116|6.7524809999999995|2.6371|2032.704109589041
Canopus|Car|-0.62|-52.69566|6.399195|94.7867|357.13424657534244
Rigil Kentaurus|Cen|-0.01|-60.833976|14.660765|1.3248|1843.372602739726
Capella|Aur|0.08|45.997991|5.27815|13.1234|246.47671232876712
Procyon|CMi|0.4|5.224993|7.655033|3.5142|224.82191780821918
Betelgeuse|Ori|0.45|7.407063000000001|5.919529|152.6718|1520.6657534246576
Achernar|Eri|0.45|-57.236757|1.628556|42.7533|116.07397260273973
Hadar|Cen|0.61|-60.373039|14.063729|120.1923|78.03013698630137
Acrux|Cru|0.77|-63.099092000000006|12.443311|98.7167|18.695890410958903
Becrux|Cru|1.25|-59.688764|12.795359|85.3971|2.956164383561644
Gacrux|Cru|1.59|-57.113212|12.519428999999999|27.1518|11.76986301369863
Polaris|UMi|1.97|89.26410899999999|2.52975|132.626|1286.8
Del Cru|Cru|2.79|-58.748928|12.252427|105.8201|1.3835616438356164
52Tau Cet|Cet|3.49|-15.937479999999999|1.734479|3.6502|286.1095890410959
Eps Cru|Cru|3.59|-60.401146999999995|12.356031|70.4722|1.16986301369863
18Eps Eri|Eri|3.72|-9.458262|3.5488480000000004|3.2161|203.27397260273972
40Omi2Eri|Eri|4.43|-7.652871|4.254537|4.9845|136.81917808219177
Rho Phe|Phe|5.24|-50.986816|0.8447680000000001|74.239|0.8136986301369863
Zet1Ret|Ret|5.53|-62.575322|3.295903|12.0077|420.63287671232877
Mira|Cet|6.47|-2.977643|2.3224419999999997|91.659|217.17534246575343
Methuselah star|Lib|7.2|-10.933497000000001|15.717529999999998|58.2751|107.74246575342465
CY CMa|CMa|8.08|-25.767548|7.38287|100000.0|749.8301369863013
Cygnus X-1|Cyg|8.84|35.201603999999996|19.972688|595.2381|263.3972602739726
Kapteyn's Star|Pic|8.86|-45.018417|5.1941690000000005|3.9114|65.47123287671234
Kruger 60|Cep|9.59|57.695875|22.466642|4.001|15.56986301369863
Gliese 710|Ser|9.66|-1.938607|18.33079|19.5618|108.91506849315068
Innes's star|Car|11.66|-57.54766899999999|11.267069000000001|12.6727|6.306849315068493





