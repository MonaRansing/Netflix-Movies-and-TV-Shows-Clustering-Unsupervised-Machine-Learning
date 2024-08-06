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

From the above 5 columns I deropped 1 column which is director column because I do not neede for analysis and date_added and ratings columns have null values so I dropped those null values using dropna fumction. Missing values from cast column is replace by "No Cast" and missing value from country column is replaced by name of countries from dataset.
