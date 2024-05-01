# data3000-adv-ds
for my advanced data science class (spring 2024)

goal:
* take raw ChatGPT-generated data and clean, feature engineer, model, predict, and analyze it

instructions:
* everything will be in final/chatgpt-influencer
* also, you should just be able to hit "run-all" for all of these

1. navigate to notebooks/datacleaning
   - here, the notebook will take the data from the raw folder (straight ChatGPT-generated rows) and clean it
   - note: make sure to edit the path if it does not work
   - the new data should be saved in your processed data folder
2. navigate to notebooks/feature_engineering
   - here, the notebook will take the cleaned data and engineer some columns for a more generalized version of the features
   - this was done so that there were not > 160 columns
   - the new data should be saved in your processed data folder, this is your final dataset before modeling
3. navigate to notebooks/linear_regression
   - here, the notebook will take the clean and engineered data and split and normalize it, train it and make predictions off of it, and then output some measures to assess it's accuracy
   - note: there will be an additional dataframe that is saved to the processed data folder containing the coefficients of the model's equation
4. navigate to notebooks/data_analysis
   - here, the notebook will just display an assortment of plots that will show the relationship between one isolated variable and the yearly income
