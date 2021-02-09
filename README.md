# Weather Analysis with SQLAlchemy and SQLite

Advanced Data Storage and Retrieval using SQLAlchemy to connect to and query a SQLite database. Then, use statistics like minimum, maximum, and average to analyze data.


## Business Problem

When opening a new venture and delivering profitability to investors depending on the type of buisness, several external conditions, such as weather, need to be taking in account before presenting the proposal.  In this project, we will be analyzing historical weather data and it's relationship with the new venture. The purpose of this work, is to enable investors with the necessary information in order to make a well informed decision on wheather or not they should invest in the business.


## Getting Started

These instructions will get your SQLite database up and running on your local machine.


### Prerequisites

Before the installations there are some important concepts you need to know:  

**SQLite**, a version of SQL that lives in the computer or phone and provides a quick way to setup a database engine without requiring a server. SQLite's main purpose is to supporting quick testing and easy prototyping. 

**When to use SQLite and PostgreSQL?**

**SQLite** is highly useful for: Standalone apps, small apps that don’t require expansion, apps need to read or write files to disk directly, the internet of things devices, developing and even testing.  In this project, we will be using this tool as the investors haven't decided yet whether or not they will invest in the new venture.

**PostgreSQL** is recommended when: Data integrity and reliability is highly concerned, custom Procedures which is extensible to run the complex task, complexity with ease. PostgreSQL gives you the functionality to maintain such a complex database smoothly without limitations.  More stablished businesses with a variety of needs and complexities will use this tool.

**SQLAlchemy** is a library that facilitates the communication between Python programs and databases. Most of the times, this library is used as an Object Relational Mapper (ORM) tool that translates Python classes to tables on relational databases and automatically converts function calls to SQL statements.


### Installing

**First**, visit the [DB Browser for SQLite](https://sqlitebrowser.org/) site and download the last released version for your operating system.  **DB Browser for SQLite**, is a high quality, visual, open source tool to create, design, and edit database files compatible with SQLite.  It is for users and developers who want to create, search, and edit databases. DB4S uses a familiar spreadsheet-like interface, and complicated SQL commands do not have to be learned.

**Second**, download [Anaconda](https://docs.anaconda.com/anaconda/install/) for your operating system.  From your Anaconda Navigator you can launch Visual Studio Code and Jupyter Notebook.


### Download files

Download the folders and files contained in this repository on your local machine except for the png_images folder


---

### Analysis

# surfs_up

Overview of the statistical analysis:

The purpose of the analysis is well defined. (3 pt)
Results:

There is a bulleted list that addresses the three key differences in weather between June and December. (6 pt)
Summary:

There is a high-level summary of the results and there are two additional queries to perform to gather more weather data for June and December. (5 pt)

Investing in Waves and Ice Cream


1. In this graph we have along the x-axis are the dates from the last 365 days from our dataset, and the y-axis is the total amount of precipitation for each day. We can observe that some months have higher amounts of precipitation than others.

graph precipitation_last_year


2. Drilling down into the last year's data and only analyzing the meteorological station with the largest number of observations, we can infer that a vast majority of the observations were over 67 degrees. If you count up the bins to the right of 67 degrees, you will get about 325 days where it was over 67 degrees when the temperature was observed.

histogram pic


3. 

---


### Recommendations



---

## Acknowledgments

* Berkeley University Department of Data Science provided the training materials to develop this project.

---

## Author

* Contact: Natalia Velasquez
* Email: nativelasquez@gmail.com
* Twitter: @NatiVelasquez18

