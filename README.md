📊 Data Validation Pipeline using Great Expectations

📌 Overview

This project demonstrates a complete data validation pipeline built using Great Expectations and Python.
It validates structured tabular data by enforcing data quality rules such as schema checks, null validation, range validation, and consistency checks.

The project simulates a real-world data quality workflow used in analytics, data engineering, and ETL pipelines.

🚀 Features

Automated data quality checks

Column-level validations (type, nulls, ranges)

Schema enforcement

Data profiling and documentation

HTML-based Data Docs generation

Easily extendable to production pipelines

🛠️ Technologies Used

Python 3.10

Great Expectations 0.17.x

Pandas

Jupyter Notebook

📂 Project Structure
data-validation-project/
│
├── data/
│   └── amazon.csv
│
├── great_expectations/
│   ├── expectations/
│   ├── validations/
│   └── data_docs/
│
├── data_validation_pipeline.ipynb
├── requirements.txt
└── README.md

📋 Validation Rules Implemented

✔ Column existence checks
✔ Non-null value checks
✔ Value range validation (e.g., ratings between 0–5)
✔ Data type validation
✔ Automated reporting via Data Docs

▶️ How to Run the Project
1️⃣ Install Dependencies
pip install -r requirements.txt

2️⃣ Run the Notebook
jupyter notebook


Open data_validation_pipeline.ipynb and run all cells.

📊 Output

Validation results printed in the notebook

HTML data quality report generated in:

great_expectations/data_docs/


Clear pass/fail summary for each validation rule

🧪 Example Validations

product_id must not be null

rating must be between 0 and 5

discounted_price must be a positive number

📈 Use Cases

Data quality validation before analytics

ETL pipeline validation

Data engineering projects

Machine learning preprocessing checks

🧠 Learnings

This project demonstrates:

How to build reproducible data quality pipelines

How to use Great Expectations effectively

Best practices for validating structured datasets
