# Future-sales-prediction

We extract data from kaggle for future sales prediction using different categories of data from an ecommerce website and by using python and some of the modules like numpy, pandas, sklearn, seaborn, matplotlib, tensorflow and xgboost we perform the data augmentation such as, For each id and shop_id and date_block_num combinations we complete the dataset by putting it to 0 if it isn't in the dataset.
Next we create test sets by guessing the 33rd month using the previous ones as we want to predict the 34th one. Then we implement xgboost regressor machine learning model and check predictions. From the prediction rate, we thus determine that the linear regression model using xgboost for our following sales data is adequate.
