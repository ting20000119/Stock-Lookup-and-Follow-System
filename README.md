# Stock Lookup and Follow System

## Installation

To use this template, your computer needs:

- [Python 2 or 3](https://python.org)
- [Pip Package Manager](https://pypi.python.org/pypi)

## Running the app

```bash
python app.py
```
by default this webserver will run on localhost:5000

## Functions of the app

### Search
- users can search by for the stock using the stock ID
- when registering, user can't use username that already exists in database
- after registering, user can login

### Insertion
- users can add their own accounts with username, password, name and email
- user can customize their own playlist by adding stocks
- everyday new stock info gets imported into the Elastic Search System

### Deletion
- user can remove liked stocks


### Other Specialty Functions
- Permission system (only people that have logged in can customize their own playlist by adding stocks)

![image](https://github.com/ting20000119/Stock-Lookup-and-Follow-System/blob/main/Stock%20Lookup%20and%20Follow%20System/img/home.png)

![image](https://github.com/ting20000119/Stock-Lookup-and-Follow-System/blob/main/Stock%20Lookup%20and%20Follow%20System/img/search.png)
