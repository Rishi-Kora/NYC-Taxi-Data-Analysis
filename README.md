# NYC-Taxi-Data-Analysis<br>
Exploratory Data Analysis - NYC Taxi Duration Data<br>
In this repository, I have taken NYC Taxi Duration data from Kaggle and I have done:<br>

1. Import necessary libraries<br>

The Colab notebook already imports the necessary libraries: Pandas, NumPy, Matplotlib, Seaborn, and Scikit-learn components. You don't need to import them again.<br>

2. Load the dataset<br>

The dataset is already loaded and combined into combined_df in the Colab notebook.<br>

3. Data Cleaning and Preprocessing<br>

Handling missing values:<br> The Colab notebook handles missing values by dropping rows with missing trip_duration and imputing with the mean for other numerical features.<br>

Converting datetime features:<br> The notebook converts pickup_datetime and dropoff_datetime into separate year, month, day, hour, minute, and second columns, which is helpful for analysis.<br>

Encoding categorical features:<br> The notebook uses Label Encoding to convert vendor_id and store_and_fwd_flag into numerical representations.<br>
4. Duplicate Removal<br>

The Colab notebook removes duplicate rows using drop_duplicates().<br>

5. Outlier Detection and Removal<br>

The notebook uses the Z-score method to detect and remove outliers based on numerical features.<br>

6. Data Visualization and Exploration<br>

Correlation heatmap:<br> The notebook creates a correlation heatmap using sns.heatmap to visualize relationships between numerical features.<br>

Descriptive statistics:<br> The notebook uses describe().transpose() to display summary statistics of the dataset.<br>

As the dataset in this code is too big and I am not able to upload the dataset, please do download the ataset from this link:<br>
https://www.kaggle.com/c/nyc-taxi-trip-duration/data

Feel free to download the code and data.
