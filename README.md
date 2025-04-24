# Anu Swathi - Task1

**Objective**-This project demonstrates the process of cleaning and preprocessing raw data from the Titanic dataset to prepare it for machine learning tasks. The goal is to ensure the data is clean, consistent, and ready for modeling.

**Tools Used**
1.Python
2.Pandas
3.NumPy
4.Matplotlib / Seaborn (for data visualization)
5.Scikit-learn (for feature scaling)

**Dataset** - The dataset used is the Titanic passenger dataset. It contains information such as age, sex, ticket fare, and whether a passenger survived.

**Steps Performed**
1. Import and Explore the Dataset :
(i)Loaded the CSV file using Pandas.
(ii)Displayed basic information including column types and missing values.
2. Handle Missing Values
(i)Replaced missing values in the Age column with the median age.
(ii)Filled missing values in the Embarked column with the mode.
(iii)Dropped the Cabin column due to a high number of missing entries.
3. Encode Categorical Features
(i)Applied one-hot encoding to the Sex and Embarked columns.
(ii)Used drop_first=True to avoid the dummy variable trap.
4. Normalize/Standardize Numerical Features - Standardized the Age and Fare columns using StandardScaler from scikit-learn.
5. Visualize and Remove Outliers
(i)Used boxplots to visualize outliers in numerical features.
(ii)Removed outliers using the IQR (Interquartile Range) method.

**Output**
(i)Cleaned and preprocessed dataset ready for modeling.
(ii)Shape and preview of the final dataset displayed.
