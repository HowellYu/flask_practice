Run the following command to create a example db
```bash
python db_creator_example.py
```

Run the following command to execute.
```bash
FLASK_APP=test.py flask run
```

**Note:**
Note that the `init_db()` call doesn’t always seem to work, so you may need to run the db_creator script if  SQLite database file isn’t generated correctly. 
