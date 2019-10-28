# Title

Dive into the Heart of Chicago's crime


# Abstract

The iconic city of Chicago (Illinois), is widely known for its crime. Surnamed Chirac because of it's crime rate compared to the war in Irak, also known for Al Capone and it's Chicago outfit during the prohibition, Fred Hampton's assassination by the city's police or the sudden rise of crime in 2015 make Chicago's crime an interesting subject to study.

Through this study of 20 years of crime, we want to bring insights on the crime evolution, geographical distribution, and effects on the city with an unbiased and apolitical approach to give people a fair idea of the safety of the city and its implications.

Also, we think that a good analysis of crime through cities with endemic criminality such as Chicago can be a useful tool for the police (to prevent crime), lawmakers (judge cases with insights from similar events), touristic office (give information about areas to avoid,  when).


# Research questions

- Is the violence evenly spread across the city or are some districts more concerned with violence? We think that some areas might be more subject to violence and crime. 

- Is there an evolution throughout the years of the violence in each neighborhood? Did some areas manage to handle crime better than others?

- Correlate some factors that correspond to the quality of life (green area, quality of education, quality of restaurants, price of real estate) and their respective areas with crimes? We would like to see if areas concerned with violence are similar to areas with a high number of failed food inspections. Indeed, there might be more failed food inspections in poorer districts than richer ones.

- Are violent areas ghettos (no-go zones)? We can speculate that people do not go to violent areas and services (taxis) tend to avoid them as well. Using the taxi courses dataset we could analyze if people go to areas with a high crime rate and if taxis take courses from such areas (we can perform the same analysis with bicycle trips.

- Is there any correlation between the density of fire and police stations and the number of crimes in certain areas of Chicago?

- Are there more towed vehicles is considered less dangerous zones where the average salary might be higher so people do not care about having their vehicles towed? Or on the contrary, it is in the dangerous areas where illegality is more present?

# Dataset

- [Chicago Crimes](https://www.kaggle.com/chicago/chicago-crime):
This dataset records many crimes committed in the past 20 years in Chicago. We have access to the year, time, location, type of crime, district of each crime. We can thus make a geographical analysis to find concerned areas. We can see the evolution using the timestamp. 

- [Food Inspection in Chicaco](https://www.kaggle.com/chicago/chicago-food-inspections):
This dataset records the results of food inspection since 2010 in Chicago. We have access to the name and location of the food institution, the results of the test. We can find areas that tend to fail inspections and see how they compare with the crime rate.  It can tell us if crimes are located in areas with good restaurants (might be richer areas) or bad ones (might be poorer areas).

- [Chicago taxi rides in 2016](https://www.kaggle.com/chicago/chicago-taxi-rides-2016):
This dataset contains taxi rides data such as the location of picking and dropping, time of the course. This would allow us to see which areas of the city are well connected and which areas tend to be excluded. We can then try to correlate the results with the violent areas. However, this analysis can only be possible for the 2016 year.

- [Towed Vehicles](https://data.cityofchicago.org/Transportation/Towed-Vehicles/ygr5-vcbg):
This dataset provides the location of vehicles in Chicago that have been towed which means either illegally parked vehicles, abandoned vehicles, and vehicles used for illegal activities. We can use this dataset to further our zone-oriented crime analysis with previous datasets.

- [Police Stations](https://data.cityofchicago.org/Public-Safety/Police-Stations/z8bn-74gv?fbclid=IwAR2yJeCXKd2toir7M50FkGWQ9MOZ7hrAD5ZMudAbiJE0vgriOIkw_d6y19Q)/[Fire Stations](https://data.cityofchicago.org/Public-Safety/Fire-Stations/28km-gtjn?fbclid=IwAR0SS0NRQiQoBv9fRFvIYgTfbqvL4sTAvKN_bbyXfsPCBeCJsTE_l72R8Vk):
These datasets provide locations of police stations and fire stations in Chicago. We can use it to find out different location densities of them and try to group them and see if we get the same results as with the crime locations.

- [Chicago public dataset](https://data.cityofchicago.org/):
This website contains publicly available datasets for the city of Chicago. It could be a great way to complete our analysis. We can find data regarding different aspects of the city such as education, real estate, environment, cleanness... Finding how violent zones differ from each other regarding other aspects might lead us to discover factors that reduce violence.


# A list of internal milestones up until project milestone 2

### Week 1 (28/10/2019 - 03/11/2019)

- Load all datasets we will use and extract meaningful data
- Setup the git
- Split the work

### Week 2 (04/11/2019 - 10/11/2019)

- Clean the datasets (remove outliers, fill missing values)
- Compute interesting derivatives of the datasets
- Extract as many information as possible from the different datasets
- Visualize the data: Draw chart and plot to get more insight into the data


### Week 3 (11/11/2019 - 17/11/2019)

- Detect correlations between features, trends.
- Extract meaningful information for our analysis that answers our questions
- Reorder the results in a clear manner

### Week 4 (18/11/2019 - 24/11/2019)

Prepare the Milestone 2 : 
- Merge our work
- Clean the code
- Check for errors
- Comment the code
- Plan the next steps

### Milestone 2: 25/11/2019


# Questions for TAs

- Should we restrict ourselves to the crime dataset or is it a good idea to explore other Chicago related datasets (food inspections, taxis courses) to find correlations?



