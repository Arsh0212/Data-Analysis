# Data Analysis on CARS24 data set (2024) #- kaggle

> The dataset consists the data of ___Maruti Suzuki___ pre-owned cars that were sold in 2024  
**Our goal was to analyse the data from the companies and the customers point of view**

> First the data needed to be cleaned and properly transformed in order to perofrm any analysis
___SQL___
We used SQL to load the data properly and clean the data


  
#Then for advanced Data Analysis the database was connected to python (jupyter notebook)
  The data was separated into Dimensions(catgorical data) and Measures(numerical data)
  Univariate analysis was done on Dimensions and also some bivariate analysis were also performed
  Correlation heatmap was formed between Measures

#Some more analysis is to be performed and a predictive model is also to be coded

#Following conclusions were made
--For Maruti Suzuki 'Baleno' is the hot selling car in second-hand car market
    This could be because of following reasons
      #First Baleno lies in the center of the pricing of the cars(Balance between affordable and effectiveness)
      #Second Baleno comes in all three Fuel_types
      #Third Baleno is also bought for personal use apart from commercial use

--As of Fuel_type the recent second-hand cars are of CNG, Hybrid and petrol, as for old cars diesel is dominant over CNG
    This could be because of following reasons
      #A person looking for a comparatively newer,expensive(good condition) car will buy greener fuel cars due to government regulations
        towards diesel cars
      # Also buying newer car means that the buyer is looking to use it for 6-7 years, no guarantee of disel cars for that long
      # Buyers looking for cheap cars will have to buy diesel as there were less CNG cars before and old CNG car engine gets damaged.

--Factors affecting the price of the cars are
  Age(cars with age 7 were the most sold 2017 models)
  Km_Driven(30-40km driven cars also have high frequency)
  Engine_capacity( also can mean car size) (1.2L is most common)
  Fuel_type (Petrol,Diesel,CNG and Hybrid)
  Transmission Type (Manual is dominanat)
