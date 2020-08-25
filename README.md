# Exploratory Data Analysis on Movie Data
![](https://github.com/somagicc/Exploratory-Data-Analysis-on-Movies-Data/blob/master/Images/Intro.PNG)

### Presentation
Watch the [presentation](https://drive.google.com/file/d/1Wc1fN-UzmwcUUOtnfNUGlRdt6QKlKImj/view?usp=sharing "presentation") giving the details of the project. 

### Video Presentation
You can also watch the elaborate [video ](https://youtu.be/QJvsTe3K-uo "video ")presentation.

## About the Data
This dataset provides information of of 1,000 most popular movies on IMDb in the last 10 years. The data fields included are: Title, Genre, Description, Director, Actors, Year, Runtime, Rating, Votes, Revenue, Metascrore

## Attributes of the Data

| Column Name                    | Description                                                                                |
| -------------------------------|------------------------------------------------------------------------------------------| 
| Rank                           | Movie rank order                                                                             
| Title                          | The title of the film                                                                       
| Genre                          | A comma-separated list of genres used to classify the film                                 |
| Description                    | Brief one-sentence movie summary                                                             
| Director                       | The name of the film's director                                                            |
| Actors                         | A comma-separated list of the main stars of the film                                        
| Year                           | The year that the film released.                                                             
| Runtime (Minutes)              | The duration of the film in minutes.                                                         
| Rating                         | User rating for the movie 0-10                                                          |
| Votes                          | Number of votes                                                                 |
| Revenue (Millions)             | Movie revenue in millions                                                          |
| Metascore                      | An aggregated average of critic scores. Values are between 0 and 100. Higher scores represent positive reviews                                                         |
## Data Preprocessing
remove missing values in 'Revenue' column by imputing median value.
remove missing values in 'Metascore' column using 'forward filling' method.

## Data Analysis
1. Distribution of Movies of the years
![](https://github.com/somagicc/Exploratory-Data-Analysis-on-Movies-Data/blob/master/Images/Distribution%20of%20Movies%20over%20the%20Years.png)

2. Distribution of Mean Revenue of the years
![](https://github.com/somagicc/Exploratory-Data-Analysis-on-Movies-Data/blob/master/Images/Distribution%20of%20Mean%20Revenue%20over%20the%20Years.png)

3. Comparing Count of Movies and Mean Revenue over the Years
![](https://github.com/somagicc/Exploratory-Data-Analysis-on-Movies-Data/blob/master/Images/Comparing%20Count%20of%20Movies%20and%20Mean%20Revenue%20over%20the%20Years.png)

4. Spread of the Revenue (KDE Plot)
![](https://github.com/somagicc/Exploratory-Data-Analysis-on-Movies-Data/blob/master/Images/KDE%20plot%20showing%20the%20density%20of%20Revenue.png)

5. Year Distribution of Top 10 movies
![](https://github.com/somagicc/Exploratory-Data-Analysis-on-Movies-Data/blob/master/Images/Year%20Distribution%20of%20Top%2010%20Movies.png)

6. Genre Distribution of Top 10 movies
![](https://github.com/somagicc/Exploratory-Data-Analysis-on-Movies-Data/blob/master/Images/Genre%20Distribution%20of%20Top%2010%20Movies.png)

7. Count of movies in each genre
![](https://github.com/somagicc/Exploratory-Data-Analysis-on-Movies-Data/blob/master/Images/Count%20of%20Movies%20of%20Each%20Genre.png)

8. Distribution of Movies on the basis of Genre
![](https://github.com/somagicc/Exploratory-Data-Analysis-on-Movies-Data/blob/master/Images/Distribution%20of%20Movies%20on%20the%20Basis%20of%20Genres.png)

9. Share of top 5 Genres
![](https://github.com/somagicc/Exploratory-Data-Analysis-on-Movies-Data/blob/master/Images/Share%20of%20Top%205%20Genres.png)

## Actionable Insight
Movies which are a combination of Drama, Action and Adventure can earn more revenue and also will be more liked by people.


<a id=section10></a>
## 10. Python Notebook
Find all the codes [here.](https://github.com/https://github.com/somagicc/Exploratory-Data-Analysis-on-Movies-Data/blob/master/EDA_Movies_Data.ipynb "here")

Thank you!


