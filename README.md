**Titanic EDA**
Exploratory Data Analysis on the Titanic dataset to derive insights into passenger survival rates.

**Project Overview**
This project analyzes the Titanic dataset to understand the survival distribution based on factors like class, age, gender, and fare. It involves data preprocessing, visualization, and correlation analysis using Python.

**Dataset**
Source: [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data)
Size: 891 rows × 12 columns

**Main Objective**: Identify factors influencing passenger survival.
Libraries Used: 
  Pandas
  Matplotlib
  Seaborn
  Methodology
  
**Data Preprocessing**
Checked for missing values
Removed the Cabin column due to excessive missing data
Removed rows with missing Age values
Final dataset: 712 rows × 11 columns

**Exploratory Data Analysis**
Summary statistics (mean, median, standard deviation)

**Data visualization:**
Bar Chart: Passenger distribution across classes
Histogram: Age distribution
Pie Chart: Gender distribution
Box Plot: Fare distribution
Heatmap: Correlation between features
Violin Plot: Age distribution across classes
Countplot: Survival rates by class

**Key Insights**
Mean passenger age: 29.64 years
Mean fare: $34.56
Most passengers were in 3rd class
Higher class passengers had a higher survival rate
Strong negative correlation between fare & class, and class & survival
Most survivors were from 1st class

**Conclusion**
Higher-class passengers had better survival chances.
More male passengers were onboard.
Fare prices were highest for 1st class passengers.

**Project Files**
titanic_eda.ipynb – Jupyter Notebook containing the analysis
titanic.csv – Dataset used (or link to download)
README.md – Project documentation
