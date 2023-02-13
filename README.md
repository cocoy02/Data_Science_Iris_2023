# EY_2023

## Motivation
A garden owner would like to examine the distinctiveness of different Iris flower classes (Iris Setosa, Iris Versicolour, and Iris Virginica) in his garden based on historical data measurements (sepal length, sepal width, petal length, petal width). With understanding of the differences, he’d also like to create a tool with help from a top data scientist to quickly retrieve records of the most similar Iris flowers in his garden for any input Iris flower.

## Getting Started
This project uses Python 3.8 and Jupyter Notebook. Upon cloning this repository into your local machine, run the following command to install all relevant packages.
```bash
pip install -r requirements.txt
```
To run the project:
-- Open `Yang Leyuan_Iris.ipynb`
-- Start the Kernel and Run All

Error shooting:
-- If the server is being used, please change the port to any number

## Files
The following table contains a brief description of the files and folders in this repository.
| Folder / File | Description |
| - | - |
| **main.py** | Main file for running project pipeline. |
| **data_analysis.ipynb** | A sample notebook showing how our aspect-based sentiment analysis data can be used for downstream applications to analyse restaurant performance. |
| **scraping** | Folder containing code and scripts to trigger data scraping from the Burpple website. |
| **rules** | Folder containing `rule_mining.ipynb`, used to test rules for aspect identification. | 
| **modelling** | Folder containing jupyter notebooks used for topic modelling, aspect identification, sentiment analysis (VADER, LR, SVM, NB, RF, BERT, FastText, Stacking) and model explainability (LIME). |
| **utils** | Folder containing python files for preprocessing, postprocessing, rule mining and scoring used in our final pipeline. |
| **dashboard** | Folder containing code used to build our final application on Python Dash. |


## Application Demo
On our application, users can search for a food or restaurant, and filter by location, category, and price range. The search outputs a list of restaurants sorted in decreasing overall score. Depending on user preferences, the output can also be sorted by 6 aspects: food, service, price, portion, ambience, time. On individual restaurant pages, basic restaurant information is provided, and users can view the individual reviews and its associated sentiment scores.
![burpple_plus_demo.gif](assets/burpple_plus_demo.gif)

## Built With
- [Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
- [scikit-learn](https://scikit-learn.org/stable/)
- [Natural Language Toolkit](https://www.nltk.org/)
- [Facebook fastText](https://fasttext.cc/)
- [Google BERT](https://arxiv.org/abs/1810.04805)
- [LIME](https://lime-ml.readthedocs.io/en/latest/)
- [plotly | dash](https://dash.plotly.com/)

## Authors
- Aw Xin Min - [Github](https://github.com/awxinmin)
- Lai Yan Jean -  [Github](https://github.com/laiyanjean)
- Lee Jun Hui Sean - [Github](https://github.com/seansljh)
- Risa Lim Ning - [Github](https://github.com/risalim)
- Valary Lim Wan Qian - [Github](https://github.com/ValaryLim)
