# House-Prices-Phase-2

This project develops machine learning models using regression techniques to predict home prices in Ames, Iowa based on 79 housing features from the Ames Housing Dataset compiled by Dean De Cock dataset. The analysis demonstrates how factors beyond typical considerations significantly influence housing prices. The task is to accurately forecast the SalePrice for each house in the test dataset.

### Project Pipeline

###### Exploratory Data Analysis (EDA)
- Perform univariate, bivariate, and multivariate analyses
- Create visualizations to understand feature relationships
- Examine data distributions, target variable patterns, and identify potential issues

###### Data Preprocessing
- Handle missing values through imputation or/and removal
- Remove unnecessary columns and features with strong collinearity
- Encode categorical variables and scale numerical features
- Save cleaned dataset for modeling

###### Model Development and Tuning
- Create train-test splits
- Implement regression models (Random Forest, Linear Regression)
- Perform hyperparameter tuning via GridSearchCV
- Re-train models with optimized parameters

###### Model Evaluation and Selection
- Evaluate performance using RMSE, R², and MAE metrics
- Compare models and select best performer

###### Prediction Generation
- Apply final model to test dataset
- Generate housing price predictions

### Tools

- Python 
- Jupyter Notebooks
- MatplotLib
- Seaborn
- Scikit-Learn
- Pandas 
- Numpy

### Dataset Description

###### Numeric Features
- SalePrice: The property's sale price in dollars. This is the target variable that this project aims to predict.
- MSSubClass: The building class
- LotFrontage: Linear feet of street connected to property
- LotArea: Lot size in square feet
- OverallQual: Overall material and finish quality
- OverallCond: Overall condition rating
- YearBuilt: Original construction date
- YearRemodAdd: Remodel date
- MasVnrArea: Masonry veneer area in square feet
- BsmtFinSF1: Type 1 finished square feet
- BsmtFinSF2: Type 2 finished square feet
- BsmtUnfSF: Unfinished square feet of basement area
- TotalBsmtSF: Total square feet of basement area
- 1stFlrSF: First Floor square feet
- 2ndFlrSF: Second floor square feet
- LowQualFinSF: Low quality finished square feet (all floors)
- GrLivArea: Above grade (ground) living area square feet
- BsmtFullBath: Basement full bathrooms
- BsmtHalfBath: Basement half bathrooms
- FullBath: Full bathrooms above grade
- HalfBath: Half baths above grade
- Bedroom: Number of bedrooms above basement level
- Kitchen: Number of kitchens
- TotRmsAbvGrd: Total rooms above grade (does not include bathrooms)
- Fireplaces: Number of fireplaces
- GarageYrBlt: Year garage was built
- GarageFinish: Interior finish of the garage
- GarageCars: Size of garage in car capacity
- GarageArea: Size of garage in square feet
- WoodDeckSF: Wood deck area in square feet
- OpenPorchSF: Open porch area in square feet
- EnclosedPorch: Enclosed porch area in square feet
- 3SsnPorch: Three season porch area in square feet
- ScreenPorch: Screen porch area in square feet
- PoolArea: Pool area in square feet
- MiscVal: Value of miscellaneous feature
- MoSold: Month Sold
- YrSold: Year Sold

###### Categorical Features

- MSZoning: The general zoning classification
- Street: Type of road access
- Alley: Type of alley access
- LotShape: General shape of property
- LandContour: Flatness of the property
- Utilities: Type of utilities available
- LotConfig: Lot configuration
- LandSlope: Slope of property
- Neighborhood: Physical locations within Ames city limits
- Condition1: Proximity to main road or railroad
- Condition2: Proximity to main road or railroad (if a second is present)
- BldgType: Type of dwelling
- HouseStyle: Style of dwelling
- RoofStyle: Type of roof
- RoofMatl: Roof material
- Exterior1st: Exterior covering on house
- Exterior2nd: Exterior covering on house (if more than one material)
- MasVnrType: Masonry veneer type
- ExterQual: Exterior material quality
- ExterCond: Present condition of the material on the exterior
- Foundation: Type of foundation
- BsmtQual: Height of the basement
- BsmtCond: General condition of the basement
- BsmtExposure: Walkout or garden level basement walls
- BsmtFinType1: Quality of basement finished area
- BsmtFinType2: Quality of second finished area (if present)
- Heating: Type of heating
- HeatingQC: Heating quality and condition
- CentralAir: Central air conditioning
- Electrical: Electrical system
- KitchenQual: Kitchen quality
- FireplaceQu: Fireplace quality
- Functional: Home functionality rating
- GarageType: Garage location
- GarageQual: Garage quality
- GarageCond: Garage condition
- PavedDrive: Paved driveway
- PoolQC: Pool quality
- Fence: Fence quality
- MiscFeature: Miscellaneous feature not covered in other categories
- SaleType: Type of sale
- SaleCondition: Condition of sale