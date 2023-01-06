
## **Description**
Simple analysis of Moscow city buildings, Russia. Period is from 1600 to 2022 years (not all buildings of 2022 were in dataset, it influenced on 2022 numbers on graphics)
## **Analysis steps:**
1. Making list of all buildings URL addresses
2. Getting valid data from every URL:
  - address
  - year of build
  - flats amount
  - entrances amount
  - height (floors amount)
  - total living square 
  - latitude
  - longitude 
3. Visualizing of dependences

## **Summary** 📉
Through 31429 building URLs were 99,98% with valid data (only valid buildings were used for step 3). The most common height of buildings is 5 floors, more than twice amount from second 9 floors. The fastest building speed was in 1858-1973 years. The largest number of new buildings was in 1960. The flat square has been decreasing by little the last 10 years. There are tendencies of increasing building height, flats by entrance floor amount, flats per building amount in the last few years. The heatmap of different building height amounts by street was also included. There are 2195 streets at all, and the most buildings are on Volgogradskiy prospect. More detailed and other interesting graphics - in file.\
\
\
[Source](https://dom.mingkh.ru) of data 
\
*Programming language:* Python.\
*Libraries were used:* requests, BeautifulSoup, pandas, numpy, re, time, sys, matplotlib, seaborn.



