# PROJECT DETAILS: QUERY A DIGITAL MUSIC STORE DATABASE
This is the 3rd project in Udacity's Business Analytics Nanodegree
## Project Prompt
In this project, you will query the Parch and Posey Database, which holds information about a paper store. For this project, you will assist the Parch and Posey team with understanding their web traffic, their customers and employees, and their order information.
### Deliverables
You need to come up with 4 questions that you can answer with SQL. The questions must be complex enough to where the SQL used to answer it requires at least one JOIN and one Aggregation.

## Submission Requirements
The final submission should be a Google Slides file, and include a text file that includes each of the queries used to create the visualizations

## Set up your local environment
- Download the [Parch and Posey database](https://s3.amazonaws.com/video.udacity-data.com/topher/2018/May/5afb2ecf_pandp/pandp.db) file
- Download DB Browser for [SQLite](http://sqlitebrowser.org/)

After both have been downloaded, load up the database in SQLite to start querying.

## Key Notes/Suggestions
### Understanding the data
All of these purchases are of songs, no purchases are of entire albums. So if you are trying to show which album has the most sales, you would need to clarify this so that it is not misleading. You would have to show which album has the most songs sold off of it.

### Unrecognized Token
You may get an error that says "unrecognized token" the reason for this is the different uses of single and double quotes around words in your query.
In SQLite "" are used to denote strings and '' are used to denote columns(though this is rare, but sometimes people will have column names with spaces in them and so using the '' allows you to still reference that column
- Correct `SELECT * FROM Genre WHERE Genre.name = "Rock"`
- Incorrect `SELECT * FROM Genre WHERE Genre.name = 'Rock'`

## Results
The final project submission which features the presentation of the questions and their corresponding answers per the queries can be found [here](https://github.com/KOdoi-OJ/Query-a-Digital-Music-Store-Database/blob/main/SQL%20Project%20Submission%20-%20Parch%20and%20Posey%20database.pdf)

