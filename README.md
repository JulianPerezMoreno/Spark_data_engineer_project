This is a personal little project to learn how to use Apache Spark for Data Engineering.

**Note:** A large file has been deleted from all branches and local/remote repositories:
`spark-4.0.1-bin-hadoop3/yarn/spark-4.0.1-yarn-shuffle.jar`

This is because this project is not using the cluster system of YARN. If needed, Spark can be downloaded again in a separate folder to include this file.

**How to Use:**

1.  **Clone the repository:**
    ```bash
    git clone <your_repository_url>
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd Spark_data_engineer_project
    ```
3.  **Run the main script:**
    ```bash
    # Replace with your actual script name
    python main.py
    ```
4.  **Dependencies:**
    *   Make sure you have Python and the necessary libraries installed. You can install them using pip:
        ```bash
        pip install -r requirements.txt  # If you have a requirements.txt file
        ```

**What's Next?**

*   Explore the existing code and modify it to suit your needs.
*   Add new Spark functionalities and features.
*   Consider deploying the project to a local Spark environment.


This project is designed to explore Market Risk Modeling techniques using Apache Spark.  
It uses historical financial data from the EURO STOXX 50 index, stored in Parquet format for efficient processing.  
GDP from european countries (Export the dataframe containing cleaned data on Gross Domestic Product (GDP) and its main components (output, expenditure, and income) in Parquet format).
Tasas de interés de referencia del Banco Central Europeo (BCE)
Main dataset:  
- `euro_stoxx50.parquet`
- 'GDP_and_main_components.parquet'
Key_ECB_interest_rates.pdf y Interest_rate_statistics(2004_EU_Member_States_&_ACCBs)(39).csv