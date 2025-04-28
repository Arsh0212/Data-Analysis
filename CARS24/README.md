# Data Analysis on CARS24 data set (2024) # kaggle
## The dataset consists the data of ___Maruti Suzuki___ pre-owned cars that were sold in 2024

*Our goal was to analyse the data from the companies and the customers point of view*

- ### First the data needed to be cleaned and properly transformed in order to perofrm any analysis

  ### SQL 
  We used SQL to load the data properly and clean the data
  
  - New columns were made from existing features
  - Few columns were dropped
  - NULL values were checked
  - Some continuos numerical data was converted to categorical data(KM_Driven_Range)
  - Basic EDA was performed on the dataset

- ### After the dataset was prepared ,it was time for some in-depth analysis

  ### Python
  Python with it's libraries(pandas,numpy,matplotlib,seaborn) was used.
  Python was connected to the database using SQLAlchemy  
  
  - Features were divided into _Dimensions_ and _Measures_
  - _Univariate_ analysis was conducted on _Dimensions_
  - _Bivariate_ analysis was performed between possible _pairs of Dimension and Measures_
  - Graphs were made using matplotlib and seaborn
  - A correlation graph was made between numerical values
  
- ### Following conclusions were made
  #### 1.For Maruti Suzuki 'Baleno' is the hot selling car in second-hand car market
    - First Baleno lies in the center of the pricing of the cars(Balance between affordable and effectiveness)  
    - Second Baleno comes in all three Fuel_types  
    - Third Baleno is also bought for personal use apart from commercial use  
  
  #### 2.As of Fuel_type the recent second-hand cars are of CNG, Hybrid and petrol, as for old cars diesel is dominant over CNG  
    - A person looking for a comparatively newer,expensive(good condition) car will buy greener fuel cars due to government regulations
            towards diesel cars  
    - Also buying newer car means that the buyer is looking to use it for 6-7 years, no guarantee of disel cars for that long  
    - Buyers looking for cheap cars will have to buy diesel as there were less CNG cars before and old CNG car engine gets damaged.
  
  #### 3.Factors affecting the price of the cars are
    - Age(cars with age 7 were the most sold 2017 models)
    - Km_Driven(30-40km driven cars also have high frequency)
    - Engine_capacity( also can mean car size) (1.2L is most common)
    - Fuel_type (Petrol,Diesel,CNG and Hybrid)
    - Transmission Type (Manual is dominanat)
