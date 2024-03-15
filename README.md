# Crime-data-prediction-using-pyspark

**PROJECT OVERVIEW**

The Big Data Analytics project focusing on Crime Prediction in Syracuse is a comprehensive endeavor aimed at harnessing large-scale data to forecast and analyze crime patterns within the city. The primary objective is to employ advanced data analytics techniques on diverse datasets encompassing historical crime records, socio-economic indicators, demographic information, weather patterns, and geographical features. The project will be initiated with meticulous data collection and preparation, ensuring the cleanliness and compatibility of the datasets for subsequent analysis and Exploratory Data Analysis (EDA). 

Feature engineering techniques will be implemented to identify crucial factors influencing crime rates, which will be used to augment predictive models. Machine learning algorithms such as Random Forest, Decision Trees, Gradient Boosted Trees are being used in this project to develop robust models capable of predicting future crime occurrences in Syracuse. Ethical considerations regarding privacy, bias mitigation, and fairness in predictions will be paramount throughout the project's lifecycle. The goal is to provide actionable insights for law enforcement to proactively address and reduce crime rates, thereby enhancing public safety in Syracuse.

**DATASET DESCRIPTION**

The Syracuse crime data is obtained from the City of Syracuse. The data is for 5 years from 2019 to 2023. This crime data is divided into Part 1 and Part 2 offense. Part 1 contains Criminal Homicide, Forcible rape, Robbery, Aggravated assault, Burglary, Larceny-theft and Motor Vehicle Theft whereas Part 2 includes all the offenses – Kidnapping, Extorsion, Simple Assault, Stolen Property, Bribery, Loitering etc. The following points gives the number of columns and their description.

1. **ObjectID:** Unique ID to each record
2. **DateEnd:** Data that the crime was reported. It could have happened earlier. This is the format of DD-MON-YY(Ex. 01-Jan-22)
3. **Time Start and time end:** Listed in military time (2400) - Burglaries and larcenies are often a time frame.
4. **Address:** Where the crime occurred. All addresses are in the 100's beacuse the Syracuse Police Department allows privacy for residents and only lists the block number
5. **Code defined:** Offense names are listed as crime categories group for ease of understanding. There are have been many other offenses also, but the one displayed is the highest Unified Crime Reporting (UCR) category.
6. **Arrest:** Means that there was an arrest, but not necessarily for that crime.
7. **Larceny Code:** Indicates the type of larceny (Example: Building or from Motor Vehicle).

The 5 years (2019-2023) crime data is combined into a dataset, including Part 1 and Part 2 crime data. Upon combining, we got 63,449 records of the crime events and 11 variables. 


