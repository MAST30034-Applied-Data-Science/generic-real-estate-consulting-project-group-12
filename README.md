# Generic Real Estate Consulting Project
- Group number: Group 12
- Group member: Yonglin He, Ziyi Li, Heng Yu, TianChen Xia, Haoyue Tan

**Research Goal:** Predict rental prices for both residential properties and apartments throughout Victoria, Australia for the next three years

**Timeline:** The timeline for the property dataset downloaded through API is from year 2019 to 2022, containing over 10K+ data, which will used for modelling

## Data
All the detailed information of datasets listed on readme file of data `data/README.md`

## Notebooks
To run the pipeline, please visit the `notebooks` directory and run the files in order:

1.`scraping.ipynb`: Scrape the basic rental data from domain.<br>
2.`get_historical_house_data.ipynb`: Use api to get historical rental data.<br>
3.`get_externel_data.ipynb`: Get the externel features around properties through OpenStreetMap.<br>
4.`get_ptv.ipynb`: Get the transportation data.<br>
5.`get_future_built_school_address.ipynb`: Get the school data that will be built in the future.<br>
6.`population forcasting.ipynb`: Forcasting population for next five years.<br>
7.`modify_shopping.ipynb`: Preprocess the shopping center data to let it be able to merge into our dataframe.<br>
8.`merged_data.ipynb`: Merge all the scraped data together.<br>
9.`prediction.ipynb`: Fit the models and make predictions, also answer to three questions.<br>
10.`visualization.ipynb`: Codes for visualization.<br>


See the overall summary book at `notebooks/notebook summary.ipynb`

## Models
All the trained models are stored under this directory.
How to load the model:
```
import pickle
pickle.dump(xgbc,open(r"../models/trained_XGBoost_model.dat",'wb'))
model = pickle.load(open(r"../models/trained_XGBoost_model.dat", "rb")) 
# now you can use the trained model to predict
```
1. The trained XGBoost model is stored in trained_XGBoost_model.dat 
2. The trained Decison Tree model is stored in trained_decision_tree_model.dat 
1. The trained Random Forest model is stored in trained_RandomForest_model.dat 
1. The trained Linear Regression model is stored in trained_LR_model.dat 
1. The trained MLP model is stored in trained_MLP_model.dat 

## Scripts
There is no python scripts under this folder, all code are stored under notebooks directory.
