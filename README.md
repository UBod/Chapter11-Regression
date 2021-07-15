# Chapter 11: Regression
## Data-Driven Modeling of Numerical Relationships in Tourism
***[Andreas Stöckl](https://github.com/astoeckl)*** & ***[Ulrich Bodenhofer](https://github.com/Ubod)***

### Abstract

Regression is the task of calculating a numerical value based on an object’s set of characteristics. One important sub-branch consists of methods that learn regression functions from example data. This repository provides a Jupyter notebook along with a data set from a tourism-related use case that exemplifies how to model the prediction of the total sum of bookings for a hotel based on web tracking data. Predictions with linear regression, support vector regression, decision trees, random forests, and neural networks will be calculated and evaluated.

### Environment Setup

The notebook was created using `Python 3.8.10`. You need the following packages: `pandas', `numpy', `sklearn', `plotly', `matplotlib', and `xgboost'. Additionally, you need a properly configured IPython kernel. 

On a Windows system with Python 3, we recommend performing the following steps upon cloning the repository:
```bash
# create a new Python environment and activate it.
python -m venv .env
.env\Scripts\activate
pip install ipykernel jupyter pandas numpy plotly sklearn matplotlib xgboost
python -m ipykernel install --user --name .env --display-name "Python (Data Science in Tourism)"

# now you can start a Jupyter session
jupyter notebook
```

On a Linux/Mac OS system with Python 3, we recommend performing the following steps upon cloning the repository:
```bash
# create a new Python environment and activate it.
python3 -m venv .env
source .env/bin/activate
pip install ipykernel jupyter pandas numpy plotly sklearn matplotlib xgboost
python -m ipykernel install --user --name .env --display-name "Python (Data Science in Tourism)"

# now you can start a Jupyter session
jupyter notebook
```

### Contact

Andreas Stöckl - [Homepage](http://www.stoeckl.ai/) - [LinkedIn](https://www.linkedin.com/in/andreas-st%C3%B6ckl-57682113a/) - [Twitter](https://twitter.com/stoecklai)

Ulrich Bodenhofer - [Homepage](http://ulrich.bodenhofer.com) - [LinkedIn](https://www.linkedin.com/in/ulrichbodenhofer/) - [Twitter](https://twitter.com/u_bode)
