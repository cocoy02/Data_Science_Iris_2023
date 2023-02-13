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
| **raw data** | Raw data downloaded from [Datasets](https://archive.ics.uci.edu/ml/datasets/Iris)  |
| **image** | Plots for checking data quality |



## Application Demo
- Similar Points within the class: After the input of the new point, the table will show the similar points in the predicted class.
![burpple_plus_demo.gif](assets/Similar Points within the class.mov)

- Nearest Points: After the input of the new point, the table will show the nearest points in the whole dataset.
![burpple_plus_demo.gif](assets/Similar Points within the class.mov)

## Built With
- [scikit-learn](https://scikit-learn.org/stable/)
- [plotly | dash](https://dash.plotly.com/)
