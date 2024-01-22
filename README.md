# Gun Violence Data Analysis
The Institute for Firearm Injury Prevention states that gun violence is an epidemic in the United States, and there have been year after year increases in gun violence-related deaths since the early and mid-2000s.
# Objective
There's currently a lack of significant and easily accessible amounts of detailed data on gun violence in the United States. This project aims to change that; there are more than 260k gun violence incidents recorded in the dataset, with detailed information about each incident available. The hope is that this will make it easier for data scientists and statisticians to study gun violence and make predictions about future trends. The dataset contains data for all recorded gun violence incidents in the US between January 2013 and March 2018, inclusive.

The goal of the project was to explore trends in the data and find any relationships between what causes gun-related incidents. This was done with exploratory visual analysis, linear regression, and k-mean clustering. Other analysis techniques used included geospatial analysis and time-series analysis.

The initial hypotheses formed during the initial exploratory analysis found that total incidents and male participants had a strong correlation. There was not a significantly high correlation when a correlation heat map was utilized, but after performing linear regression and cluster analysis, there was a clearer relationship.
# Data
The dataset is the Gun Violence Data from 2013-2018, by James Ko via [Kaggle](https://www.kaggle.com/datasets/jameslko/gun-violence-data/data).

The data contains more than 260,000 incidents of gun violence incidents. The dataset contains information regarding each unique incidents' id, the date is occured, geographic location, the number of people involved, killed, and injured, gun information, age groups, genders, sources, and notes. 
# Tools
* Python libraries used in this project include:

  * pandas
  * NumPy
  * seaborn
  * matplotlib
  * Folium
  * scikit-learn

* Scripts were created in Jupyter.

* The final presentation was created in Tableau and can be viewed [here](https://public.tableau.com/app/profile/nupur.parikh/viz/6_7GunViolence/Story?publish=yes).
# Folder Structure
* 01 Project Management: Contains the project brief, a document containing an overview of the CareerFoundry course and project.
* 02 Data: Contains the original datasets, versions I cleaned, and subsets data used in this project.
* 03 Scripts: A folder with all of the Jupyter scripts created for analysis and visualizations.
* 04 Analysis: This contains the visuals created for the project, as well as data sourcing documentation, full correlation matrixes, and the time analysis data preprocessing.

