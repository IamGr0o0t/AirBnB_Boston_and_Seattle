# Boston and Seattle AirBnB Udacity Project


### Table of content
---------------
* #####[Motivation](https://github.com/IamGr0o0t/AirBnB_Boston_and_Seattle#motivation)
* #####[Installation](https://github.com/IamGr0o0t/AirBnB_Boston_and_Seattle#installation)
* #####[Software versions](https://github.com/IamGr0o0t/AirBnB_Boston_and_Seattle#software-versions)
* #####[File descriptions](https://github.com/IamGr0o0t/AirBnB_Boston_and_Seattle#file-Descriptions)


### Motivation
---------------
I myself use AirBnB quite often. It was really important for me to come with some practical question that can be answered using data provided by AirBnB

This project tries to answer three major questions regarding AirBnB data within these two cities.
1. What are the key differences between Boston and Seattle AirbBnB markets?
2. How AirBnB prices are affected by the seasonality?
3. What is the best predictor of price for Boston and Seattle AirBnB? How well can we model it?


### Installation
---------------
All packages i have used were installed via most recent conda distribution.
```bash
conda 4.8.2
```
If you wish to install some other packages please feel free and do it with conda-forge.
```bash
conda install -c conda-forge (Insert Package Here)
```
### Software versions
---------------
* Anaconda version == 4.8.2
* Python version == 3.7.6
* pandas version == 1.0.1
* Numpy version == 1.18.1
* matplotlib version == 3.1.3
* seaborn version == 0.10.0
* sklearn version == 0.22.1

### File descriptions
---------------
There are 4 files related to data provided by AirBnB.

* All python code is well documented in my ipython notebook AirBnB_Boston_and_Seattle_Project.ipynb. Where you can find project following the CRISP-DM
  pattern in order to find meaningful information stored in our csv files.
* seattle_listings.csv and boston_listings.csv files contain data related to the seattle AirBnB market with included columns like: price, cleaning fee, 
  zipcode, neighbourhood, city, review scores, review messages and many more. I have used these two files to answer questions 1 and 3.
* seattle_calendar.csv and boston_callendar.csv contain information related to airbnb prices fee on specific date. I have used these files to answer 
  question 2.

### Results and Findings
---------------
* From my EDA (Exploratory Data Analysis) I managed to present clear key differences between the Boston and Seattle AirBnB markets. Results show us 
  higher on average AirBnB price in Boston than Seattle, but it is Seattle that has higher AirBnB rental volume. 
* Findings also displayed clear seasonality patter in average AirBnB prices in both cities with Summer being more expensive than any other season and 
  Winter being the cheapest.
* There are clear price fluctuations close to the big event dates (St Patrick's Parade, Boston Marathon)
* Lastly with very basic ML model I was able to find the best predictors of price in both cities with importance over neighbourhood and property types. 
  In another words, neighborhood has large impact on price of your next AirBnB.

### Licensing, Authors, Acknowledgements
---------------
The Seattle data can be found [here](https://www.kaggle.com/airbnb/seattle/data).
The Boston data can be found [here](https://www.kaggle.com/airbnb/boston).
This datasets are part of Airbnb Inside, and the original source can be found [here](http://insideairbnb.com/get-the-data.html).
Thank you to [Udacity.com](https://classroom.udacity.com) for an amazing Data Science course.
