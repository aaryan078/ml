

![alt tag](https://raw.githubusercontent.com/mandliya/ml/master/utils/quote.jpg)

<!-- streaktable start -->
| Current Status|     Stats     |
| :------------: | :----------: |
| Total Machine Learning Projects | 20 |
| Current Daily Streak | 23 |
| Last Streak Dates | 06/23/2019 - 07/02/2019 |
| Current Streak Dates | 04/13/2020 - 05/05/2020 |
| Daily Log Progress| [daily_log.md](daily_log.md)|
<!-- streaktable end -->

- [Machine Learning and Deep Learning Projects](#Machine-Learning-and-Deep-Learning-Projects)
  - [Hands on Machine Learning](#Hands-on-Machine-Learning)
  - [Data Wrangling](#Data-Wrangling)
  - [SQL](#SQL)
  - [Time Series](#Time-Series)
  
## Machine Learning and Deep Learning Projects

<!-- Hands on Machine Learning start -->
### Hands on Machine Learning
|No. | Project | Description | Notebook | Notes |
|:--:| :------:| :--------- | :------: | :---: |
|1.| The Machine Learning Landscape | The basics of machine learning terminology, types and challenges | To be updated | Source: [Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow](https://learning.oreilly.com/library/view/hands-on-machine-learning/9781492032632/) |
|2.| End to End Machine Learning Project | In this project we will go through an example project end to end, pretending to be a recently hired data scientist in a real estate company.Here are the main steps you will go through: <ol><li>Look at the big picture.</li> <li>Get the data.</li><li>Discover and visualize the data to gain insights.</li><li>Prepare the data for Machine Learning algorithms.</li><li>Select a model and train it.</li><li>Fine-tune your model.</li><li>Present your solution.</li><li>Launch, monitor, and maintain your system</li></ol>|[End_to_end_machine_learning_project.ipynb](hands_on_machine_learning/2/End_to_end_machine_learning_project.ipynb)| Source: [Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow](https://learning.oreilly.com/library/view/hands-on-machine-learning/9781492032632/) |
|3.| Classification | In this project we will go through concepts of Classification by building a digit classifier using MNIST dataset. We will learn concepts of performance measurement for classfication (e.g. Confusion Matrix, Precision and Recall, The ROC curve etc) |[Classification.ipynb](hands_on_machine_learning/3/Classification.ipynb)| Source: [Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow](https://learning.oreilly.com/library/view/hands-on-machine-learning/9781492032632/) |
<!-- Hands on Machine Learning end -->

<!--- Data Wrangling start --->
### Data Wrangling
|No. | Project | Description | Notebook | Notes |
|:--:| :------:| :--------- | :------: | :---: |
|1.| **Data Wrangling using Quandl Api** |  We retrieve financial data of a stock using quandl api and do basic data analysis using plain vanilla python. | [data_wrangling_using_api.ipynb](data_wrangling/api/data_wrangling_using_api.ipynb) | - |
|2.|**Pandas from scratch**| This notebook takes an in-depth look at Pandas, the swiss army knife for data analysis.<ul><li> Exploring pandas data-structures (Series and DataFrame) in detail</li></ul><ul><li>We fetch Google's stock data and perform various data analysis on it which includes reading data from various sources, filter, visualize, and apply statistics on top of it.</li></ul>|[pandas_handson.ipynb](data_wrangling/pandas/pandas_handson.ipynb)|-|
|3.|**Never on a Friday or Turning Tuesday**| A simple exploratory data analysis of stock market data to determine if Tuesdays are *Turning Tuesdays*.| [never_on_a_friday.ipynb](data_wrangling/pandas/never_on_a_friday.ipynb)|-|
|4.|**Handling missing values in pandas**| This notebook provides a good overview of how pandas handle missing values and explores functions it provides to handle missing data.| [handling_missing_data.ipynb](data_wrangling/pandas/handling_missing_data.ipynb)|
|5.|**Mini-Project: Data Wrangling and Transformation with Pandas**| In this mini-project we explore multiple datasets (movie, cast, release) to do an extensive data exploration, analysis and visualtion. | [data_wrangling_transformations_movie.ipynb](data_wrangling/pandas/data_wrangling_transformations_movie.ipynb)| - |
|6.|**Data Wrangling with JSON**| This notebook helps understanding Panda's JSON functionality. It also has some challenges which require some fun data-wrangling (e.g. missing values etc).| [Mini_Project_Wrangling_Json_Exercise.ipynb](data_wrangling/json/Mini_Project_Wrangling_Json_Exercise.ipynb)|-|
|7.|**67 years of Lego**| An exploratory data analysis of fun dataset on every single lego block that has ever been built. Lot of good pandas aggregation| [lego_analysis.ipynb](data_wrangling/exploring_67_years_of_lego/lego_analysis.ipynb)| Source: [Datacamp](https://projects.datacamp.com/projects/10)|
|8.|**Explore the crypto-currency Bitcoin market**| In this notebook we do an in-depth analysis of crypto-currency market cap analysis, and visualize top gainers and losers in a fun way! This analysis tells you how risky or profitable this market is currently.|[cryptocurrency_analysis.ipynb](data_wrangling/exploring_the_bitcoin_crypto_market/cryptocurrency_analysis.ipynb)|-|
|9.|**Discovery of Handwashing**| This notebook tells the story of discovery of handwashing, and how Dr. Ignaz Semmelweis brought down the deaths of women who just gave birth caused *childbed* fever .|[discovery_of_handwashing.ipynb](data_wrangling/discovery_of_handwashing/discovery_of_handwashing.ipynb)|-|
|10.|**Exploring evaluation of linux**| This notebook does exploratory data analysis on Linux git commit history. A good lot of pandas!|[exploring_the_evaluation_of_linux.ipynb](data_wrangling\exploring_the_evaluation_of_linux\exploring_the_evaluation_of_linux.ipynb)|-|
|11.|**The github history of Scala Language**| This notebook explore the pull requests of Scala language project on github and does interesting analysis of pull requests based on authors, year, months etc|[EDA_scala_history.ipynb](data_wrangling/the_github_history_of_the_scala_language/EDA_scala_history.ipynb)|Source: [Datacamp](https://projects.datacamp.com/projects/163)|
|12.|**Who is drunk and when in Ames, Iowa**|Ames, Iowa is home to Iowa State University. Ames has had its fair share of alcohol-related incidents. (For example, Google 'VEISHEA riots 2014'). In this notebook, we analyze and visualize some breath alcohol test data from Ames that is published by the State of Iowa.|[EDA_Ames_iowa_drinking.ipynb](data_wrangling/who_is_drunk_and_when_in_Ames_Iowa/EDA_Ames_iowa_drinking.ipynb)|Source: [Datacamp](https://projects.datacamp.com/projects/475)|
|13.|**Working with strings in Pandas**|In this notebooks, we explore string manipulation and easy analysis string operations on pandas.|[Working_With_Strings.ipynb](data_wrangling/pandas/Working_With_Strings.ipynb)|Source:[Python Data Science Handbook](https://nbviewer.jupyter.org/github/jakevdp/PythonDataScienceHandbook/blob/master/notebooks/03.10-Working-With-Strings.ipynb)|
|14.|**A New Era of Data Analysis in Baseball**| In this notebook, we will use Statcast data to compare the home runs of two of baseball's brightest (and largest) stars, Aaron Judge (6'7") and Giancarlo Stanton (6'6"), both of whom now play for the New York Yankees.|[data_analysis_in_pandas.ipynb](data_wrangling/a_new_era_of_data_analysis_in_baseball/data_analysis_in_baseball.ipynb)| source: [Datacamp](https://www.datacamp.com/projects/250)|
|15.|**Name Game: Gender prediction using sound**| A fun analysis of NYT's authors dataset of Children’s Picture Books. We analyze the gender distribution of authors to see if there have been changes over years based on author's names and how they sound using nysiis algorithm.|[name_game.ipynb](data_wrangling/name_game_gender_prediction_using_sound/name_game.ipynb) | source: [Datacamp](https://www.datacamp.com/projects/97) |
<!--- Data Wrangling end --->

<!--- SQL start --->
### SQL
|No. | Project | Description | Notebook | Notes |
|:--:| :------:| :--------- | :------: | :---: |
|1.|**SQL Spark at scale**| In this notebook, we work through a series of exercises using Spark SQL and familiarize ourselves with how SQL works with spark.|[Mini_Project_SQL_with_Spark.ipynb](sql/sql_with_spark/Mini_Project_SQL_with_Spark.ipynb)| One of the ways to use this notebook is to try [domino trial](https://trial.dominodatalab.com), create a pyspark workspace and launch this [notebook](https://trial.dominodatalab.com/u/mandliya/springboard-mini-projects/view/aic-5_6_6-sql-at-scale-with-spark-mini-project/Mini_Project_SQL_with_Spark.ipynb), as we need a pyspark environment.|
<!--- SQL end --->

<!--- Time Series start --->
### Time Series
|No. | Project | Description | Notebook | Notes |
|:--:| :------:| :--------- | :------: | :---: |
|1.|**Working with time series in python**|This notebook teaches basics of time series analysis. We take a fun dataset of Seattle's Fremont Bridge bicycle data and Google's stock data to visualize, understand and work through dates and time in Python|[Time_series_basics.ipynb](time_series/Time_series_basics.ipynb).|Data is fetched directly from web.|
<!--- Time Series end --->

### Kaggle
|No. | Project | Description | Notebook | Notes |
|:--:| :------:| :--------- | :------: | :---: |
|1.|**Titanic: Machine Learning from Disaster**|This notebook has the walk-through of Kaggle's iconic Titanic problem, learning from the best kernels there. Also this a solution of exercise 2 of chapter 3 of [Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow](https://learning.oreilly.com/library/view/hands-on-machine-learning/9781492032632/)|[titanic_competition.ipynb](kaggle/titanic_competition.ipynb).|This notebook is downloaded from Kaggle's kernel.|