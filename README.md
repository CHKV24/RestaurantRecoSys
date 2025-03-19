# Recommendation System Project

## Project Overview
This project focuses on building a Recommendation System using data from Bangalore restaurants. The system leverages data analysis and machine learning techniques to provide personalized recommendations.

## Files in the Repository
- **`19CSE352_Part1_Gp5_MBA.ipynb`**: Jupyter Notebook implementing Market Basket Analysis for recommendation insights.
- **`19CSE352_Part1_Gp5_RecoSys.ipynb`**: Jupyter Notebook building a collaborative filtering recommendation system.
- **`data_set_ink.txt`**: Dataset containing restaurant data for Bangalore, sourced from [Kaggle](https://www.kaggle.com/datasets/vora1011/zomato-bangalore-restaurants-2022s).

## Requirements
To run the notebooks successfully, you will need the following dependencies:
- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

Install dependencies using the following command:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

## How to Run
1. Clone the repository:
```bash
git clone <repository-url>
```
2. Navigate to the project directory:
```bash
cd <project-directory>
```
3. Open Jupyter Notebook:
```bash
jupyter notebook
```
4. Open the desired `.ipynb` file and run the cells in sequence.

## Project Workflow
1. **Data Preprocessing**
   - Data cleaning and handling missing values.
   - Feature engineering to improve recommendation accuracy.
2. **Market Basket Analysis**
   - Frequent itemset generation and association rule mining.
3. **Collaborative Filtering**
   - Implemented user-based and item-based filtering models.
   - Evaluated model performance using metrics like RMSE and MAE.

## Results
- The Market Basket Analysis identified key item combinations to improve user recommendations.
- The Collaborative Filtering model demonstrated improved personalized suggestions.

## Dataset Information
The dataset includes the following features:
- Restaurant names
- Cuisine types
- Ratings and reviews
- Location data

## Future Improvements
- Integrate a hybrid recommendation system.
- Add a web interface for interactive recommendations.
