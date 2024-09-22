# **Diabetes Data Analysis and Prediction**

## **Project Overview**

This project focuses on analyzing diabetes data sourced from 130 U.S. hospitals over the years 1999-2008 using AI/ML techniques. The workflow is divided into key stages: data fetching, preprocessing, exploratory data analysis (EDA), and model building, including both machine learning and deep learning approaches. The modular design ensures clarity and maintainability.

## **Dataset**

The dataset is sourced from the UCI Machine Learning Repository. You can find the original dataset and description [here](https://archive.ics.uci.edu/dataset/296/diabetes+130-us+hospitals+for+years+1999-2008).

## **Fetching the Dataset**

You can install the required libraries using the following command:

```bash
cd notebook
python uci_dataset_fetcher.py
```

## **Installation and Dependencies**

To download the dataset, use the `uci_dataset_fetcher.py` script located in the root directory. The script will automatically download and save the dataset locally.

```bash
pip install -r requirements.txt
```

## **Usage**

    1. Run the uci_dataset_fetcher.py script to download the dataset.
    2. Follow the workflow by executing the notebooks in the following order:
        1. preprocessing/data_cleaning.ipynb
        2. preprocessing/data_encoding.ipynb
        3. data_analysis/data_analyses.ipynb
        4. models/random_forest.ipynb
        5. models/Deep_learning_model.ipynb
    3. Review the results and analysis presented in each notebook.

## **Results**

The project demonstrates the application of machine learning and deep learning models to predict diabetes-related outcomes using the dataset. The models provide valuable insights and predictions, which can be applied in healthcare settings.

## **License**

This project is open-source and available under the MIT License.
