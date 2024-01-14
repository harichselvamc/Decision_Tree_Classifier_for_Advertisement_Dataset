# Decision Tree Classifier for Advertisement Dataset

## Overview

This repository contains a Decision Tree Classifier implemented in R programming for analyzing an advertisement dataset. The primary objective is to predict the success or failure of an advertisement based on various features present in the dataset.

## Dataset

The dataset utilized for this project is available as `advertisement.csv`. It encompasses essential information, including the advertisement type, platform, target audience, and other features that could impact the advertisement's effectiveness.


## Files

- **main.ipynb**: This Jupyter Notebook contains all the code for data loading, preprocessing, model training, and evaluation. It serves as the central hub for understanding the project's workflow.

## Dependencies

Ensure the following R packages are installed:

- `rpart`: For constructing decision trees.
- `caret`: For machine learning model training and evaluation.
- `caTools`: For sample splitting and other data manipulation functions.


Install these packages using the following commands:

```
install.packages("rpart")
install.packages("caret")
install.packages("caTools")
```


## Usage

1. **Clone the repository to your local machine:**

    ```bash
    git clone https://github.com/harichselvamc/Decision_Tree_Classifier_for_Advertisement_Dataset.git
    ```

2. **Open and run the `main.ipynb` notebook in your R environment.**

3. **Follow the step-by-step instructions in the notebook to:**
   - Load the dataset
   - Preprocess the data
   - Train the Decision Tree model
   - Evaluate its performance
