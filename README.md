# Aviation Accident Analysis
Enclosed is my data analysis for the aviation data. Our client is intereted in aircrafts from 1983 onwards that are professionally made.

For starters, here are my recommendations for large and small aircrafts:
Small:
Beech 19, Bell 47D-1, Cessna 180C, Diamond Aircraft Ind Inc DA 20 C1, Grumman G164B, and the Piper PA-18A 150 models

The data anylsis on lowest fatal/serious injury also pointed to Cessna as being a very safe make. I would point my recommendation there.

Large:
I would stick with Boeing: Boeing 727-223, Boeing 737-232  and Boeing 757
Based on this: Boeing and Mcdonnell Douglas are the makes I would recommend!


The main takeaway from this  analysis is that smaller aircrafts have a higher injury rate and a higher destruction rate which, unsurprisingly,
indicates that they are safer and better bets for survivabiliry. Let's look at the first 2 bar charts that we made (in the analysis file). Even the lowest (serious/fatal)injury rate for small aircrafts was above 0% while we had a number of large aircrafts that had 0% serious/fatal injur rates. 

A few statistic stick out. Firstly, let's just look at the counts themselves! Only 351 of the accidents for large aircrafts had serious/fatal injuries vs 1,920! Now, let's take a look at the two means: for fatal/serious injury% the mean is only 1.72%, again implying the rarity of a serious/fatal accident. On the otherside (with small aircrafts),the mean is 15.33%! That implies that over 14% of accidents result in fatal/serious injury. I will note tha the standard deviation is quite high, but that appears to be because it seems if there is a fatal accident, most often all passengers are injured (ie we have a wide range of outcomes meaning a lot of 0s and 100%). Reviewing this data the biggest takeaway is that large planes are much safer and small planes should be avoided (if at all possible).

There is however a very interesting point! As noted above, data shows that small aircrafts are much more dangerous, however, there are 6 models that (with at least 10 data points) have not produced any serious or fatal injuries. That does not mean that flying a small aircraft is safer, but if I was to recommend small crafts, I would suggest the Beech 19, Bell 47D-1, Cessna 180C, Diamond Aircraft Ind Inc DA 20 C1, Grumman G164B, and the Piper PA-18A 150 models.The large aircrafts are again showing signs of being much safer. We are talking miniscule percentages. Again, my suggestion would be to avoid small planes if possible and only fly on larger crafts.

#Let's briefly talk about the weather condition section. I wanted to bring this particular variable up because in this case we have a bunch of unknown values. So this brings up the question, even though we have 
#unknown values, can we make an intelligent interpretation of the data. I would aruge that we can. Firstly, let's look at what these two categories (outside of the unkown) are: IMC and VMC. IMC stands for "Instrument Meteorological Condition". What this means is that the conditions are severe enough that the pilot cannot safely navigate with their sight, but must rely on instruments for navigation. VMC stands for "Visual Meteorological Conditions" which means that pilots are able to navigate by sight. VMC conditions allow for sufficient visibility to see and avoid other aircrafts and terrain while IMC conditions (such as severe clouds) do not allow for that visibility. If we look at the data (simply IMC and VMC), we can see that the rate at which accidents happened in "bad" weather (IMC) conditions was much higher than that of "good" weather (VMC). I think we can safely assume that flying in IMC conditions leads to more severe accidents.

The data shows that having 1 or 2 engines has a higher rate of severe injury to that of 3 or more. If we think about this logically, the more engines that an aircraft has, the stronger capabilities are in the case of failure. However, we must also be aware of other potentail factors such as pilot experience or the level of maintenance on the aircraft to be able to draw an exact correlation. However, I think that we can assume that having more engines as opposed to less does increase safety to a degree. In order to fully analyze this we would need more data points. I would not strictly make a reccomendation based on this datapoint. In general flight safety is not a black and white thing. There are many factors that could paly a role in why or why not a an aircraft has a severe accident.