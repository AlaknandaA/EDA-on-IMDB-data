# Exploratory Data Analysis on an IMDB movie Dataset

### Problem Statement
Trying to find some interesting insights into a few movies released between 1916 and 2016, using Python. Python functions like concatenation, dropping, sorting, grouping, etc. have been used to gather the insights.

#### Inspection and Cleaning of Data

Have inspected shape and datatypes of all variables in the dataset. Checked number of null values per column.\
After that, I have dropped the columns and rows with high percentages of null values(greater than 5%).
Also, filled the remaining nulls in the 'Language' column with English.
There were some duplicate values in the data as well, I dropped those duplicates.
After all of these steps, still retained 77% of our original data.

#### Analysis Insights:

##### 1. **Top 10 movies by Profit**:

Movie Name | Profit (in Million USD)
--- | ---
Avatar | 523.51
Jurassic World | 502.18
Titanic | 458.67
Star Wars: Episode IV - A New Hope | 449.94
E.T. the Extra-Terrestrial | 424.45
The Avengers | 403.28
The Lion King | 377.78
Star Wars: Episode I - The Phantom Menace | 359.55
The Dark Knight | 348.32
The Hunger Games | 330

##### 2. **Top 10 Foreign Language Films by IMDB Score**:

Movie Name | Language | IMDB Score
--- | --- | ---
The Good, the Bad and the Ugly	| Italian | 8.9
City of God	| Portuguese | 8.7
Seven Samurai |	Japanese | 8.7
Spirited Away |	Japanese | 8.6
Children of Heaven |	Persian | 8.5
The Lives of Others	| German | 8.5
Baahubali: The Beginning | Telugu | 8.4
A Separation	| Persian | 8.4
Amélie	| French | 8.4
Oldboy | Korean | 8.4

##### 3. **Top 10 Directors by IMDB score**

director_name	| imdb_score
--- | ---
Charles Chaplin	| 8.600000
Tony Kaye	| 8.600000
Ron Fricke	| 8.500000
Damien Chazelle |	8.500000
Majid Majidi	| 8.500000
Alfred Hitchcock |	8.500000
Sergio Leone	| 8.433333
Christopher Nolan |	8.425000
Asghar Farhadi |	8.400000
Richard Marquand	| 8.400000

##### 4. **Top 5 genre combinations based on mean gross income values**

genre_1	| genre_2	 | gross income (in Million USD)
--- | --- | ---
Family	| Sci-Fi |	434.95
Adventure |	Sci-Fi	228.63
Adventure | Family	| 118.92
Adventure | Animation	| 117
Action | Adventure	| 109.595465

##### 5. **Plotting number of voted users per decade**

![Alt text](images/Number_of_voted_users_per_decade.png?raw=true "Title")

The number of voted users is fluctuating per decade. There is no clear upward or downward trend.
