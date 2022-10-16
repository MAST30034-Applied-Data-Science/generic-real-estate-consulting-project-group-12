# Generic Real Estate Consulting Project
- Group number: Group 12
- Group member: Yonglin He, Ziyi Li, Heng Yu, TianChen Xia, Haoyue Tan

**Research Goal:** Predict rental prices for both residential properties and apartments throughout Victoria, Australia for the next three years

**Timeline:** The timeline for the property dataset downloaded through API is from year 2019 to 2022, containing over 10K+ data, which will used for modelling

## Datasets
ALl the detailed information of datasets listed on readme file of data `data/README.md`


To run the pipeline, please visit the `notebooks` directory and run the files in order:

1.`scraping.ipynb`: Scrape the basic rental data from domain.

2.`get_historical_data.ipynb`: Use api to get historical rental data.

3.`get_externel_data.ipynb`: Get the environment and some other geolocation data.

4.`get_ptv.ipynb`: Get the transportation data.

5.`get_future_built_school_address.ipynb`: Get the school data that will be built in the future.

6.`population forcasting.ipynb`: Forcasting population for next five years.

7.`modify_shopping.ipynb`: Preprocess the shopping center data to let it be able to merge into our dataframe.

8.`merged_data.ipynb`: Merge all the scraped data together.

9.`prediction.ipynb`: Fit the models and make predictions, also answer to the third question.

10.`visualization.ipynb`: Codes for visualization.


See the overall summary book at `notebooks/notebook summary.ipynb`
