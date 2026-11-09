Data_Analytics
Nothing interesting. It's Repository.

Chaika Yurii CS-41
Laboratory Work №3
Course: Data Analytics
Student: Yurii Chaika, CS-41

Objective
To develop practical skills in data cleaning and transformation using Pandas and NumPy. The work focuses on handling missing values, duplicate records, outliers, type conversion, feature engineering, categorical encoding, and data scaling techniques.

Dataset
War Thunder Vehicles Dataset (general_vehicles.csv)

Tasks Completed
Imported Pandas and NumPy libraries and loaded the dataset from Google Drive.
Explored the dataset structure using head(), shape, info(), and describe().
Analyzed missing values and applied appropriate handling methods.
Detected and removed duplicate records from the dataset.
Identified outliers using the Interquartile Range (IQR) method.
Converted date-related columns into datetime format.
Cleaned string data by removing extra spaces and standardizing text values.
Created additional features from existing columns.
Applied One-Hot Encoding to categorical variables.
Performed Min-Max Normalization and Z-Score Standardization on numerical data.
Created a custom binary feature using np.where().
Saved the processed dataset into a new CSV file.
★ Additional task: implemented a reusable clean_dataset() function that automates duplicate removal, missing value handling, date conversion, and basic preprocessing steps.
Technologies Used
Python
Pandas
NumPy
Google Colab
Jupyter Notebook
Conclusion
During this laboratory work, various data preprocessing techniques were applied to a real-world dataset. Missing values, duplicate records, and outliers were analyzed and processed. Categorical features were transformed using one-hot encoding, and numerical data were scaled using normalization and standardization techniques.

The completed workflow demonstrates a typical data cleaning pipeline and prepares the dataset for further analytical or machine learning tasks.
