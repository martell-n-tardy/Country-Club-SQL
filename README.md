# Country-Club-SQL
A case study using Juptyer Notebook and SQLite to tackle a series of business questions on a database containing information about a country club. 

## Prerequisites
Before you begin, ensure you have met the following requirements:

* You have jupyter notebook installed
* You have have at least an intermediate understanding of SQL and databases

    If not, I strongly suggest completing the following courses offered through DataCamp:
      
     - Introduction to SQL for Data Science
     - Joining Data in SQL
     - Intermediate SQL
  
* You are familiar with relational databases in Python
  
    If not, again DataCamp offers a course 
    - Working with Relational Databases in Python
    (specifically chapter 4 of this course will be sufficient for this requirement) 

## Installing Country-Club-SQL
To install Country-Club_SQL, follow these steps:

Linux and macOS:

```
execute the python script
python LocalSQLConnection.py
```
Results should look like:
```
2.6.0
2. Query all tasks
(0, 'Tennis Court 1', 5, 25, 10000, 200)
(1, 'Tennis Court 2', 5, 25, 8000, 200)
(2, 'Badminton Court', 0, 15.5, 4000, 50)
(3, 'Table Tennis', 0, 5, 320, 10)
(4, 'Massage Room 1', 9.9, 80, 4000, 3000)
(5, 'Massage Room 2', 9.9, 80, 4000, 3000)
(6, 'Squash Court', 3.5, 17.5, 5000, 80)
(7, 'Snooker Table', 0, 5, 450, 15)
(8, 'Pool Table', 0, 5, 400, 15)
```

If you see this then things are working and you should be able to edit the file to add in any queries you want. 

Your SQL queries will occur directly on the `sqlite_db_pythonsqlite.db` database file.
Just edit the query section of the `def select_all_tasks(conn)` function as seen through this link

https://user-images.githubusercontent.com/69739726/103509874-f0bc8380-4e18-11eb-9a67-ceeec0cc9e05.png

If you found this project interesting and would like to continue sharping your SQL skills, 
I've included practice SQL interview questions within the document titled "SQL Practice Interview Questions" in this repository.

Additionally, I found the HackerRank SQL Challenges to be both fun and informative to the learning process as well. 
Here's the link, https://www.hackerrank.com/domains/sql. Give a few of them a try!

And as always thanks for stopping by :wave: :sparkles:
