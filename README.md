# Country-Club-SQL
A case study using Juptyer Notebook and SQLite to tackle a series of business questions on a database containing information about a country club. 

## Prerequisites
Before you begin, ensure you have met the following requirements:

*You have jupyter notebook installed
*You have have at least an intermediate understanding of SQL and databases
*You are familiar with relational databases in Python

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
Just edit the query section of the 'select_all_tasks(conn)' function as seen below.

![picture alt] https://user-images.githubusercontent.com/69739726/103509874-f0bc8380-4e18-11eb-9a67-ceeec0cc9e05.png

## Contributing to Country-Club-SQL
To contribute to Country-Club-SQL, follow these steps:

1. Fork this repository.
2. Create a branch: git checkout -b <branch_name>.
3. Make your changes and commit them: git commit -m '<commit_message>'
4. Push to the original branch: git push origin <project_name>/<location>
5. Create the pull request.
Alternatively see the GitHub documentation on creating a pull request.

## Contact
If you want to contact me you can reach me at mtardy888@gmail.com.
