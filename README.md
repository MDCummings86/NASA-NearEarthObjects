# NASA-NearEarthObjects
https://www.kaggle.com/datasets/sameepvani/nasa-nearest-earth-objects

1. **An Analysis of Nearest Earth Objects**
   - In this project, I am using :
       a)clean the data set
       b)understand the minimum, maximum, mean, quartiles, and standard deviation of the numeric columns representing the min and max estimated diameter, relative velocity, miss distance, and absolute magnitude.
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
   - A description of the dataset 
       a)![DFDescription](https://github.com/MDCummings86/NASA-NearEarthObjects/assets/126340452/f29546cd-46db-43c1-a7c0-47e9239acbb3.png?raw=true)
   - The following heat map verifies there are no duplicate values.
       b)![heatmap](https://github.com/MDCummings86/NASA-NearEarthObjects/assets/126340452/c0bbab97-12c8-46a8-ad36-af0d53f9a584)
   - The following ridge map shows the distribution of near earth objects. Notice how there is the highest density objects with absolute magnitude of over 27, while there is a low denisty of objects with absolute magnitude below 14. 
       c)![AbMagRidge](https://github.com/MDCummings86/NASA-NearEarthObjects/assets/126340452/5fcf16fc-cab9-4852-a6ee-077179087273.png?raw=true)
   - The following linear regression shows the correlation between absolute magnitude and relative velocity. The r-squared is: 0.12521875685386286. The correlation coefficient confirms a very weak negative correlation
between the relative velocity of a near earth object and its absolute magnitude.
       d)![RVAMlinregress](https://github.com/MDCummings86/NASA-NearEarthObjects/assets/126340452/0809581d-72de-4596-a70b-91ef1ed9df44.png?raw=true)

  

