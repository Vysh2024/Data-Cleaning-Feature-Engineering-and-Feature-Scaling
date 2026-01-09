# Data-Cleaning-Feature-Engineering-and-Feature-Scaling
The main objective of this project is to design and implement a robust data preprocessing system that addresses common challenges such as missing values, outliers, inconsistent formatting, and noise. By performing effective data preprocessing, the project aims to enhance the quality, reliability, and usefulness of the data for machine learning.

Dataset

The dataset used in this project was provided as part of the assignment. It contains both numerical and categorical features, including attributes such as age, salary, gender, and place. The dataset is stored locally as a CSV file and is processed using Python libraries.

Tools and Libraries Used

Python was used as the primary programming language. The main libraries include Pandas and NumPy for data manipulation, Matplotlib for data visualization, and Scikit-learn for encoding and feature scaling.

Data Exploration

The dataset was initially explored to understand its structure and content. Unique values and the number of unique entries were identified for each feature. Statistical analysis was performed to understand the distribution of numerical and categorical variables. Column names were renamed into a consistent and standardized format to improve readability and usability.

Data Cleaning

Missing and inappropriate values were identified and handled appropriately. The value 0 in the age column was replaced with null values. Duplicate rows were removed to avoid redundancy. Missing numerical values were treated using median or mean, while missing categorical values were replaced using the mode. This ensured a clean and complete dataset.

Data Analysis

The cleaned dataset was filtered based on given conditions, specifically selecting records where age is greater than 40 and salary is less than 5000. A scatter plot was created to visualize the relationship between age and salary. Additionally, the number of people from each place was counted and represented visually using a bar chart.

Data Encoding

Categorical variables were converted into numerical form to make the data suitable for machine learning algorithms. Label encoding was applied to binary categorical features such as gender, while one-hot encoding was used for multi-category features such as place.

Feature Scaling

After encoding, numerical features were scaled using two different techniques. StandardScaler was used to normalize features to a standard normal distribution, and MinMaxScaler was used to scale values between 0 and 1. This step ensures that features contribute equally during model training.

Final Outcome

The final dataset is clean, consistent, and fully prepared for machine learning applications. All preprocessing steps were successfully applied, making the data reliable and suitable for further analysis and model development.

Conclusion

This project highlights the importance of data preprocessing in the machine learning pipeline. Effective preprocessing significantly enhances data quality and improves the performance and reliability of machine learning models.


Align it exactly with your rubric wording

Just tell me 😊
