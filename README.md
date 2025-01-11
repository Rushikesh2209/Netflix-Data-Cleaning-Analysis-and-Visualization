# Netflix Data: Cleaning, Analysis and Visualization

![screenshot1](https://github.com/Rushikesh2209/Netflix-Data-Cleaning-Analysis-and-Visualization/blob/main/netflix.jpg)

## Context:
 #### This dataset provides a unique opportunity to delve into the factors that shape the popularity of Netflix content and develop a robust model for predicting audience preferences.
## Description:
 #### Netflix is a popular streaming service that offers a vast catalog of movies, TV shows, and original content. This dataset is a cleaned version of the original version which can be found here. The data consists of content added to Netflix from 2008 to 2021. The oldest content is as old as 1925 and the newest is 2021. The purpose of this dataset is to test my data cleaning and visualization skills.
 
 #### The first step is to Importing the required Libraries.

 ![screenshot1](https://github.com/Rushikesh2209/Netflix-Data-Cleaning-Analysis-and-Visualization/blob/480e8f1d0f1082915d3fb895490fbd16d81e91c1/1.png)

 
#### Upload the csv file named (netflix1.csv) in the Python folder saved on Jupyter Notebook. Load the Dataset from the csv file name (netflix1.csv) using the panda function.

![screenshot1](https://github.com/Rushikesh2209/Netflix-Data-Cleaning-Analysis-and-Visualization/blob/480e8f1d0f1082915d3fb895490fbd16d81e91c1/2.png)

 
 #### Remove all duplicate rows from the data frame.

 ![screenshot1](https://github.com/Rushikesh2209/Netflix-Data-Cleaning-Analysis-and-Visualization/blob/480e8f1d0f1082915d3fb895490fbd16d81e91c1/3.png)

#### Return the dimensions (rows, columns) of the data frame
 
 ![screenshot1](https://github.com/Rushikesh2209/Netflix-Data-Cleaning-Analysis-and-Visualization/blob/480e8f1d0f1082915d3fb895490fbd16d81e91c1/4.png)

.

 #### Return all the column names of the DataFrame.

![screenshot1](https://github.com/Rushikesh2209/Netflix-Data-Cleaning-Analysis-and-Visualization/blob/480e8f1d0f1082915d3fb895490fbd16d81e91c1/5.png)

 
#### Now, we loaded the dataset and examined its basic information using info(). The dataset has no missing values.

![screenshot1](https://github.com/Rushikesh2209/Netflix-Data-Cleaning-Analysis-and-Visualization/blob/480e8f1d0f1082915d3fb895490fbd16d81e91c1/6.png)


#### Convert the 'date_added' column to the DateTime format for easier date-based analysis and operations.

![screenshot1](https://github.com/Rushikesh2209/Netflix-Data-Cleaning-Analysis-and-Visualization/blob/480e8f1d0f1082915d3fb895490fbd16d81e91c1/7.png)
![screenshot1](https://github.com/Rushikesh2209/Netflix-Data-Cleaning-Analysis-and-Visualization/blob/480e8f1d0f1082915d3fb895490fbd16d81e91c1/8.png)


#### Count the occurrences of each unique value in the 'type' column and reset the index to create a DataFrame

![screenshot1](https://github.com/Rushikesh2209/Netflix-Data-Cleaning-Analysis-and-Visualization/blob/480e8f1d0f1082915d3fb895490fbd16d81e91c1/9.png)
![screenshot1](https://github.com/Rushikesh2209/Netflix-Data-Cleaning-Analysis-and-Visualization/blob/480e8f1d0f1082915d3fb895490fbd16d81e91c1/10.png)
![screenshot1](https://github.com/Rushikesh2209/Netflix-Data-Cleaning-Analysis-and-Visualization/blob/480e8f1d0f1082915d3fb895490fbd16d81e91c1/11.png)
![screenshot1](https://github.com/Rushikesh2209/Netflix-Data-Cleaning-Analysis-and-Visualization/blob/480e8f1d0f1082915d3fb895490fbd16d81e91c1/12.png)


#### Filter out rows where 'director' is 'Not Given', then count occurrences of each 'type' and'director', sort them in descending order, and reset the index for a clean DataFrame.

![screenshot1](https://github.com/Rushikesh2209/Netflix-Data-Cleaning-Analysis-and-Visualization/blob/480e8f1d0f1082915d3fb895490fbd16d81e91c1/13.png)
![screenshot1](https://github.com/Rushikesh2209/Netflix-Data-Cleaning-Analysis-and-Visualization/blob/480e8f1d0f1082915d3fb895490fbd16d81e91c1/14.png)

#### Get the top 10 most frequent movie directors from the 'directors' DataFrame.

![screenshot1](https://github.com/Rushikesh2209/Netflix-Data-Cleaning-Analysis-and-Visualization/blob/480e8f1d0f1082915d3fb895490fbd16d81e91c1/15.png)

#### Get the top 10 most frequent TV show directors from the 'directors' DataFrame.

![screenshot1](https://github.com/Rushikesh2209/Netflix-Data-Cleaning-Analysis-and-Visualization/blob/480e8f1d0f1082915d3fb895490fbd16d81e91c1/16.png)

#### Return an array of unique countries present in the 'country' column of the DataFrame.

![screenshot1](https://github.com/Rushikesh2209/Netflix-Data-Cleaning-Analysis-and-Visualization/blob/480e8f1d0f1082915d3fb895490fbd16d81e91c1/17.png)
![screenshot1](https://github.com/Rushikesh2209/Netflix-Data-Cleaning-Analysis-and-Visualization/blob/480e8f1d0f1082915d3fb895490fbd16d81e91c1/18.png)

#### Return the number of unique values in the 'release_year' column.

![screenshot1](https://github.com/Rushikesh2209/Netflix-Data-Cleaning-Analysis-and-Visualization/blob/480e8f1d0f1082915d3fb895490fbd16d81e91c1/19.png)

#### Filter out 'Not Given' countries, count occurrences of each 'type' and 'country', sort by frequency, and reset the index.

![screenshot1](https://github.com/Rushikesh2209/Netflix-Data-Cleaning-Analysis-and-Visualization/blob/480e8f1d0f1082915d3fb895490fbd16d81e91c1/20.png)
![screenshot1](https://github.com/Rushikesh2209/Netflix-Data-Cleaning-Analysis-and-Visualization/blob/480e8f1d0f1082915d3fb895490fbd16d81e91c1/21.png)
![screenshot1](https://github.com/Rushikesh2209/Netflix-Data-Cleaning-Analysis-and-Visualization/blob/480e8f1d0f1082915d3fb895490fbd16d81e91c1/22.png)
![screenshot1](https://github.com/Rushikesh2209/Netflix-Data-Cleaning-Analysis-and-Visualization/blob/480e8f1d0f1082915d3fb895490fbd16d81e91c1/23.png)

#### Count occurrences of each 'release_year', sort them in descending order, and reset the index for a clean DataFrame

![screenshot1](https://github.com/Rushikesh2209/Netflix-Data-Cleaning-Analysis-and-Visualization/blob/480e8f1d0f1082915d3fb895490fbd16d81e91c1/24.png)
![screenshot1](https://github.com/Rushikesh2209/Netflix-Data-Cleaning-Analysis-and-Visualization/blob/480e8f1d0f1082915d3fb895490fbd16d81e91c1/25.png)
![screenshot1](https://github.com/Rushikesh2209/Netflix-Data-Cleaning-Analysis-and-Visualization/blob/480e8f1d0f1082915d3fb895490fbd16d81e91c1/26.png)
![screenshot1](https://github.com/Rushikesh2209/Netflix-Data-Cleaning-Analysis-and-Visualization/blob/480e8f1d0f1082915d3fb895490fbd16d81e91c1/27.png)

#### Group data by 'type' and 'duration', count occurrences of each duration, sort by frequency, and reset the index.
![screenshot1](https://github.com/Rushikesh2209/Netflix-Data-Cleaning-Analysis-and-Visualization/blob/480e8f1d0f1082915d3fb895490fbd16d81e91c1/28.png)
![screenshot1](https://github.com/Rushikesh2209/Netflix-Data-Cleaning-Analysis-and-Visualization/blob/480e8f1d0f1082915d3fb895490fbd16d81e91c1/29.png)

#### Group data by 'type' and 'rating', count occurrences of each rating, sort by frequency, and reset the index.

![screenshot1](https://github.com/Rushikesh2209/Netflix-Data-Cleaning-Analysis-and-Visualization/blob/480e8f1d0f1082915d3fb895490fbd16d81e91c1/30.png)
![screenshot1](https://github.com/Rushikesh2209/Netflix-Data-Cleaning-Analysis-and-Visualization/blob/480e8f1d0f1082915d3fb895490fbd16d81e91c1/31.png)

#### Group data by 'listed_in' (genre) and 'type', count occurrences of each genre, and reset the index for a clean DataFrame

![screenshot1](https://github.com/Rushikesh2209/Netflix-Data-Cleaning-Analysis-and-Visualization/blob/480e8f1d0f1082915d3fb895490fbd16d81e91c1/32.png)
![screenshot1](https://github.com/Rushikesh2209/Netflix-Data-Cleaning-Analysis-and-Visualization/blob/480e8f1d0f1082915d3fb895490fbd16d81e91c1/33.png)

#### Create a pie chart of 'types' with percentage labels, a shadow effect, and an exploded slice for 'TV Show
![screenshot1](https://github.com/Rushikesh2209/Netflix-Data-Cleaning-Analysis-and-Visualization/blob/480e8f1d0f1082915d3fb895490fbd16d81e91c1/34.png)

#### Generate a distinct color palette and Create the bar plot
![screenshot1](https://github.com/Rushikesh2209/Netflix-Data-Cleaning-Analysis-and-Visualization/blob/480e8f1d0f1082915d3fb895490fbd16d81e91c1/35.png)

#### Generate a distinct color palette for Top 10 movie directors and Create the bar plot.

![screenshot1](https://github.com/Rushikesh2209/Netflix-Data-Cleaning-Analysis-and-Visualization/blob/480e8f1d0f1082915d3fb895490fbd16d81e91c1/36.png)
![screenshot1](https://github.com/Rushikesh2209/Netflix-Data-Cleaning-Analysis-and-Visualization/blob/480e8f1d0f1082915d3fb895490fbd16d81e91c1/37.png)
![screenshot1](https://github.com/Rushikesh2209/Netflix-Data-Cleaning-Analysis-and-Visualization/blob/480e8f1d0f1082915d3fb895490fbd16d81e91c1/38.png)
![screenshot1](https://github.com/Rushikesh2209/Netflix-Data-Cleaning-Analysis-and-Visualization/blob/480e8f1d0f1082915d3fb895490fbd16d81e91c1/39.png)
![screenshot1](https://github.com/Rushikesh2209/Netflix-Data-Cleaning-Analysis-and-Visualization/blob/480e8f1d0f1082915d3fb895490fbd16d81e91c1/40.png)
![screenshot1](https://github.com/Rushikesh2209/Netflix-Data-Cleaning-Analysis-and-Visualization/blob/480e8f1d0f1082915d3fb895490fbd16d81e91c1/41.png)

#### Plot the pie chart and Provide the 'count' values for the pie chart.

![screenshot1](https://github.com/Rushikesh2209/Netflix-Data-Cleaning-Analysis-and-Visualization/blob/480e8f1d0f1082915d3fb895490fbd16d81e91c1/42.png)

## Conclusion and Insights
#### Through this analysis, we have gained valuable insights into the Netflix dataset. We have explored the distribution of content types, genres, and directors, as well as the trends in content release over time. The findings of this analysis can be used to inform content acquisition and production strategies, as well as to identify opportunities for growth and improvement.

#### 1) The majority of Netflix content is TV Shows, with a significant increase in TV Show releases over the years.

#### 2) Movies are the second most common type of content, with a steady release pattern over the years.

#### 3) The most popular genres are Documentaries, TV Dramas, and Comedies.

#### 4) The top directors by content count are primarily associated with TV Shows.

#### 5) There is a clear trend of increasing content release over the years, with a significant spike in 2021.

#### 6) The word cloud of movie titles highlights the diversity of content available on Netflix.

