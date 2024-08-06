# Netflix-Movies-and-TV-Shows-Clustering-Unsupervised-Machine-Learning
## **Obective:** 
This project aims to analyze the evolution of Netflix's content library, using a dataset of TV shows and movies available on Netflix as of 2019.
## **Dataset:**
* show_id : Unique ID for every Movie / Tv Show
* type : Identifier - A Movie or TV Show
* title : Title of the Movie / Tv Show
* director : Director of the Movie
* cast : Actors involved in the movie / show
* country : Country where the movie / show was produced
* date_added : Date it was added on Netflix
* release_year : Actual Releaseyear of the movie / show
* rating : TV Rating of the movie / show
* duration : Total Duration - in minutes or number of seasons
* listed_in : Genere
* description: The Summary description
## **Data Cleaning and Manipulation:**
In the given dataset there is no duplicate values therefore no need to do any changes. In the given dataset there are total 3613 missing values.
There are 5 columns which have missing values as follows:
  * director - 2389
  * cast - 718
  * country - 507
  * date_added - 10
  * rating - 7

From the above 5 columns I dropped 1 column which is director column because I do not need for analysis and date_added and ratings columns have null values so I dropped those null values using dropna fumction. Missing values from cast column is replace by "No Cast" and missing value from country column is replaced by name of countries from dataset.
## **EDA:**
For the EDA and data visualization I used following charts :
 * Pie Chart
 * Bar plot
 * Count Plot
 * Heatmap
 * Point plot
 * Line Plot
 * Distplot

I tried to find out answers of following:
 * How many TV shows and movies are there in the dataset?
 * What is the distribution of release years for the content?
 * Release by month
 * Top 10 countries who produce the most content?
 * Rating distribution of TV shows and Movies
 * What are the most common genres on Netflix?
 * Duration
## **Hypothesis Testing:**
In hypothesis testing I define three hypothetical statments and also tried to find out p value using Z-statistical test and T-statistical test.
## **Feature Engineering:**
In feature engineering I did textual data processing, removed punctuations etc.
## **Machine Learning Model Implimentation:**
In this project I used three algorithms kMeans clustering, Hierarchy Clustering and Alggomerative Clustering.
## *Conclusion:**
* EDA:
  * There are more number of movies than TV shows.
  * In 2018, the number of both tv shows and movies are highest. In 2017 highest number of movies released and In 2020 highest number of tv shows released.
  * In 12th month means in December maximum number of content was added. From october to january highest number of content was added.
  * The graph shows a significant increase in both TV shows and movies on Netflix starting from the 2000s, with a sharp spike in content around 2015-2019. TV shows have seen rapid growth, especially in the last decade, while the number of movies, after peaking, appears to have slightly declined recently.
  * TV-MA has the highest number of ratings in both the cases i. e. tv shows as well as movies category.
