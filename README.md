# NBA-Games-Predictor
This project predicts NBA game outcomes by analyzing box scores. First, box scores are scraped and cleaned using BeautifulSoup, then parsed into pandas DataFrames. Key predictors are identified through feature selection, and a machine learning model is trained on these features. Rolling predictions are applied to enhance accuracy over time.

Installation
To follow this project, please install the following locally:

JupyerLab
Python 3.8+
Python packages
pandas
scikit-learn
beautifulsoup4
playwright
Data
We'll download our dataset from Basketball Reference.

You can find the pre-scraped data here if you don't want to run the code.
If you only want to do the second part of this project (prediction), you can download the csv file of box scores here.
