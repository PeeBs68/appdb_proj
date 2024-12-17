# **Programming for Data Analysis**
***

This repository contains a python file titled **'project.py'** which is an application front end connected a SQL database and a Neo4j Database.

## **Overview**

The purpose of this python file is to build a frond end menu that the user can use to perform a number of queries on two different database types. 

This file performs the following functionality:
1. Builds a menu based application and displays it to the user
2. Receives keyboard input from the user and performs actions based on the inputs.
3. Performs queries against a SQL database and a Neo4j database.
4. Exits the menu on command

## **Requirements**

To run the analysis in this notebook, you need to have the following Python packages installed:

- `click`
- `tabulate`
- `neo4j==4.4.0`
- `mysql.connector`
- `neo4j.GraphDatabase`
- `os`
- `time`

You can install these dependencies using 'pip':

```bash
pip install click, tabulate, neo4j==4.4.0, mysql.connector, neo4j.GraphDatabase, os, time
```

Alternatively you can install all the required dependencies from the `requirements.txt file:

```bash
pip install -r requirements.txt
```

## **Usage**

### **Steps to Run the Analysis**

1. Clone this repository:

```bash
git clone https://github.com/PeeBs68/appdb_proj.git
```

2. Launch VS Code:

```bash
python project.py
```

### **File Workflow**

The **project.py** follows these key steps

#### 1. **Menu Display**
    - Displays the main menu
    - Prompts user for input

#### 2. **Database Queries**
    - Loads query for selected menu item
    - Opens config file with connectivity details
	- Performs query and closes database connection

#### 3. **Results**
    - Display the results
	- Returns user back to main menu when prompted

#### 4. **Close**
	- Quits the menu and returns user back to the terminal prompt
