
# House Price Prediction Using Machine Learning and Deep Learning

I've developed a comprehensive house price prediction model, using Machine Learning Algorithms and Deep Learning techniques. My objective was to build a robust predictive model that estimate house prices based on various features like square footage, number of bedrooms, location, etc, and compare all models to see which one worked the best.

## Dataset

You can download the dataset from here or from:

kaggle - [Dataset can be downloaded from here](https://www.kaggle.com/datasets/harlfoxem/housesalesprediction)


## Algorithms Used

**Machine Learning:** 
- K-Nearest Neighbors (KNN)
- Ridge Regression
- Linear Regression
- Lasso Regression
- Random Forest
- Decision Tree

**Deep Learning:** 
- Sequential


## Features Column of the dataset 

- **id** - Unique ID for each home sold
- **date** - Date of the home sale
- **price** - Price of each home sold
- **bedrooms** - Number of bedrooms
- **bathrooms** - Number of bathrooms, where .5 accounts for a room with a toilet but no shower
- **sqft_living** - Square footage of the apartments interior living space
- **sqft_lot** - Square footage of the land space
- **floors** - Number of floors
- **waterfront **- A dummy variable for whether the apartment was overlooking the waterfront or not
- **view** - An index from 0 to 4 of how good the view of the property was
- **condition** - An index from 1 to 5 on the condition of the apartment,
- **grade** - An index from 1 to 13, where 1-3 falls short of building construction and design, 7 has an average level of construction and design, and 11-13 have a high quality level of construction and design.
- **sqft_above** - The square footage of the interior housing space that is above ground level
- **sqft_basement** - The square footage of the interior housing space that is below ground level
- **yr_built** - The year the house was initially built
- **yr_renovated** - The year of the house’s last renovation
- **zipcode** - What zipcode area the house is in
- **lat** - Lattitude
- **long**- Longitude
- **sqft_living15** - The square footage of interior housing living space for the nearest 15 neighbors
- **sqft_lot15** - The square footage of the land lots of the nearest 15 neighbors


## Process

This section gives overview how I tackled this project

```bash
  1) Data Preprocessing
  2) Feature Engineering
  3) Exploratory Data Analysis
  4) Model Building and training for Machine Learning Algorithms
  5) Evaluating Machine Learning Models
  6) Checking Performance on new Data
  7) Model Building and training for Deep Learning Algorithms
  8) Evaluating Deep Learning Algorithms
  9) Checking Performance on new Data
  10) Comparing their performance
```
    
## FAQ

#### Which model performed best?

Decision Tree with almost 100% accuracy

#### Which model performed worst?

KNN Algorithm

#### How was Deep Learning performance?

Good. But it could be better. Its explained variance is 0.8482, which is decent.

#### How many layers did you used?

6 layers with 19 neurons.
1 output layer with 1 neuron (for price)

