# django-tutorial

# SQLite
```
(.venv) tobi@MacBook-Air mysite % sqlite3
SQLite version 3.32.3 2020-06-18 14:16:19
Enter ".help" for usage hints.
Connected to a transient in-memory database.
Use ".open FILENAME" to reopen on a persistent database.
sqlite> .open db.sqlite3
sqlite> .schema
```

# Shell

```
(.venv) tobi@MacBook-Air mysite % python manage.py shell          
Python 3.7.3 (default, Mar  6 2020, 22:34:30) 
[Clang 11.0.3 (clang-1103.0.32.29)] on darwin
Type "help", "copyright", "credits" or "license" for more information.
(InteractiveConsole)
>>> from polls.models import Choice, Question
>>> Question.objects.all()
<QuerySet [<Question: What's up?>]>
```