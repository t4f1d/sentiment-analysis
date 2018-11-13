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


## Methodology

### 1. Retrieve Data
Firstly, we looped to download the GDELT data, extract the files, read source country `ID` data as the filter; the source country data will give us the source country of every website domain; the last, read and put filtered data into the database. Data are collected from **January 2018 - October 2018.**

### 2. Statistical Analysis


## Built With

* [Python 3.7](https://www.python.org/downloads/) - The Programming Languange
* [Jupyter Notebook](http://jupyter.org/) - The Notebook for interactive computing
* [MySQL](https://www.mysql.com/) - Database management system

