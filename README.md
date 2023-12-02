Introduction:
Diabetes is a prevalent and growing health concern worldwide, with its causes attributed to a combination of genetic factors and environmental lifestyle. In an effort to understand this complex disease, researchers conducted a study on the Pima tribe, also known as the Pima Indians, a community in America. This study revealed that women in the Pima tribe are particularly susceptible to diabetes at an early age. The dataset used in this project comprises instances selected from this research, focusing on females aged at least 21 years with Pima Indian heritage.

Objective:
The primary objective of this project is to conduct Exploratory Data Analysis (EDA) to gain insights into various aspects of diabetes within the Pima tribe. Through data visualization and statistical analysis, we aim to understand the patterns and relationships present in the dataset, shedding light on potential factors influencing diabetes among the tribe's female population.

Dataset Overview:
The dataset includes the following features:

Pregnancies: Number of times pregnant
Glucose: Plasma glucose concentration over 2 hours in an oral glucose tolerance test
BloodPressure: Diastolic blood pressure (mm Hg)
SkinThickness: Triceps skin fold thickness (mm)
Insulin: 2-Hour serum insulin (mu U/ml)
BMI: Body mass index (weight in kg/(height in m)^2)
DiabetesPedigreeFunction: A function scoring the likelihood of diabetes based on family history.
Age: Age in years
Outcome: Class variable (0: person is not diabetic, 1: person is diabetic)
Project Structure
The project is structured as follows:

Data Loading and Overview: Importing necessary libraries and loading the Pima diabetes dataset. Displaying the first and last records, checking dimensions, and examining data types.

Data Exploration and Visualization: Performing Exploratory Data Analysis (EDA) to understand the distribution, summary statistics, and relationships among variables. Visualizing key features using plots like distribution plots, pair plots, and scatter plots.

Model Training: Splitting and scaling the data, training a Logistic Regression model, and a Random Forest model. Evaluating model performance on accuracy and confusion matrices.

Conclusion: Summarizing key findings and observations from the analysis, and comparing the performance of the trained models.
