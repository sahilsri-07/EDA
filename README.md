# Zomato Dataset Exploratory Data Analysis & Feature Engineering

This repository contains an **Exploratory Data Analysis (EDA)** and **Feature Engineering** project on the Zomato restaurant dataset. The goal is to uncover insights into restaurant trends, ratings, costs, and geographic distribution, and prepare the data for potential machine learning modeling.

-----

## 📊 Dataset

The project utilizes two main data files:

1.  **`zomato.csv`**: The primary dataset containing detailed information on restaurants, including:

      * Restaurant ID, Name, City
      * Cuisines
      * Average Cost for two, Currency
      * Rating (Aggregate rating, Color, Text, Votes)
      * Booking and delivery features (Has Table booking, Has Online delivery)

2.  **`Country-Code.xlsx - Sheet1.csv`**: A supplementary file used to map the `Country Code` column in the main dataset to the actual `Country` name.

-----

## 💡 Project Goals

  * Perform a comprehensive **Exploratory Data Analysis (EDA)** to understand the distribution and characteristics of the data.
  * Analyze key relationships, such as the correlation between cost, ratings, and votes.
  * Identify the most popular cuisines and cities.
  * Handle missing values and perform necessary **data cleaning**.
  * Implement **Feature Engineering** techniques, such as:
      * Merging the country codes to get meaningful country names.
      * Creating new features from existing columns (e.g., extracting information from the Cuisines or Locality columns).

-----

## 📂 Repository Structure

  * **`1-eda-feature-engineering.ipynb`**: The main Jupyter Notebook containing all the code for data loading, EDA, data visualization, and feature engineering.
  * **`zomato.csv`**: The raw restaurant data file.
  * **`Country-Code.xlsx - Sheet1.csv`**: The country code mapping file.

-----

## 🛠️ Requirements and Installation

This project requires a standard Python data science environment.

To run the notebook locally, you need the following libraries:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### How to Run

1.  Clone the repository:
    ```bash
    git clone <YOUR_REPO_URL>
    cd <YOUR_REPO_NAME>
    ```
2.  Ensure you have the required libraries installed.
3.  Launch Jupyter Notebook or JupyterLab:
    ```bash
    jupyter notebook
    ```
4.  Open and run the **`1-eda-feature-engineering.ipynb`** notebook.
