# Customer Transaction Analysis

This Python script analyzes a synthetic dataset of customer transactions to identify customer spending patterns, classify customers, and identify VIP customers for targeted marketing campaigns.

## Overview

The script performs the following analyses:

1.  **Customer Classification:** Classifies customers into "High-Spender" and "Occasional" categories based on their total transaction amounts.
2.  **Buying Pattern Identification:** Calculates the average number of transactions per month for each customer to understand their purchasing frequency.
3.  **VIP Customer Identification:** Identifies VIP customers as the top 10% of spenders, suitable for targeted marketing campaigns.
4.  **Data Visualization:** Generates a histogram to visualize the distribution of customer spending and highlights the VIP threshold.


## Prerequisites

* Python 3.x
* Pandas (`pip install pandas`)
* NumPy (`pip install numpy`)
* Matplotlib (`pip install matplotlib`)


## Usage

1.  **Clone the repository (if applicable):**
    ```bash
    git clone [repository URL]
    cd [repository directory]
    ```
2.  **Install the required libraries:**
    ```bash
    pip install pandas numpy matplotlib
    ```
3.  **Run the Python script:**
    ```bash
    python your_script_name.py
    ```
    (Replace `your_script_name.py` with the actual name of your script.)

## Script Details

* The script generates a synthetic dataset of customer transactions with random customer IDs, transaction dates, and transaction amounts.
* Customers are classified as "High-Spender" if their total transaction amount exceeds $2000, and "Occasional" otherwise.
* The script calculates the average number of transactions per month for each customer to understand their buying patterns.
* VIP customers are identified as those in the top 10% of total spenders.
* The customer spending distribution is visualized using a histogram, with the VIP threshold indicated by a red dashed line.
* The script uses a fictional `ace_tools` library to display the resulting dataframe. Replace this with either print statements, or another method of displaying dataframes.

## Output

The script generates the following outputs:

* A DataFrame containing customer IDs, total transaction amounts, customer types, average transactions per month, and VIP customer flags.
* A histogram displaying the distribution of customer spending, with the VIP threshold marked.

## Customization

* You can modify the number of customers and transactions by changing the `num_customers` and `num_transactions` variables.
* The threshold for classifying high spenders and the VIP threshold can be adjusted as needed.
* The date range can be changed by modifying the start date in the transaction date generation.
* The range of transaction amounts can be changed by modifying the parameters in the `np.random.uniform()` call.

## Note

This script generates a synthetic dataset for demonstration purposes. For real-world applications, you should replace the synthetic data generation with data from your actual transaction database.