# CardiovasculardiseasesPrediction

1.	Introduction 

Heart is the most important organ of human being. Heart failure (HF) occurs when the heart cannot pump enough blood to meet the needs of the body. Available electronic medical records of patients quantify symptoms, body features, and clinical laboratory test values, which can be used to perform biostatistics analysis aimed at highlighting patterns and correlations otherwise undetectable by medical doctors. Machine learning, in particular, can predict patients’ survival from their data and can individuate the most important features among those included in their medical records. Cardiovascular diseases kill approximately 17 million people globally every year, and they mainly exhibit as myocardial infarctions and heart failures.

About half of all people diagnosed with congestive heart failure will survive five years. About 30% will survive for 10 years. We analyzed a dataset containing the medical records of 299 heart failure patients collected at the Faisalabad Institute of Cardiology and at the Allied Hospital in Faisalabad during April–December 2015. The patients consisted of 105 women and 194 men, and their ages range between 40 and 95 years old. All 299 patients had left ventricular systolic dysfunction and had previous heart failures that put them in classes III or IV of New York Heart Association classification of the stages of heart failure.


2.	Problem Statement
People with cardiovascular disease or who are at high cardiovascular risk (due to the presence of one or more risk factors such as hypertension, diabetes, hyperlipidemia or already established disease) need early detection and management wherein a machine learning model can be of great help.


3.	Data set description
This is a Kaggle dataset. 
https://www.kaggle.com/andrewmvd/heart-failure-clinical-data
The Heart failure is a common event caused by CVDs and this dataset contains 13 features that can be used to predict mortality by heart failure.
It contains 13 Columns and 299 Rows.  
The short description of each attribute is below:

* Death_Event: Patient Deceased (Boolean)
* Age: Age in Years 
* Anaemia: Decrease of red blood cells or haemoglobin (Boolean)
* Creatinine_Phosphokinase: Level of the CPK enzyme in the blood (mcg/L)
* Diabetes: If the patient has diabetes (Boolean)
* Ejection-fraction: Percentage of blood leaving the heart (percentage)
* High-blood-pressure: If the patient has hypertension (Boolean)
* Platelets: Platelets in the blood (kiloplatelets/mL)
* Serum-creatinine: Level of serum creatinine in the blood (mg/dL)
* Serum-sodium: Level of serum sodium in the blood (mEq/L)
* Sex : Woman or man (binary)
* Smoking: If the patient smokes or not (Boolean)
* Time: Follow-up period (days)

4.	Data preparation

Before dive into developing ML model, we first need to analyze the data. Data preparation will take into 4 steps. The first is clean data.  Second is data validation. Third is data visualization, and last is data partition.  

This step is reviewing the overall data. Initial assessment of the data to identify which columns are Quantitative, Categorical or Qualitative.

5. Data Cleaning:

* There are no missing values in the data.
Using hfp.isna.sum()

6. Data Validation:
* We have checked for the balance of the data based on the output variable that is 0 and 1
* Identified the type of variables based on the number of unique values in column using [.]append and [.]unique

7. Visualizing The Data :

* Bar Graph
* Pie Chart
* Scatter Plot
* Box PLot
* Corelation matrix
* Histogram Distribution


8. Partitioning and Scaling the data : 
* We have split the data into training set (80%) and validation set (20%).


