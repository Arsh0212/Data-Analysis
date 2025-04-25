Data Analysis on CARS24 data set (2024)

#The data was picked from kaggle and downloaded on the local system

#It was then loaded in postgresql database for basic transformations and queries
  A few columns were added , the data was cleaned and the columns were dropped.
  
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
  Age
  Km_Driven
  Engine_capacity( also can mean car size)
  Fuel_type 
  Transmission Type
