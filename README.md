
# Python + Sql Analysis 

#### Summary
This project is an end-to-end ELT (Extract, Load, Transform) project that utilizes SQL Server and Python to clean and analyze Netflix movie and TV show data. The project demonstrates data cleaning techniques, data modeling, and SQL analysis.
## Highlights
- 🧰 **Data Extraction:** The project begins by extracting data from a Netflix dataset using Python Pandas and loading it into SQL Server.
- 🧹 **Data Cleaning:** The data is then cleaned in SQL Server by handling foreign characters, removing duplicates, and creating separate tables for multi-valued columns such as directors, countries, and genres.
- 🧮 **Data Analysis:** The project then addresses five data analysis questions using SQL queries, demonstrating techniques for data aggregation, filtering, and ranking.
- 📊 **Data Visualization:** The project also perform some EDA in jupyter notebook (python). 


### Queries to solve in sql 

1.  For each director count the no of movies and tv shows      created by them in separate columns 
for directors who have created tv shows and movies both .

2. which country has highest number of comedy movies .

3. For each year (as per date added to netflix), which director has maximum number of movies released .

4. What is average duration of movies in each genre .

5.  find the list of directors who have created horror and   comedy movies both , display director names along with number of comedy and horror movies directed by them.
 
### Analysis  (EDA)
  
  1. Pie Chart for Distribution of Movies and TV Shows on Netflix.
  2. Line Chart for Number of Titles Released Each Year.
  3. Bar Chart for Distribution of Different Ratings for Netflix Titles  
