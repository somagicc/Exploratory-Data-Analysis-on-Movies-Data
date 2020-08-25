# Exploratory Data Analysis on Movies-Data
![]()

### Presentation
Watch the [presentation](https://docs.google.com/presentation/d/1huSoQE3e1uz74Howpzvw_peBVImpeXq_cgswhPmRRyk/edit "presentation") giving the details of the project. 

### Video Presentation
You can also watch the elaborate [video ](https://www.youtube.com/watch?v=yUopC0USor4&t=137s "video ")presentation.

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


1. Distribution of Movies of the years
![]()

2. Distribution of Mean Revenue of the years
![]()

3. Comparing Count of Movies and Mean Revenue over the Years
![]()

4. Spread of the Revenue (KDE Plot)
![]()

5. Year Distribution of Top 10 movies
![]()

6. Genre Distribution of Top 10 movies
![]()

7. Count of movies in each genre
![]()

8. Distribution of Movies on the basis of Genre
![]()

9. Share of top 5 Genres
![]()

Actionable Insight
Movies which are a combination of Drama, Action and Adventure can earn more revenue and also will be more liked by people.


<a id=section10></a>
## 10. Python Notebook
Find all the codes [here.](https://github.com/somagicc/Gender-Recognition-by-Voice/blob/master/Gender_Recognition_by_Voice.ipynb "here")

Thank you!


