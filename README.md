# Level-2-Capstone-Project-2-2022

# *1. The Purpose*

The purpose of the project is to create a detailed Exploratory Data Analysis (EDA) of a specific data set and present the findings by means of tables and visualisations

# *2. The Data*

The data that's analysed is for an [Automobile Data Set](https://github.com/Chris-github01/Level-2-Capstone-Project-2-2022/blob/main/automobile.csv). The following data is given in the data set:
  * symbolling
  * normalized-losses
  * make
  * fuel-type
  * aspiration
  * num-of-doors
  * body-style
  * drive-wheels
  * engine-location
  * wheel-base
  * curb-weight
  * engine-type
  * num-of-cylinders
  * engine-size
  * horsepower
  * peak-rpm
  * city-mpg
  * highway-mpg
  * price
 
 # *3. Data Analysis*
 
 The Exploratory Data Analysis is broken down into the following sections:
  * Introduction
  * Data cleaning
  * Missing data
  * Data stories and visualisations
 
 Each section listed above will be discussed below
 
 ## 3.1 Introduction
 
 The introduction mentions that the EDA is an analysis of an automobile data set and that a number of questions will be answered by means of tables and visualisations.
 
 ## 3.2 Data cleaning
 
 On inspection, the data contains '?' which needs to be replaced with 'NAN'. The replace() function is used to "clean" the data
 
 ## 3.3 Missing data
 
 In this section the data set is checked for missing data. In this EDA it is done in list form, table form and as a visualisation. Functions are then used to replace the missing data with the appropriated  mean values 
 
 ## 3.4 Data stories and visualisations
 
 In this section of the [Exploratory Data Analysis](https://github.com/Chris-github01/Level-2-Capstone-Project-2-2022/blob/main/automobile.ipynb), we extract stories and assumptions based on visualizations of the data set. The analysis is broken down into the following sections:
  * Aspiration analysis
  * Make analysis
  * Price analysis
  * Engine specification analysis
  * Price vs Body style analysis
  * Power to weight ratio 
  * Fuel economy
  * Aspiration/ price analysis
  * Engine size analysis
  * Frequency analysis
  
  ### 3.4.1 Aspiration analysis
  
  Here we will check how many automobiles are normally aspirated versus how many have turbos.
  
  ### 3.4.2 Make analysis
  
  Under make analysis we will check how many different makes each automobile manufacturer produces.
  
  ### 3.4.3 Price analysis
  
  Here we will check the average price per car for each manufacturer. 
  
  ### 3.4.4 Engine specification analysis
  
  In this section we will check the engine specifications in terms of 'engine size', 'horsepower' and 'peak-rpm'. 
  
  ### 3.4.5 Price vs Body style analysis
  
  Here we will compare the price to body style of each automobile.
  
  ### 3.4.6 Power to weight ratio 
  
  In this section we compare the power (horsepower) to weight (curb-weight which is the weight of the car with a full tank of gas) ratio. The comparison is also between gas and diesel cars, to see which type of fuel has more power.
  
  ### 3.4.7 Fuel economy
  
  Here we will compare the fuel economy between gas and diesel cars.
  
  ### 3.4.8 Aspiration/ price analysis
  
  In this section we compare the price to body-style and also the aspiration type, which is compared between standard or turbo.
  
  ### 3.4.9 Engine size analysis
  
  Here we will compare the engine sizes. The power output (horsepower) is dependent on the number of cylinders of the different cars. 
  
  ### 3.4.10 Frequency analysis
  
  In this section we will check the frequencies of the engine-types as well as number-of-doors.
  
# *4. Results*

After analysing the data, a detailed report with [results](https://github.com/Chris-github01/Level-2-Capstone-Project-2-2022/blob/main/EDA.pdf) is made.
