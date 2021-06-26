# Surf's Up: Analyzing Weather Data And Business Prospects Using SQLAlchemy

## Purpose
The point of this project was to practice using the SQLAlchemy dependency by reflecting and analyzing a database of weather observations to determine the viability of a (fictional) surf shop in Hawaii. The analysis focused on separate queries of temperature data for June and December.

## Results
As the figures below illustrate (and as pop culture has suggested for generations), the temperatures in Hawaii are pretty consistently comfortable, whether it's the beginning of summer or the beginning of winter. In particular, temperatures on the island of Oahu:

- Have similar average highs in June and December, at least during the timespan for which we have data (2010-2017). The average high temperature for June (~75 degrees) is only four degrees higher than the average high temperature in December (~71 degrees). 
- Vary only slightly from those averages. The standard deviation in both months is between 3 and 4 degrees.
- Lack extreme outlier temperatures, with ranges staked mostly to the high 60s and throughout the 70s. Despite having noticeably different minimum temperatures (56 degrees in December versus 64 in June), most would probably consider that a comfortable spread. The max temperatures (83 in December versus 85 in June) are also essentially the same.

![image](https://user-images.githubusercontent.com/1015285/123522987-8d543580-d686-11eb-92e1-636b42c1fdd2.png)
Fig. 1 - June temperature summary

![image](https://user-images.githubusercontent.com/1015285/123523044-d1dfd100-d686-11eb-9a15-f7309cb43eeb.png)
Fig. 2 - December temperature summary

## Summary
This analysis suggests what maybe should have been obvious from the get-go: from a temperature standpoint at least, a business specializing in ice cream and surfing is a viable opportunity on the island of Oahu in Hawaii. More data, of course, could flesh out any further concerns posed by the weather. 

### Further exploration

One possibility would be using the same SQL database to query precipitation in June and December across the entire seven years of data (as opposed to the analysis in the module, which focused on the most recent calendar year of data). 

It would also be prudent to compare temperature summaries in different months. Although June and December signal the start of summer and winter, it's possible there are more extreme temperatures that could pose a threat to the business when those seasons are further along. Analyzing July and January, for instance, or August and February, might provide additional insights. However, it's probably fair to conclude that if you're going to open a business focusing on ice cream and surfing, Oahu is as good a place as any.
