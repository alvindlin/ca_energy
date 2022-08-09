# Energy in California

For the Capstone Project for the "Data Visualization with Tableau" Specialization course on Coursera, this study was performed to create a visual presentation of a topic of my choice. As a California native who is passionate about the environment and has an interest in becoming an energy analyst, I decided to do a study on California's Energy and Consumption. The final interactive dashboard can be found [here](https://public.tableau.com/shared/43SJJRK5Y?:display_count=n&:origin=viz_share_link). Snippets of the dashboard is presented below. 

## Project Overview

California produces the most renewable energy in the United States, making it a national leader in the fight to climate change and converting to cleaner energy. With several legislation passed in the last 20 years to push California into renewable energy production. The objective of this project are as follows:
1. Find trends in the data by fuel type and consumption
2. Was the state successful in meeting the Global Warming Solutions Act of 2006 which required California to meet 33% electricity consumption to be generated by renewable resources? 

## Data and Challenges

Data was pulled from the California Energy Comission. For the total in-state electricity generation, I pulled it from [here](https://www.energy.ca.gov/data-reports/energy-almanac/california-electricity-data/california-electrical-energy-generation). For the electricity consumption data, I pulled it from [here](http://www.ecdms.energy.ca.gov/). The data was from a trusted source, as it was officially published from the California Energy Commission Government website. 

The values, dates, and names were all complete and clean. The main problem with the electricity generation data was that the tables were all on one excel sheet. I had to manually split the tables into multiple sheets prior to working on them in Tableau. In addition to that, I transpoed the entire sheet so that the years were in the first column. This way it can be used as a dimension in Tableau. 

Raw Data

![raw data](https://user-images.githubusercontent.com/107506192/183778693-31514844-d3cb-47ae-a007-bd56d628a132.png)

Transposed and Cleaned Data

![Screen Shot 2022-08-09 at 4 27 37 PM](https://user-images.githubusercontent.com/107506192/183778847-fc007568-c603-4c0a-ba6e-4c5c78baac3b.png)

## Results

### 1. Renewable Energy vs Non-Renewable Energy

<img width="446" alt="Renewable energy" src="https://user-images.githubusercontent.com/107506192/183779672-5cbfdae1-bcd4-45ac-bf48-b04d551e8527.png">

Renewable energy acconted for about 15% of total in-state energy production in 2006 when the act was passed. California was successful as it reached 33% renewable energy production in 2020. 

<img width="428" alt="percent renewable" src="https://user-images.githubusercontent.com/107506192/183779755-1bccd9ff-610d-4782-abf9-8eeb4df2d99a.png"> <img width="452" alt="total energy" src="https://user-images.githubusercontent.com/107506192/183779706-059d2698-e276-4ab0-9e6e-992c048ee8dd.png">

### 2. Total In-State Electricity Generation

Biggest increase in total generation was about 8% from 2005 to 2006. Biggest increase in Renewable Energy production occured from 2013 to 2014.

<img width="721" alt="total system electricity generation" src="https://user-images.githubusercontent.com/107506192/183779963-7101ae29-1e4a-4c2d-94cc-c573961483f8.png">

Overall, the largest contributors to Non-Renewable energy remain to be Natural Gas, Nuclear, and Large Hydro. The largest contributors to Renewable Energy in the state are Geothermal, Wind, and Solar PV. Of the Renewable Energy sources, Wind and Solar PV showed the largest growth in 2010 and 2011 and are continuing to grow. Visit the dashboard to interact with the data exploration section shown below [here](https://public.tableau.com/shared/43SJJRK5Y?:display_count=n&:origin=viz_share_link).

<img width="717" alt="bar graph" src="https://user-images.githubusercontent.com/107506192/183779982-5ba7883e-0088-46b3-bbc8-16872bc81285.png">

### 3. Electricity Consumption 

Commercial and Residential makes up over 65% of the total electricity consumption. 

<img width="522" alt="entity" src="https://user-images.githubusercontent.com/107506192/183780479-d442a476-704d-4dd6-88fa-d814177cbce7.png">

Southern California Edison and Pacific Gas and Electric makes up over 70% of electricity consumption.

<img width="533" alt="planning area" src="https://user-images.githubusercontent.com/107506192/183780502-c33011f6-41ec-445b-94bd-1f52b7686149.png">



