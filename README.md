# Exploratory Data Analysis on Movie Data
![](https://github.com/somagicc/Exploratory-Data-Analysis-on-Movies-Data/blob/master/Images/Intro.PNG)

### Presentation
Watch the [presentation](https://drive.google.com/file/d/1Wc1fN-UzmwcUUOtnfNUGlRdt6QKlKImj/view?usp=sharing "presentation") giving the details of the project. 

### Video Presentation
You can also watch the elaborate [video ](https://youtu.be/QJvsTe3K-uo "video ")presentation.

Or just continue here.
## Table of Contents
1. [About the Data](#section1)
2. [Attributes of Data](#section2)
3. [Data Preprocessing](#section3)
4. [Insights from Data Analysis](#section4)
5. [Conclusion](#section5)
6. [Python Notebook](#section6)

-------

<a id=section1></a>
## 1. About the Data
This dataset provides information of of 1,000 most popular movies on IMDb in the last 10 years. The data fields included are: Title, Genre, Description, Director, Actors, Year, Runtime, Rating, Votes, Revenue, Metascrore

<a id=section2></a>
## 2. Attributes of the Data

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
<a id=section3></a>
## 3. Data Preprocessing
- Removed missing values in 'Revenue' column by imputing median value.
- Removed missing values in 'Metascore' column using 'forward filling' method.

<a id=section4></a>
## 4. Insights from Data Analysis

![](https://github.com/somagicc/Exploratory-Data-Analysis-on-Movies-Data/blob/master/Images/Distribution%20of%20Movies%20over%20the%20Years.png)


![](https://github.com/somagicc/Exploratory-Data-Analysis-on-Movies-Data/blob/master/Images/Distribution%20of%20Mean%20Revenue%20over%20the%20Years.png)


![](https://github.com/somagicc/Exploratory-Data-Analysis-on-Movies-Data/blob/master/Images/Comparing%20Count%20of%20Movies%20and%20Mean%20Revenue%20over%20the%20Years.png)


![](https://github.com/somagicc/Exploratory-Data-Analysis-on-Movies-Data/blob/master/Images/KDE%20plot%20showing%20the%20density%20of%20Revenue.png)


![](https://github.com/somagicc/Exploratory-Data-Analysis-on-Movies-Data/blob/master/Images/Year%20Distribution%20of%20Top%2010%20Movies.png)


![](https://github.com/somagicc/Exploratory-Data-Analysis-on-Movies-Data/blob/master/Images/Genre%20Distribution%20of%20Top%2010%20Movies.png)


![](https://github.com/somagicc/Exploratory-Data-Analysis-on-Movies-Data/blob/master/Images/Count%20of%20Movies%20of%20Each%20Genre.png)


![](https://github.com/somagicc/Exploratory-Data-Analysis-on-Movies-Data/blob/master/Images/Distribution%20of%20Movies%20on%20the%20Basis%20of%20Genres.png)


![](https://github.com/somagicc/Exploratory-Data-Analysis-on-Movies-Data/blob/master/Images/Share%20of%20Top%205%20Genres.png)

<a id=section5></a>
## 5. Conclusion
Movies which are a combination of Drama, Action and Adventure can earn more revenue and also will be more liked by people.

<a id=section6></a>
## 6. Python Notebook
Find all the codes [here.](https://github.com/somagicc/Exploratory-Data-Analysis-on-Movies-Data/blob/master/EDA_Movies_Data.ipynb "here")

Thank you!


