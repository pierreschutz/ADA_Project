# Dive into the Heart of Chicago's crime

Please find our data story here : https://pierreschutz.github.io/dada-story/

1. [Abstract](#abstract)
2. [Research questions](#research-questions)
3. [Datasets](#datasets)
4. [Internal milestones](#internal-milestones)
5. [Contributions](#contributions)


# Abstract

The iconic city of Chicago (Illinois), is widely known for its crime. Surnamed Chirac because of it's crime rate compared to the war in Irak, also known for Al Capone and it's Chicago outfit during the prohibition, Fred Hampton's assassination by the city's police or the sudden rise of crime in 2015 make Chicago's crime an interesting subject to study.

Through this study of 20 years of crime, we want to bring insights on the crime evolution, geographical distribution, and effects on the city with an unbiased and apolitical approach to give people a fair idea of the safety of the city and its implications.

Also, we think that a good analysis of crime through cities with endemic criminality such as Chicago can be a useful tool for the police (to prevent crime), lawmakers (judge cases with insights from similar events), touristic office (give information about areas to avoid,  when).


# Research Questions

- Is the violence evenly spread across the city or are some districts more concerned with violence? We think that some areas might be more subject to violence and crime. 

- Is there an evolution throughout the years of the violence in each neighborhood? Did some areas manage to handle crime better than others?

- Correlate some factors that correspond to the quality of life (green area, quality of education, quality of restaurants, price of real estate) and their respective areas with crimes? We would like to see if areas concerned with violence are similar to areas with a high number of failed food inspections. Indeed, there might be more failed food inspections in poorer districts than richer ones.

- Can we predict if a crime will lead to an arrest of the author, the probability to be victim of a certain type of crime or even predict the type of crime given it's other report information?

# Datasets

- [Chicago - Crimes](https://www.kaggle.com/chicago/chicago-crime):
This dataset records many crimes committed in the past 20 years in Chicago. We have access to the year, time, location, type of crime, district of each crime. We can thus make a geographical analysis to find concerned areas. We can see the evolution using the timestamp. 

- [Chicaco - Food Inspection](https://www.kaggle.com/chicago/chicago-food-inspections):
This dataset records the results of food inspection since 2010 in Chicago. We have access to the name and location of the food institution, the results of the test. We can find areas that tend to fail inspections and see how they compare with the crime rate.  It can tell us if crimes are located in areas with good restaurants (might be richer areas) or bad ones (might be poorer areas).

- [Chicago - Taxi Rides (2016)](https://www.kaggle.com/chicago/chicago-taxi-rides-2016):
This dataset contains taxi rides data such as the location of picking and dropping, time of the course. This would allow us to see which areas of the city are well connected and which areas tend to be excluded. We can then try to correlate the results with the violent areas. However, this analysis can only be possible for the 2016 year.

- [Chicago - Flu Clinics](https://healthdata.gov/dataset/flu-shot-locations-2014-present):
List of free flu clinics offered throughout Chicago, either by the Department of Public Health or in collaboration with it.



# Internal Milestones

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

### Week 5 (24/11/2019 - 01/12/2019)

- Build model prediction community areas from location
- Merge the different datasets using community areas


### Week 6 (02/12/2019 - 08/12/2019)

- Answer the research questions using all datasets 
- Build predictive models
- Choose the may to report our work (Data Report / Data Story)

### Week 7 (09/12/2019 - 15/12/2019)

- Create and complete the report/story using our analysis
- Extract the results from the notebooks and report them into the presentation.

### Week 8 (16/12/2019 - 20/12/2019)

- Finish building the report or story 
- Merge notebook and clean the code


### Milestone 3 : 20/12/2019

# Contributions 

- **Louis Amaudruz:**
  - Datasets research (Milestone 1)
  - Clinics dataset preprocessing and analysis (Milestone 2)
  - Machine learning models for Data Story (Milestone 3)

- **Maxence Jouve:** 
  - Project definition and datasets research (Milestone 1)
  - Crime dataset preprocessing and analysis (Milestone 2)
  - Crime dataset analysis for Data Story (Milestone 3)

- **Rayane Laraki:**
  - Taxi rides dataset preprocessing and analysis (Milestone 2)
  - Effects on the city analysis for Data Story (Milestone 3)
  - Prepare the final presentation 

- **Pierre Schutz:**
  - Project definition and datasets research (Milestone 1)
  - Food inspection preprocessing and analysis (Milestone 2)
  - Jekyll website for Data Story (Milestone 3)





