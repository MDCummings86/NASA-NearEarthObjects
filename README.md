# NASA-NearEarthObjects
https://www.kaggle.com/datasets/sameepvani/nasa-nearest-earth-objects

1. **An Analysis of Nearest Earth Objects**
   - In this project, I aim to:
       a)clean the data set
       b)understand the minimum, maximum, mean, quartiles, and standard deviation of the numeric columns
       c)understand the distribution of objects by absolute magnitude and maximum estimated distance
       d)understand whether the maximum estimated diameter is on average higher for hazardous or non-hazardous objects 

2. **Introduction**
   a) In this project I will clean the data and perform Exploratory Data Analysis.
   b) I'm trying to find out if most nearest earth objects that have been identified have all columns of information to assess how reliable the discoveries will be. I would like to understand which size or luminosity of objects are more prevalent in our local space. I would also like to identify any correllation between estimated size and whether the object is hazardous. 
   

3. **Data Collection**
   a) The data is sourced from csv files within the following url: https://www.kaggle.com/datasets/sameepvani/nasa-nearest-earth-objects
    b) Within the dataset, the columns are defined as follows:
                          id: Unique Identifier for each Asteroid
                        name: Name given by NASA
            est_diameter_min: Minimum Estimated Diameter in Kilometres
            est_diameter_max: Maximum Estimated Diameter in Kilometres
           relative_velocity: Velocity Relative to Earth
               miss_distance: Distance in Kilometres missed
               orbiting_body: Planet that the asteroid orbits
               sentry_object: Included in sentry - an automated collision monitoring system
          absolute_magnitude: Describes intrinsic luminosity
                   hazardous: Boolean feature that shows whether asteroid is harmful or not   
        - Discuss any data cleaning or preprocessing steps performed.

4. **Data Exploration**
   - Perform exploratory data analysis (EDA) to understand the characteristics of the dataset.
       a) 
   - Visualize the data using appropriate plots, charts, or graphs.
       a)![ alt text for screen readers](/Users/mdcummings/Desktop/Data Analysis/My Projects/NASA - Nearest Earth Objects/NASA-NearEarthObjects/DFDescription.png  "Figure 1")
       b) ![ alt text for screen readers](/Users/mdcummings/Desktop/Data Analysis/My Projects/NASA - Nearest Earth Objects/NASA-NearEarthObjects/AbMagRidge.png "Figure 1")
       c)RVAMlinregress.png ![ alt text for screen readers](/Users/mdcummings/Desktop/Data Analysis/My Projects/NASA - Nearest Earth Objects/NASA-NearEarthObjects/RVAMlinregress.png "Figure 1")
   - Identify any patterns, trends, or outliers in the data.

