# Recommendation-Engine

# Project Introduction
For this project you will analyze the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles you think they will like.

**1. Exploratory Data Analysis**

Before making recommendations of any kind, we need to explore the data we are working with for the project. There are some basic, required questions to be answered about the data we are working with throughout the rest of the notebook. The first part is related to exploratory data analysis of the data sets.

**2. Rank Based Recommendations**

To get started in building recommendations, we first find the most popular articles simply based on the most interactions. Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. These are then the articles we might recommend to new users (or anyone depending on what we know about them).

**3. User-User Based Collaborative Filtering**

In order to build better recommendations for the users of IBM's platform, we could look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. 

**4. Content Based Recommendations (EXTRA - NOT REQUIRED)**


**5. Matrix Factorization**

Finally, we complete a machine learning approach to building recommendations. Using the user-item interactions, we build out a matrix decomposition. Using the decomposition, we get an idea of how well we can predict new articles to an individual might interact with (spoiler alert - it isn't great).

## Data
user-item-interactions.csv: file contains user interaction.
articles_community.csv: file contains articles description.
## Acknowledgments
I would like to thank Udacity for this amazing project, and IBM for providing the data.

<a name="getting_started"></a>
# Getting Started

<a name="dependencies"></a>
## Dependencies
* Python 3.5+ (I used Python 3.7)
* Machine Learning Libraries: NumPy, SciPy, Pandas, Sciki-Learn
* Natural Language Process Libraries: NLTK
* SQLlite Database Libraqries: SQLalchemy
* Web App and Data Visualization: Flask, Plotly

## Installing
Clone this GIT repository:
```
git clone https://github.com/pandeysoni/Udacity-IBM-Recommendation-Engine.git
```

## Activate Virtual environment using python or pyenv
```
# Activate using python
python3 -m venv env
source env/bin/activate
```

```
# Activate using pyenv
pyenv activate venv
```

## Install requirement file
```
pip install requirements.txt
```

## Executing Program:
Run Recommendations_with_IBM.ipynb file in Jupyter Notebook.

## Authors

* [Soni Pandey](https://github.com/pandeysoni)

