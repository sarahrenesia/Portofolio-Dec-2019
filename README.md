PROJECTS
===

### Portfolio 1 
There are 2 datasets, which are strava and the Golden Cheetah. We combined both of the data by keeping the rows that appear in both data (has the same date and time). Before the data being explored more, first data is being filtered, the rows with no measured power and NaN values are removed. After that these analysis are being done:
- The shape of the key variables distribution
- The realtionship between the key variables
- The differences between the three categories: Race, Workout, and Ride
- What variables lead more kudos and which rides are more popular

### Portfolio 2
In the portofolio 2, we tried to reproduced the analysis process in the Journal : Candanedo, L., Feldheim, V. and Deramaix, D. (2017). Data driven prediction models of energy use of appliances in a low-energy house. Energy and Buildings, 140, pp.81-97.
The purpose of this experiment is to understand the relationships between the appliances' energy consumption with different predictors. Using the data from the experiment, we would also want to be able to do a prediction of the appliances' energy consumption and also to obtain wich predictors give a significant effect to the energy consumption. 
1. Importing the data (energydata_complete.csv).
2. Checking the variability and distribution of the energy consumption.
3. See the relationship between the Appliancess energy consumption and all the variables.
4. Identification of the time and day trend in the consumption of energy.
5. Make a linear regression model and evaluating the model, see how it predicts the Appliances Energy Consumption
6. Use the sklearn RFE function to apply Recursive Feature Estimation to the data to rank and select the best features 

### Portfolio 3
Visualisating how the K-Means Clustering work by these steps
1. Generate the random data with 4 centres
2. Generate 4 random centres as start of K-Means clustering
3. Visualise how the clustering works for each iterations
4. Show the final clustering result
