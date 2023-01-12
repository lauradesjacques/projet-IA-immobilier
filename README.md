# AI project at the service of real estate agents

### Context :
You are an AI developer at a Silicon Valley startup that provides real estate investment services. Relationship managers mentioned that demand has increased recently and it is becoming difficult to do personalized estimates. As a result, the company has entrusted you with automating this task with a predictive model.
The goal is to create a model with your data to predict the value of the median house price by district/block.

### Notebooks :
- Exploratory Data Analysis
- Statistical inference analysis on data
- Procedure followed to find a suitable model
- Protocol for using the model to make predictions

### Data :
Database that contains median house prices for California districts from the 1990 census :
- longitude
- latitude
- housingMedianAge: Median age of a house in a block; a lower figure corresponds to a newer building.
- totalRooms: Total number of rooms in a block
- totalBedrooms: Total number of bedrooms in a block
- population: Total number of people residing in a block
- households: Total number of households, i.e. a group of people residing in a housing unit, for a block
- medianIncome: Median household income in a block of houses (measured in tens of thousands of US dollars)
- medianHouseValue: Median house value for households in a block (measured in US dollars)
- oceanProximity: Location of the house in relation to the sea

### Topics covered :
- Data cleaning techniques: knowing how to deal with duplicates, missing data, outliers, scaling, balancing, encoding, discretizing, feature engineering.
- Statistical inference: perform an inference analysis with the statsmodels library, know how to quantify the statistical significance of the model, identify the cofounding factors, check that the inference conditions are respected.
