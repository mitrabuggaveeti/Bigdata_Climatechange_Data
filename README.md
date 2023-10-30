# BDA_Project_13

# Team
- Mitra Buggaveeti
- Sai Kiran Reddy Bokka
- Deeksha Reddy Ganta
- Lahari Prathapagiri
- Lakshmi Prasanna Adeboyena

## Communication plan 

Communication channels: Discord for daily team conversation and syncing. We will be using email for formal way of communication.

Communication frequency: 20 mins long standup call on zoom for every altenate day to check the progress of the project

Work divison : Tasks are divided among team members efficiently any work overload can be brought to team notice and disucss to reslove them.

Meeting agendas: Update on tasks assigned to each individual, assigning new tasks and planning future developments, discussing issues faced and collectively working to fix them.

## Project artifact repository:
Git Link : [https://github.com/mitrabuggaveeti/BDA_Project_13](https://github.com/mitrabuggaveeti/BDA_Project_13)


# First Choice :
Kaggle : [https://www.kaggle.com/datasets/berkeleyearth/climate-change-earth-surface-temperature-data](https://www.kaggle.com/datasets/berkeleyearth/climate-change-earth-surface-temperature-data)
## Selection of data to analyze

We have selected data on climate change from Kaggle that helps us understand Earth's surface temperature changes Earth's surface temperature throughout time. The temperature has changed significantly between the early 1990s and the present. We will use the Berkeley Earth data source, which has 1.6 billion temperature reports from 16 pre-existing archives in a properly structured format. This dataset is important for obtaining information on the average land temperature as well as data combining average land and ocean temperatures.

Berkeley Earth data: https://berkeleyearth.org/data/

## Business Problem or Opportunity

The chosen dataset can be used to address various business problems and opportunities such as:
1. Climate change research: The dataset can be used to identify long-term trends in temperature and investigate the impact of climate change on different regions around the world. This could be useful for businesses focused on climate change mitigation and adaptation, as well as for policymakers and advocacy groups.

2. Sustainable development: Businesses can use this dataset to inform sustainable development strategies, particularly for businesses operating in industries that are high emitters of greenhouse gases. By understanding how temperature is changing in different regions and how it may impact business operations, companies can identify opportunities for innovation and investment in sustainable technologies and practices.

3. Risk assessment: The dataset can also be used for risk assessment and disaster planning. By analyzing temperature patterns, businesses can identify regions that are most at risk for extreme weather events, such as heatwaves, droughts, or flooding, and develop contingency plans to mitigate these risks.

## Domain Knowledge

1. Data visualization: This form for conveying knowledge and conclusions from data makes utilizes visual aids like graphs, charts, and maps. In addition to making the data easier to comprehend and analyze, this approach may be employed to find hyperlinks, trends, and patterns in the data.
2. Greenhouse effect: The greenhouse effect is an occurrence of nature that occurs when certain gases, such as carbon dioxide and water vapor, in the Earth's atmosphere take in sunlight and prevent it from exiting into orbit.
3. Climate science: The study of the Earth's climate system, including the factors that affect it, the internal processes that take location, and the patterns and trends that emerge through time. 
4. Temperature anomalies: An temperature aberration is a deviation from the usual deviation for an area and a time period. Abnormalities are utilized for recognizing patterns and trends in temperature data and also monitoring temperature variations over time.
5. Data cleaning and preprocessing: Earlier, for collecting data, people utilized mercury thermometers, therefore any changes in the visit duration have an impact on the measurements Preparing information for analysis involves finding and fixing problems including missing values, outliers, and contradictory or incorrect information. 

## Research Objectives and Question(s) (what you are trying to describe or predict with the data)
The agenda of our team is to identifying the strategies that could help us define the solutions to the below questions using suitable visualisations as part of our research work. By analysis the chosen dataset we would further investigate the following questions: 1)In correlation to changes in temperature, are there population changes in animals or plants?2)How do temperature variations over different periods, including daily or seasonal variations, relate to long-term changes in average temperature?3)Between changes in temperature and differences in people's health, are there any relationships?

