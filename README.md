# EY_2023

## Motivation
A garden owner would like to examine the distinctiveness of different Iris flower classes (Iris Setosa, Iris Versicolour, and Iris Virginica) in his garden based on historical data measurements (sepal length, sepal width, petal length, petal width). With understanding of the differences, he’d also like to create a tool with help from a top data scientist to quickly retrieve records of the most similar Iris flowers in his garden for any input Iris flower.

## Getting Started
This project uses Python 3.8 and Jupyter Notebook. Upon cloning this repository into your local machine, run the following command to install all relevant packages.
```bash
pip install -r requirements.txt
```
To run the project:
- Open `Yang Leyuan_Iris.ipynb`
- Start the Kernel and Run All

Error shooting:
- If the server is being used, please change the port to any number

## Files
The following table contains a brief description of the files and folders in this repository.
| Folder / File | Description |
| - | - |
| **Yang Leyuan_Iris.ipynb** | Main file for data preprocessing, data modelling and data visualization. |
| **raw data** | Raw data downloaded from [scikit-learn](https://archive.ics.uci.edu/ml/datasets/Iris)  |
| **image** | Plots for checking data quality |



## Application Demo
On our application, users can search for a food or restaurant, and filter by location, category, and price range. The search outputs a list of restaurants sorted in decreasing overall score. Depending on user preferences, the output can also be sorted by 6 aspects: food, service, price, portion, ambience, time. On individual restaurant pages, basic restaurant information is provided, and users can view the individual reviews and its associated sentiment scores.
![burpple_plus_demo.gif](assets/burpple_plus_demo.gif)

## Built With
- [scikit-learn](https://scikit-learn.org/stable/)
- [plotly | dash](https://dash.plotly.com/)
