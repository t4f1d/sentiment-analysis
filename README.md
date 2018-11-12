# sentiment-analysis
Indonesia News Sentiment Analysis from GDELT (Global Database of Events, Language, and Tone) Global Knowledge Public Dataset

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

What things you need to install the software and how to install them

```
Anaconda
MySQL Database
Jupyter Notebook
```

### Installing

A step by step series of examples that tell you how to get a development running

Clone this repository

```bash
$ git clone https://github.com/t4f1d/sentiment-analysis.git
```

and then import the database `data/gdelt_id_data.sql.zip` into MySQL Database

```bash
mysql -u username -p gdelt_id_data < gdelt_id_data.sql.zip
```


## Running the tests

Explain how to run the automated tests for this system


## Built With

* [Python 3.7](https://www.python.org/downloads/) - The Programming Languange
* [Jupyter Notebook](http://jupyter.org/) - The Notebook for interactive computing
* [MySQL](https://www.mysql.com/) - Database management system

