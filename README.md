# Data Modeling with Cassandra

Data modeling with Cassandra and build an ETL pipeline using Python.


### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Run](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

```
# Installing Java SDK via Brew (OSX)
brew install --cask adoptopenjdk/openjdk/adoptopenjdk8
```

```
# Installing Python via Brew (OSX)
brew install python
```

```
# Installing CQL
pip install cql
```

```
# Installing cassandra-driver
pip install cassandra-driver
```

```
# Installing cassandra-driver via Brew (OSX)
brew info cassandra
```

## Project Motivation<a name="motivation"></a>
A startup called Sparkify wants to analyze the data they've been collecting on songs and user activity on their new music streaming app. The analysis team is particularly interested in understanding what songs users are listening to. Currently, there is no easy way to query the data to generate the results, since the data reside in a directory of CSV files on user activity on the app.

They'd like a data engineer to create an Apache Cassandra database which can create queries on song play data to answer the questions.


## File Descriptions <a name="files"></a>


```
- Project_1B_Project_Template.ipynb  # Data Modeling file 
- event_data/  Music app history cvs files
- README.md
```

## Run <a name="results"></a>

```
cassandra -f

```
If something goes wrong, please check the article.
https://www.linkedin.com/pulse/%25E5%25A6%2582%25E4%25BD%2595%25E5%259C%25A8-mac-os-x-%25E4%25B8%258A%25E5%25AE%2589%25E8%25A3%2585-apache-cassandra-tom-ge/?trackingId=KuxYavn9SgKxEW2k7dqMzg%3D%3D


## Licensing, Authors, and Acknowledgements <a name="licensing"></a>

### Built With

* [Cassandra](https://cassandra.apache.org/) - Manage massive amounts of data, fast, without losing sleep


### Versioning

* We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags).

### Authors

* **Tom Ge** - *Fullstack egineer* - [github profile](https://github.com/tomgtqq)

### License

* This project is licensed under the MIT License
