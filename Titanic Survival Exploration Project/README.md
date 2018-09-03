# Project 0: Introduction and Fundamentals

## Titanic Survival Exploration
### This project requires **Python 2.7** and the following Python libraries installed:
**Install**
- [Numpy](http://www.numpy.org/).
- [Pandas](http://pandas.pydata.org/).
- [matplotlib](https://matplotlib.org/).
- [scikit-learn](http://scikit-learn.org/stable/).

Udacity recommends our students install [Anaconda](https://www.continuum.io/downloads) , a pre-packaged Python distribution 
that contains all of the necessary libraries and software for this project.

**Project Overview**
In this project, we will create decision functions that attempt to predict survival outcomes
from the 1912 Titanic disaster based on each passenger's features, such as sex ande age.
We will start with a simple algorithm and increase its complexity until we are able to predict
the outcomes for atleast `80%` of the passengers in the provided data.

**Code**
Template code is provided in the notebook `titanic_survival_exploration.ipynb` notebook file.
Additional supporting code can be found in `titanic_visualizations.py` .
While some code has already been implemented to get you started,
you will need to implement additional functionality when requested to successfully complete the project.

**Data**

The dataset used in this project is included as `titanic_data.csv` . 
This dataset is provided by Udacity and contains the following attributes:

- `survival` : Survival (0 = No; 1 = Yes)
- `pclass` : Passenger Class (1 = 1st; 2 = 2nd; 3 = 3rd)
- `name` : Name
- `sex` : Sex
- `age` : Age
- `sibsp` : Number of Siblings/Spouses Aboard
- `parch` : Number of Parents/Children Aboard
- `ticket` : Ticket Number
- `fare` : Passenger Fare
- `cabin` : Cabin
- `embarked` : Port of Embarkation (C = Cherbourg; Q = Queenstown; S = Southampton)
