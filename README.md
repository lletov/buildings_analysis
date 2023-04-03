## **Description**
Trends and buildings construction dynamic of Moscow, St. Petersburg and Kazan sities analysis from 1600 till 2021 years.
## **Steps**
![pipeline](https://github.com/lletov/buildings_analysis/blob/main/pictures/pipeline.png)

1. **Data parsing**\
The following values were taken for every city building from the sourse: address, year of building's construction, flats number, enterances number, height of building in floors, overall building living square, coordinates of building i. e. latitude and longitude. Theese data were compiled in csv file. Samples of csv files are in *data* folder of this repositoty.
2. **Statistic analysis**\
Visualization of trends and buildings construction dynamic, based on the parsed data, some new columns will be added in CSV and save after. Some pictures are in *pictures* folder, all picures will be added soon.
3. **Geo analysis**\
Based on the parsed data, heatmaps by year of construction and by buildings height were created for every city. The html versions of them are in *heatmaps* folder of this repository. Folium library were used to heatmap creating.
4. **Summary statistic**\
Summary statistic graphs were created to show mutual dependences of trends and features between cities under consideration. Final graphs are in *summary_statistics.ipynb* file.
\
\
CSV file structure after data parsing:

|- | Address | Year  | Flats | Entrance | Height | Square | Latitude | Longitude | city |
|--|---------|-------|-------|----------|--------|--------|----------|-----------|------|
|2 | ул. подольская, 7 литер а|1902| 10 | 2 | 5 | 880.60 | 59.917015 | 30.322821 | spb |
|11| ул. волгоградская, 9|1963| 80 | 4 | 5 | 3668.70 | 55.829052 | 49.086157 |kazan |
|38| ул. декабристов, 8 корпус 1	|1984| 237 | 5 | 12 | 13584.00 | 55.864460 | 37.599094 |moscow |


## **Summary** 📉
Different statistic graphs for every city were received, summary mutual dependences graphs were received as well. They can be used to look after tendences and buildings construction dynamic, compare them with historical periods to predict the future tendences.

## **Progress**
- [x] few cities
- [x] base analysis
- [ ] add more cities
- [ ] add more dependences

## **Date of parsing**

|-                | Moscow  | St. Petersburg  | Kazan   |
|-----------------|---------|----------------|---------|
|Date of parsing  | 12.2023 | 02.2023        | 02.2023 |
