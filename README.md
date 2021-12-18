# Sarah--Portfolio

## Project1: Using Convolutional Neural Networks(CNN) to Detect a Smile Face.  
Neural Network has enabled machines to view the world as humans do, perceive it in a similar manner and use the knowledge for complicated tasks such as Image/Video recognition, Image Analysis/Classification and Natural Language Processing, etc. The Convolutional Neural Network is an advanced algorithm that widely used on image recognition and classification.   
In this study, I used CNN deep learning model to implement the image recognition in order to recognize a smile face from all kinds of countenances. There are more than 3000 images in the train dataset and more than 1200 images in the validation dataset. The aim of this project is to use Keras algorithm to build CNN models, train the model by the train dataset and evaluate the model by the validation dataset.[The details and python codes are recorded here](https://github.com/sarahzhao21/Using-Convolutional-Neural-Networks-CNN-to-Detect-a-Smile.git).     
Here is the structure of the CNN Networks in this study:   
![CNN structure of this project](https://github.com/sarahzhao21/Using-Convolutional-Neural-Networks-CNN-to-Detect-a-Smile/blob/963f2c0392bde663ba3c097eef7d9c1eea373afd/CNN%20Structure%20Catoon.png)

## Project2: Discover Patients’ Health Care Demand -- Drug Review Analysis by Natural Language Processing.
Since the COVID-19 pandemic in 2019, disease prevention and health improvement play more and more important roles in people’s life. With the rapid development of the pharmaceutical industry, large numbers of new medications have been developed and launched to market. Although the medication products were approved by FDA, it doesn’t mean the products are effective for each patient. Thus, it becomes very critical to understand the performance and related features of the drugs on users. Recent years, text and natural language analysis captures more attention as it can explore deeper information and bring more insight into the quantitative methodology, so it can be used to analyze users’ demand. 
![Top Bigrams of "Effective"](https://github.com/sarahzhao21/Discover-Patients-Health-Care-Demand----Drug-Review-Analysis-by-NLP/blob/a27d0443e6971095da414d41a79c3715d25b7222/top_effect_bigram5.png).   
 
This kind of study will be helpful for the pharmaceutical industry to better understand consumers’ demand and health needs, as well as patients’ responses for corresponding medications. The marketing managers or business leads will also care about these studies because understanding consumers’ needs, or intentions will be helpful for the marketing forecast.   
[Please click here for more details and python codes](https://github.com/sarahzhao21/Discover-Patients-Health-Care-Demand----Drug-Review-Analysis-by-NLP.git).  
[The summary is in my blog](https://xinyiz-13686.medium.com/discover-customers-health-care-demand-drug-review-analysis-by-natural-language-processing-8aaa5c9f2e57)

## Project3: Dependency Parsing by PyTorch Deep Learning Algorithm

Despite its seeming chaos, natural language has lots of structure. We’ve already seen some of this structure in part of speech tags and how the order of parts of speech are predictive of what kinds of words might come next (via their parts of speech).

In this project, I have got a deeper view of this structure by implementing a dependency parser. Dependency parsing identifies the syntactic relationship between word pairs to create a parse tree. I implemented the shift-reduce neural dependency parser of Chen and Manning [2014], which was one of the first neural network-based parser and is quite famous. And PyTorcfh is the library that has been used in this work. This project include 1)finish the implementation of the neural network and 2) fill in the main training loop that processes each batch of instances and does backprop and 3)Test the performance of the parser. 
[For details and python codes, please look at this.](https://github.com/sarahzhao21/Dependency_Parsing_PyTorch.git)   
![Accuracy of the two models](https://github.com/sarahzhao21/Dependency_Parsing_PyTorch/blob/8994369435e3964d70e056e4bc63edeec778c699/acc.png)![Loss of the two models](https://github.com/sarahzhao21/Dependency_Parsing_PyTorch/blob/8994369435e3964d70e056e4bc63edeec778c699/loss.png)


## Project4: Information retrieval by SQL and data visualization by Tableau.
Since the pandemic of COVID-19 in early 2019, people's lives were dramatically changed. The aim of this study is to figure out the most recent situations of death rate, infected rate and vaccination rate of all the countries in the world by SQL and to create easy to read visualizations on that by Tableau.
[Please click this for more details and codes.](https://github.com/sarahzhao21/COVID-19-study-by-SQL-and-visualization-by-Tableau.git)
![2021 COVID-19 Would Situation Dashboard](https://github.com/sarahzhao21/COVID-19-study-by-SQL-and-visualization-by-Tableau/blob/7fca289b8a60db0714d48cd2ca5bb14e80193d0e/COVID%20visualization%202021.png)

## Project5: Data Cleaning by postgreSQL.
Although some of the Python packages(pandas, numpy) is very powerful for data cleaning, SQL is also very useful and convinient for data cleaning. In this project, I will use postgreSQL to do the data organization, management and cleaning.   
[The codes and explainations are recorded here](https://github.com/sarahzhao21/data_organization_cleaning_by_SQL.git).  
The processes of data cleaning that have been used in this project include:  
1.Add new columns to a table and update those columns.   
2.Delete useless columns from a table.   
3.Extract different elements from timestamp or date records.     
4.Extract different elements from strings and rebuilt strings.   
5.Check if there are null values in a columns and repopulate the null values based on other columns or rows.   
6.Check if there are duplicate rows in the table and remove the duplicate rows.   
7.Change some kind of values to different values in a column.      

## Project6: A Network Based Music Recommendation System.
In this era of the Internet, popular music has also been greatly developed, with more and more ordinary musicians publishing their works on the Internet platform, and new popular musics born almost every day; besides, the taste of the audience is no longer limited to their favorite singers. Based on this background, we want to set up a music recommendation system based on the song network to help the audience to find more music that suits their taste.
[Please click here for more details and codes.](https://github.com/sarahzhao21/A-Recommendation-System-Based-on-Network.git)
![The network graph based on users history of a music website](https://github.com/sarahzhao21/A-Recommendation-System-Based-on-Network/blob/b5cfd422d5d336eca932ee38dec3c2172c4123fb/images/Recommendation%20graph.png)


## Project7: Trout Lake Temperature Prediction by Machine Learning Algorithm.
Lake monitoring provides important information for environment protection and pollution identification, such as temperature/thermal monitoring. In this Kaggle task, the instructor will provide thermal sensor data for multiple lakes and ask people to predict/estimate the temperature at a certain depth for certain lakes. The Lake Trout’s data during the period of Apr 20th, 2012 - Apr 19th, 2018 was provided. There will be multiple sensors at different depths, and what will be provided include: lake_id, time, depth and the corresponding temperature at this depth and time point.
|Date_Time	           |Water_Temp_C	|Depth_m|
|:-----------------:|:-----------:|:-------:|
|2012-04-20 00:00:00	 |5.257	        |1.5|
|2012-04-20 00:00:00	 |5.257        	|2.5|
|2012-04-20 00:00:00	 |5.257       	|3.5|
|2012-04-20 00:00:00	 |5.205	        |4.5|
|2012-04-20 00:00:00	 |5.205         |5.5|

### Task
Predicting/estimating the temperature of Trout Lake at depth 10.5 m during Apr 20th, 2018 - Apr 19th, 2019. 
Benchmark 1:  MSE < 0.065
Benchmark 2:  MSE < 0.032.
[Please click here for more details and codes.](https://github.com/sarahzhao21/SI670_Kaggle_Competetion_Temperature_Prediction.git)

## Project8: Sentiment Analysis and Prediction by User Reviews with NLP Deep Learning Models.
For this project, we would like to explore the relationship between yelp user reviews and yelp user ratings of restaurants. User rating is a good indicator of user attitudes towards local business. Inspired by the novel approaches that integrate NLP with deep learning, this project aims to train an algorithm that predicts the classes of user ratings with user reviews. This algorithm could be used to detect the user attitudes to restaurants from other crowdsourcing narratives (e.g. Tweets about restaurants) and can potentially expand the rating system of local restaurants.
[Please click here for more details and codes.](https://github.com/sarahzhao21/SI-670-Maching-Learning-Project.git)
![Classify Yelp Users Rating by User Reviews.](https://user-images.githubusercontent.com/54957469/119426199-c50e3d00-bcd6-11eb-9fce-ac7690411a9a.jpg)

