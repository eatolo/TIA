Context
This is the dataset used in the second chapter of Aurélien Géron's recent book 'Hands-On Machine learning with Scikit-Learn and TensorFlow'. It serves as an excellent introduction to implementing machine learning algorithms because it requires rudimentary data cleaning, has an easily understandable list of variables and sits at an optimal size between being to toyish and too cumbersome.

The data contains information from the 1990 California census. So although it may not help you with predicting current housing prices like the Zillow Zestimate dataset, it does provide an accessible introductory dataset for teaching people about the basics of machine learning.

Content
The data pertains to the houses found in a given California district and some summary stats about them based on the 1990 census data. Be warned the data aren't cleaned so there are some preprocessing steps required! The columns are as follows, their names are pretty self explanitory:

1. longitude: It is the geographical longitude of the location of the dwelling, measured in degrees.

2. latitude: It is the geographic latitude of the location of the dwelling, measured in degrees.

3. housing_median_age: It is the median age of the houses in the area, measured in years.

4. total_rooms: It is the total number of rooms in the dwellings in the area.

5. total_bedrooms: It is the total number of sleeping rooms in the dwellings in the area.

6. population: It is the total number of people residing in the area.

7. households: It is the total number of households in the area.

8. median_income: This is the median household income in the area, measured in tens of thousands of dollars.

9. median_house_value: It is the median value of homes in the area, measured in dollars.

10. ocean_proximity: It is the proximity of the house to the Pacific Ocean. The possible values are:
- <1H OCEAN: Less than an hour away from the ocean.
- INLAND: Inside the region.
- NEAR OCEAN: At a distance close to the ocean.
- NEAR BAY: Near the San Francisco Bay.
- ISLAND: On an island.

Acknowledgements
This data was initially featured in the following paper:
Pace, R. Kelley, and Ronald Barry. "Sparse spatial autoregressions." Statistics & Probability Letters 33.3 (1997): 291-297.

and I encountered it in 'Hands-On Machine learning with Scikit-Learn and TensorFlow' by Aurélien Géron.
Aurélien Géron wrote:
This dataset is a modified version of the California Housing dataset available from:
Luís Torgo's page (University of Porto)

Inspiration
See my kernel on machine learning basics in R using this dataset, or venture over to the following link for a python based introductory tutorial: https://github.com/ageron/handson-ml/tree/master/datasets/housing