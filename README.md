# Project - Programming for Data Analysis

The following Project concerns data analysis in Python

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install numpy, matplotlib, pandas and seaborn.

```bash
pip install numpy
pip install matplotlib
pip install pandas
pip install seaborn
```
## Project Objective:
In this project we have to create a dataset by simulating a real world phenomenon of our choice. And have to model and synthesise such data using Python package of numpy.random

## Project Scope:
Dataset should be at least one-hundred data points across at least four different variables.

Investigate the types of variables involved, their likely distributions, and their relationships with each other.

Synthesise/simulate a data set as closely matching their properties as possible.

Detail your research and implement the simulation in a Jupyter notebook.

## Selection of Dataset and Attributes
For this project i will create a song track dataset which can be used for real problems like music recommendation, rating prediction of a song, top 10 songs of the year. The columns of the data set will be 6 and the total rows will be 200. The column attributes are as follows:

1. Song_id = int   
#Unique ID for every song in the dataset, in total there are 200 songs in the dataset

2. Listen_count = int   
#Number of times a song was listened

3. Year = int [2015, 2020]   
#Release year of the song track

4. Genre = str   
[pop, rock, jazz, hiphop, disco, folk]

5. Downloads = int   
#Number of downloads of each song

6. Rating = float   
#Average rating of each song

## Generating Dataset using Numpy Random Module
We will use normal distribution for listen counts and number of downloads and for ratings we'll use unifrom distribution from 1 to 5. The year and genre will be randomly selected using randint and random choice.

## Creating Pandas DataFrame For Better view of Dataset
In this project for better visualization of dataset we have been using the pandas library to create a dataframe from our attributes which we have already generated using numpy random module.


## Displaying Dataset using Dataframe

```
df.head()
df.tail()
```

### Finding the relations between the variables

Ploting different graphs to get better understanding of the dataset.

> 1. Heat Map
> 2. Box Plot
> 3. Distribution Plot
> 4. Histogram
> 5. Pie Chart


## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.
## Reference

## License
[MIT](https://choosealicense.com/licenses/mit/)