# Second Choice : 
Kaggle : [https://www.kaggle.com/datasets/START-UMD/gtd](https://www.kaggle.com/datasets/START-UMD/gtd)
## Selection of data to analyze

The purpose of the analysis of this dataset is because it contains detailed information on terrorist attacks worldwide, including the date and location of the attack, the weapons used, the target of the attack, and the number of casualties. This dataset can be used to analyze patterns and trends in terrorist activity over time and across different regions of the world.It can also be used to investigate the components—such as political unpredictability, religious extremism, and economic situations—that affect the severity and frequency of terrorist acts.
## Business Problem or Opportunity

The dataset on global terrorism from the Global Terrorism Database (GTD) can be leveraged for various business problems and opportunities such as:
1. Risk assessment: The dataset can be used for risk assessment purposes by businesses operating in regions that are prone to terrorist attacks. By analyzing the historical data on terrorist incidents, businesses can identify patterns and trends that could help them mitigate potential risks and develop contingency plans.
2. Insurance and risk management: Insurance companies can use this dataset to inform their underwriting and risk management practices. By analyzing the historical data on terrorist attacks, insurers can better understand the likelihood and severity of potential losses, and adjust their premiums and coverage accordingly.
3. Security and defense: The dataset can also be used by businesses that provide security and defense solutions. By analyzing the data on terrorist attacks, these companies can identify patterns and trends that could inform their product development and service offerings.

## Domain Knowledge:

Global terrorism database is provided by university of Maryland. It is an open-source database of worldwide terrorist attacks which have information over 200k terrorist incidents from the year 1970 to 2017. The dataset have the required information of the date, location, type, and severity of each attack, as well as the information on the perpetrators, the targets, and the weapons used. The data also includes additional variables such as the number of injuries, and damage to the property caused by the attack.

The primary purpose of this Dataset is that it can be helpful and used for research and analysis of terrorism trends, patterns and  to make better decisions related to counter terrorism efforts. Domain knowledge required for this dataset include focus on terrorism studies and criminology. Researchers and policy makers can use this dataset to find out the patterns and trends in the activities of terrorists to find out the areas with most effected terrorism and develop strategies for preventing the terrorist attacks. It also helps in building predictive models that helps in understadning of the terrorist attacks and their causes.

##  Research Objectives and Question(s) (what you are trying to describe or predict with the data)

The agenda of our team is to identify the strategies that could help us define the solutions to the below questions using suitable visualizations as part of our research work. By analysis the chosen dataset we would further investigate the following questions:
1. What are the most common types of terrorist attacks worldwide, and how have they changed over time?2. To what extent does political instability or conflict contribute to the incidence of terrorist attacks, and vice versa? 3. How have terrorist attacks affected civilian populations in terms of deaths, injuries, displacement, and psychological trauma?


# Deliverable 2

# Data understanding

## a) Exploratory Data Analysis

Exploratory Data Analysis was done through AWS Sagemaker. The link for the file is pasted here: https://github.com/mitrabuggaveeti/BDA_Project_13/blob/deliverable2/Deliverable_2.ipynb

## b) Dashboard
Dashboard instances were created using AWS Quicksight. These dashboards are used for presenting results using visualizations such as representing graphs like Pie Chart and Bar Chart for evaluating the research objectives. Also several different plots have been created using Scikit learn library from python and Amazon SageMaker notebook (AWS). Some of the graphs for AWS QuickSight are presented in the PDF, the link for the same is pasted below:

https://github.com/mitrabuggaveeti/BDA_Project_13/blob/deliverable2/dashboard.pdf

## c) Documentation

https://github.com/mitrabuggaveeti/BDA_Project_13/blob/deliverable2/Deliverable_2.pdf
# Data Preparation
As part of the data preparation process, all null values are first checked since they limit the ability of the machine learning algorithm to learn. Each column's null values are examined, and all of them are replaced with mean. After completing the above step, the data on each column was carefully observed and the Standard deviation, Mean, Maximum, and other statistical distributions are examined to determine how evenly the data is distributed.

# Deliverable 3

# Analytics, Machine Learning
This is a sizable dataset that includes historical global temperatures. This data set is frequently used in machine learning and analytics applications for research on climate change, weather forecasting, and several other relevant topics.
To learn more about the properties of the data, such as patterns, trends, and anomalies in temperature data, exploratory data analysis, or EDA, can be utilized.
Data analysis can be used to find links and relationships between temperature and other factors like as time, place, and dioxide emissions.
The use of data visualization tools can be used to produce interactive maps and charts that display temperature patterns over time and in various geographic locations.
This dataset may be utilized to teach algorithms that use machine learning and develop models of prediction that predict upcoming variations in temperature based on past information.
Future temperature can be forecast via regression models, particularly the use of linear regression and time-series data models for forecasting.
In addition to classifying and identifying locations that are most vulnerable to climate change, algorithms like clustering and classification can also be used to group comparable geographic areas based on temperature fluctuations.

# Evaluation and Optimization
Time series analysis is more appropriate for datasets that exhibit temporal patterns and trends, such as climate change data. Time series analysis is used to analyze data that changes over time, and involves techniques that take into account the temporal ordering of data points.
Linear regression, on the other hand, is a statistical method used to model the relationship between two or more variables, where one variable is considered the dependent variable and the others are independent variables. It assumes that there is a linear relationship between the independent variables and the dependent variable.
In the case of climate change data, temperature measurements are collected at regular intervals over time, and the data is organized in a time series format. Linear regression assumes that the data points are independent of each other, which is not true for time series data where the observations are typically correlated with each other over time.

# Results
The results for some of the questions raised are discussed based upon proper data, performing pre-processing operations on data and including all the required parameters.

[https://github.com/mitrabuggaveeti/BDA_Project_13/blob/deliverable3/Deliverable_3.ipynb](https://github.com/mitrabuggaveeti/BDA_Project_13/blob/deliverable3/Deliverable_3.ipynb)
# Future Work, Comments

## What was unique about the data? 
The dataset contains temperature data from thousands of cities and regions worldwide, dating back to 1750. This long-term global coverage is valuable for researchers studying climate patterns and trends over time. The temperature data in the dataset has been carefully cleaned and quality-checked to ensure accuracy and consistency. This helps to reduce errors and biases that can arise from data collection and processing. In addition to temperature readings, the dataset includes other variables such as latitude, longitude, and country/region information. This allows researchers to analyze the data in more detail and consider other factors that may impact temperature patterns.

## Did you have to deal with imbalance? What data cleaning did you do? Outlier treatment? Imputation?
Spatial Imbalance: The spatial distribution of the dataset is not symmetrical, with some locations having more data than others. This may result in skewed temperature patterns, especially in areas where data is few. To resolve this, we can produce more thorough temperature records by using spatial interpolation techniques to fill in the gaps left by missing data.
Temporal Imbalance: Additionally, there is a temporal imbalance in the collection, with more current data having better spatial and temporal resolution than older data. This can make it difficult to compare long-term temperature trends and gauge how much the climate is changing. We can address this by using statistical techniques that take into account variations in data coverage and quality over time.


## Did you create any new additional features / variables?
There weren't any new variables, in the dataset, the values are displayed till 2013 (September). So we have enhanced it so that we can predict the temperature values for the next few months (October, and November)

## What was the process you used for evaluation? What was the best result?
The RMSE values and the percentage error are the evaluation measures for the model we employed. A lower value denotes greater accuracy, and it provides a measure of the average magnitude of the errors between the anticipated and actual values. The RMSE of our model is 14.34.

## Is there Bias in your work? What were the problems you faced? How did you solve them?
During the project creation there were several problems encountered. There was a problem with a dataset which was chosen. It had to be pre-processed to remove the null values present in the columns of the dataset. Also, the dataset chosen is a Kaggle dataset and setting up the Kaggle dataset on AWS services was a challenge. Also, there were issues while setting up AWS Glue, AWS Athena. Additionally, some of the data operations could not be set up the AWS services initially due to credits.

## What future work would you like to do?
The first step to improving your climate change model is to collect more data. This can include historical climate data, satellite imagery, or any other relevant data sources.

## Instructions for individuals that may want to use your work
The dataset is chosen from Kaggle and anyone who wishes to use our work needs to setup the AWS environment with appropriate credentials. Also, it might ask for charges which needs to be paid before using AWS services. Also, the user must load the Kaggle data into AWS and then set up the AWS SageMAker to run the python notebook consisting of code. All the other requirements for the procedure is mentioned within the github repository.

# Implementation of Work / Presentation Video
Video Link : [https://drive.google.com/file/d/1Nfw-EatrSatFeSFpap7Yc54QGzxK_WLY/view](https://drive.google.com/file/d/1Nfw-EatrSatFeSFpap7Yc54QGzxK_WLY/view)

PPT Link : [https://github.com/mitrabuggaveeti/BDA_Project_13/blob/deliverable3/Team13_BigdataFinalPPT.pptx](https://github.com/mitrabuggaveeti/BDA_Project_13/blob/deliverable3/Team13_BigdataFinalPPT.pptx)

Deliverable 3 Doc : [https://github.com/mitrabuggaveeti/BDA_Project_13/blob/deliverable3/FinalProjectDocumentation.pdf](https://github.com/mitrabuggaveeti/BDA_Project_13/blob/deliverable3/FinalProjectDocumentation.pdf)