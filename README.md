# Heart-Disease-EDA

## Introduction:
This repository contains the Exploratory Data Analysis (EDA) for a heart disease dataset. The goal of this analysis is to gain insights into the dataset, understand the distribution and relationships of variables and identify patterns. 

## Dataset
The dataset used for this analysis is sourced from Kaggle. It contains the following columns:
age
sex
chest pain type (4 values)
resting blood pressure
serum cholestoral in mg/dl
fasting blood sugar > 120 mg/dl
resting electrocardiographic results (values 0,1,2)
maximum heart rate achieved
exercise induced angina
oldpeak = ST depression induced by exercise relative to rest
the slope of the peak exercise ST segment
number of major vessels (0-3) colored by flourosopy
thal: 0 = normal; 1 = fixed defect; 2 = reversable defect
The names and social security numbers of the patients were recently removed from the database, replaced with dummy values

## Steps to replicate
1. Go to the Kaggle Datasets page to explore the available datasets. You can search for specific datasets using keywords or browse through various categories.
   
2. Select a Heart Disease Dataset:
Look for a heart disease dataset that interests you or aligns with your analysis objectives.Click on a dataset to access its details, including a description, file format, size, and any associated kernels or notebooks.

3. Download the Dataset. If the dataset is available for download, click the "Download" button to save it to your local machine. Make sure to note the file path where you downloaded the dataset.
   
4. To load a dataset using Python in Google Colab, follow these steps:
Access Google Colab: Sign in with your Google account.
Create a New Colab Notebook: Click on the "New Notebook" button to create a new Colab notebook.
Upload the Dataset to Google Colab.

5. After you have uploaded the CSV file, now it is time to read the CSV file.
   
6. Creating pie charts: Using sex and age here for the pie chart.

![image](https://github.com/ahanadasg/Heart-Disease-EDA/assets/113302918/977d8ee0-5111-4838-a3a7-4a866964e587)

7. Creating Violin Plot: Using age(age), resting blood pressure(trestbps), serum cholestoral in mg/dl(chol), maximum heart rate achieved(thalach). The abbreviations used in the excel are given in bracket. 

![image](https://github.com/ahanadasg/Heart-Disease-EDA/assets/113302918/880f2758-d459-4a34-8587-6c1aba06da22)

8. Correlation heatmap: Using values of age, resting blood pressure, serum cholestoral in mg/dl, maximum heart rate achieved, oldpeak = ST depression induced by exercise relative to rest, thal: 0 = normal; 1 = fixed defect; 2 = reversable defect.

![image](https://github.com/ahanadasg/Heart-Disease-EDA/assets/113302918/ef9af15f-c809-4356-ae3b-d57abb3bda15)

9. Pair Plot: Using values of age, resting blood pressure, serum cholestoral in mg/dl, maximum heart rate achieved, oldpeak = ST depression induced by exercise relative to rest, thal: 0 = normal; 1 = fixed defect; 2 = reversable defect.

![image](https://github.com/ahanadasg/Heart-Disease-EDA/assets/113302918/853c9a62-9c73-4e6d-8eca-613f14bc2e83)

10. Joint Plot: Age(age) versus Maximum heart rate achieved(thalach)

![image](https://github.com/ahanadasg/Heart-Disease-EDA/assets/113302918/f11d23dd-20db-471e-941f-0291f2536369)

## Conclusion

The heart disease EDA provided a comprehensive overview of the dataset, identifying potential risk factors and relationships among features. These findings can pave the way for more in-depth research, medical studies, and predictive modeling efforts to aid in the prevention and treatment of heart disease.
