# PRODIGY_DS-02

🚢 Titanic Data Cleaning & Exploratory Data Analysis (EDA)

📌 Overview
This project involves data cleaning and exploratory data analysis (EDA) on the Titanic dataset provided by Kaggle. The goal is to uncover patterns and relationships between variables—particularly those that influenced passenger survival.

By exploring the dataset visually and statistically, we aim to gain insights into the demographic and socioeconomic factors that contributed to survival during the Titanic disaster.

📁 Dataset Details
Source: Kaggle Titanic - Machine Learning from Disaster

Files Used: train.csv (main dataset for analysis)

Attributes Analyzed:

PassengerId, Survived, Pclass, Name, Sex, Age, SibSp, Parch, Ticket, Fare, Cabin, Embarked

✅ Tasks Performed
1. Data Cleaning
Checked dataset shape, column types, and missing values

Handled missing values:

Age: Filled using median

Embarked: Filled using mode

Cabin: Dropped due to high null percentage

Converted categorical variables to numerical format for analysis

2. Exploratory Data Analysis (EDA)
Used visualizations (bar charts, histograms, box plots) to explore:

Survival by Gender

Survival by Passenger Class

Age distribution and survival rate

Fare distribution by class and survival

Created a correlation heatmap to observe relationships among features

Derived insights using group-by and pivot table operations

🧪 Tools Used
Google Colab (Python environment)

Python Libraries:

pandas – data manipulation

numpy – numerical operations

matplotlib & seaborn – visualizations

🔍 Key Insights
Females had a much higher survival rate compared to males.

1st class passengers were more likely to survive than those in 2nd or 3rd class.

Younger passengers, especially children below 10, showed higher survival chances.

High ticket fares and being in the upper class correlated positively with survival.

▶️ How to Use
Open the Colab notebook from the link above.

Upload the train.csv file when prompted (or mount your Google Drive).

Run all cells sequentially to see data cleaning and EDA in action.

📬 Contact
For questions or suggestions, feel free to raise an issue or contact me directly via GitHub.
