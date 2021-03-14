# Movie Recommendation System

[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)

[![](https://img.shields.io/badge/python-3.8-blue.svg)](https://www.python.org/downloads/release/python-380/)

[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/AkashSDas)

[![Ask Me Anything !](https://img.shields.io/badge/Ask%20me-anything-1abc9c.svg)](https://github.com/AkashSDas)

[![PyPI license](https://img.shields.io/pypi/l/ansicolortags.svg)](LICENSE)

## Table of contents

- [About](#about)

- [Technologies Used](#technologies-used)

- [Results of the Project](#results-of-the-project)

- [Installation](#installation)

- [Data Source](#data-source)

- [License](#license)

## About

> **Content-Based** or **Item-Item recommendation systems**. This technique attempts to figure out what a user's favourite aspects of an item is, and then recommends items that present those aspects.

> In our case, we're going to try to figure out the input's favourite genres from the movies and ratings given.

> **Collaborative Filtering**, which is also known as **User-User Filtering**.

> As hinted by its alternate name, this technique uses other users to recommend items to the input user. It attempts to find users that have similar preferences and opinions as the input and then recommends items that they have liked to the input. There are several methods of finding similar users (Even some making use of Machine Learning), and the one we will be using here is going to be based on the **Pearson Correlation Function**.

## Technologies Used

> [![](https://img.shields.io/badge/python-3.8-blue.svg)](https://www.python.org/downloads/release/python-380/) is used as Programming Language.

> `Numpy` is used for the mathematical and data manipulation.

> `Pandas` is used to analysis and manipulation of data.

> `Pipenv` is the virtual environment used for the project. `Jupyter Notebook` is used to for the entire data science and machine learning life cycle.

## Results of the Project

#### Content Based Recommendation System

![Content Based Recommendation System](https://github.com/AkashSDas/Movie-Recommendation-System/blob/master/project-results-images/content-based.png)

#### Collaborative Filtering System

![Collaborative Filtering System](https://github.com/AkashSDas/Movie-Recommendation-System/blob/master/project-results-images/collaborative-filtering.png)

## Installation

It is highly **recommended** to use **`virtual enviroment`** for this project to avoid any issues related to dependencies.

Here **`pipenv`** is used for this project.

There is a **`requirements.txt`** file in `'Movie-Recommendation-System'/requirements.txt` which has all the dependencies for this project.

- First, start by closing the repository

```bash
git clone https://github.com/AkashSDas/Movie-Recommendation-System
```

- Start by installing **`pipenv`** if you don't have it

```bash
pip install pipenv
```

- Once installed, access the venv folder inside the project folder

```bash
cd  'Movie-Recommendation-System'/venv/
```

- Create the virtual environment

```bash
pipenv install
```

The **Pipfile** of the project must be for creating replicating project's virtual enviroment.

This will install all the dependencies and create a **Pipfile.lock** (this should not be altered).

- Enable the virtual environment

```bash
pipenv shell
```

- dataset, jupyter notebook and model are in `'Movie-Recommendation-System'/venv/src` folder.

```bash
cd src/
```

- To start/view the jupyter notebook

```bash
jupyter noterbook
```

This will open a webpage in the browser from there you can click on content-based.ipynb where `Content Based Recommendation System` model is build and in collaborative-filtering.ipynb where `Collaborative Filtering System` is build to view it.

## Data Source

> The `data used` in building the content based recommendation system and collaborative filtering system can be found on Kaggle - [Source](https://www.kaggle.com/grouplens/movielens-20m-dataset).

## License

This project is licensed under the MIT License - see the [MIT LICENSE](LICENSE) file for details.
