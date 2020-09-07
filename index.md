# Portfolio

I am a researcher with a big interest in how data shape our lives.  At the moment, I work in the field of computational biology and biophysics, which is powered by statistics analysis, machine-learning approaches, and deterministic algorithms. I am experienced in proteomics, databases, machine learning algorithms, neural networks,data analysis pipelines and data visualization using Python, R and Tableau. I have a significant interest in fields such as energy and business sector, where the data-driven products can enhance the existing decision-making. I am motivated by digging into data. Give me a dataset and questions, I'm eager to figure out what's driving the numbers. I love to solve problems with code and self-learn new things. I particularly fancy communicating through effective data visualizations such as dashboards.

Outside the office, I play the piano, compose music, cook, photograph nature, and try to master new juggling tricks.  I really enjoy socializing and discuss broad topics with people. 

# Projects 

  - [Diabetes Detection](#diabetes-detection)
  - [Classification of Bioactivity of Drugs](#classification-of-bioactivity-of-drugs)
  - [Sequence Based Function Prediction](#sequence-based-function-prediction)
  - [Deep Channel Predictor](#deep-channel-predictor)
  - [Time series Forecasting of Power Consumption](#timeseries-forecasting-of-power-consumption)
  - [Wind Turbine Condition Monitoring with Machine Learning](#conditions-monitoring-ml)


## [Diabetes Detection](http://github.com/Vikasdubey0551/Diabetes-classification-Machine-learning)

The aim of this project is to detect diabetes based on medical conditions as features. The dataset contains 8 medical conditions features (X) : Pregnancies, Glucose, BloodPressure, SkinThickness, Insulin, BMI, DiabetesPedigreeFunction, Age. Outcome is a binary target (y) label.  I have used 8 different machine learning classifiers to diabetes classfication. **Logistic regression** and **Neural Netowrks** seems to provide the best performance based on 10-fold cross validation of the dataset. Logistic regression achieves a higher F1-score as well, which is better metric for model evalution. From the confusion matricies, **decision tree** has the highest success in detecting the diabetes. Feature selection suggests the **Glucose** is the most crucial factor for the successful prediction of diabetes.

<a  href="http://github.com/Vikasdubey0551/Diabetes-classification-Machine-learning"> <img src="images/diabetes.png?raw=true" alt="Click to view the project"> </a>

---

## [Classification of Bioactivity of Drugs](http://github.com/Vikasdubey0551/ML-drug-effectiveness-abl-kinase)

This project deals with classifying the bioactivity of the drug based on Lipinski molecular descriptors. The target protein is Tyrosine ABL kinase. Mutations in the ABL-kinase
are associated with chronic myelogenous leukemia (CML). Data is obtained from the ChEMBL database. The feature engineering (i.e. Lipinski molecular descriptors) was performed f
rom the smiles obtained the ChEMBL Database. The project presents an extensive exploratory data analysis (EDA) and general methodology to find active drugs for a target protein
.

<a  href="http://github.com/Vikasdubey0551/ML-drug-effectiveness-abl-kinase"> <img src="images/bioactivity.png?raw=true" alt="Click to view the project"> </a>


---

## [Sequence Based Function Prediction](http://github.com/Vikasdubey0551/Sequential-analysis-ANN)

This project was based on classification of protein function based on their sequences. The protein function which the project focusses is the ATP binding. Data scraping was performed on several protein sequences and their function from biological databases mainly Unitprot. The sequence of the protein were augmented after 500 residues. The sequences, which had lower length were artifically padded with '_'. It is a binary classification problem and  I used **Artifical Neural Network (ANN)** to classify the protein function. After the hyperparameter tuning,  I obtained an accuracy score of  95% and F1-macro score of 93%.  

<a  href="http://github.com/Vikasdubey0551/Sequential-analysis-ANN"> <img src="images/sequence.png?raw=true" alt="Click to view the project"> </a>

---

## [Deep Channel Predictor](https://github.com/Vikasdubey0551/Deep-channel-predictor)

In this problem, the aim was to identify the number of channels open at each time point with time series electrophysiology data. Ion channels encode learning and memory, help f
ight infections, enable pain signals, and stimulate muscle contraction. If scientists could better study ion channels, which may be possible with the aid of machine learning, i
t could have a far-reaching impact.
My approach was to perform a sequence prediction using the **Bidirectional-LSTM** model along with undersampling and class reweighing. The model gave an F1-score of 94.0%.

<a  href="http://github.com/Vikasdubey0551/Deep-channel-predictor"> <img src="images/channel.png?raw=true" alt="Click to view the project"> </a>


---

## [Time Series Forecasting of Power Consumption](https://github.com/Vikasdubey0551/EDA_and_Timeseries-forecasting_power_consumption)

The data is the measurements of electric power consumption in one household with a one-minute sampling rate over a period of almost 4 years. The aim the project to perform the 
Timeseries forecasting and predictive analysis on Global_active_power variable, which represents the total power consumption.
Project contains :
- Exploratory Data Analysis (EDA) of timeseries fluctuations of Global_active_power variable in various time periods.
- Statistical test to check the normality of the data.
- Statistical test to check whether timeseries is stationary.
- Timeseries forecasting of Global_active_power variable with Recurrent Neural Networks (LSTM, GRU models)

<a  href="https://github.com/Vikasdubey0551/EDA_and_Timeseries-forecasting_power_consumption"> <img src="images/power.png?raw=true" alt="Click to view the project"> </a>


---

## [Wind Turbine Condition Monitoring with Machine Learning](https://github.com/Vikasdubey0551/Conditions-Monitoring-ML)

Ball bearings are a crucial component in any wind turbine. The condition of the ball bearings is monitored to ensure no unexpect
ed downtime of the turbine. The ball bearings consists of an outer ring, balls, cage and the inner ring. The ball bearing can be damaged in several ways, w
here the most common is a dent in either the inner or the outer ring.

Such a dent will cause distinct failure frequencies to appear as a function of the rotation speed of the shaft inside the ball b
earing. The **&quot;Ball Pass Frequency Outer&quot;**(BPFO) is the frequencies which the balls passes over a single dent in the
outer ring, this is typically specified as a multiple of rotation speed by the manufacturer.
 Every time the ball passes over a dent, it will cause a spike in vibration captured by the data acquisition equipment. This wil
l cause harmonics of the fault frequency(BPFO) to appear in the vibration data. 

In this project, I tackle the following tasks :  

- Find the difference between a good bearing and a faulty one? and identify the BPFO.
- Use machine learning techniques to distinguish the good bearing from the faulty one.

<a  href="https://github.com/Vikasdubey0551/Conditions-Monitoring-ML"> <img src="images/title2.png?raw=true" alt="Click to view the project"> </a>
