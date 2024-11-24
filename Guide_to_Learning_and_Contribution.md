1-🎓 This repository contains a Python script and an Apache Airflow DAG for automating the extraction and preprocessing of data from the BBC News website. Below is an overview of the workflow and the challenges encountered during implementation.

Workflow Overview
Data Extraction: The script utilizes BeautifulSoup and requests libraries to scrape headlines and descriptions from the BBC News homepage.

Text Preprocessing: Text preprocessing is performed using a preprocess_text function, which cleans and formats the extracted text data.

Data Storage and Version Control: Preprocessed data is stored in a CSV file, and Data Version Control (DVC) is implemented to track versions and ensure reproducibility.

Apache Airflow DAG Development: An Airflow DAG named bbc_news_dag is created to automate the data extraction and preprocessing tasks on a daily schedule.

Challenges Encountered
Apache Airflow Installation: The installation of Apache Airflow via Docker presented challenges due to compatibility issues and system dependencies.
DVC Push Issue: An issue was encountered while pushing data to the remote DVC repository, possibly due to synchronization issues with the Google account.
Repository Maintenance
The GitHub repository is maintained with detailed descriptions of the assignment in this README file.

Usage
To run the data preprocessing workflow, follow these steps:

Install the required libraries by running pip install -r requirements.txt.
Execute the Python script fetch_and_preprocess_data.py.
Optionally, set up Apache Airflow and import the bbc_news_dag.py file to automate the workflow.
Conclusion
Despite encountering challenges during Apache Airflow installation and DVC push issues, the implementation successfully automates the extraction and preprocessing of data from the BBC News website. The integration of DVC ensures version control and reproducibility of the data workflow.


2-🌐 Contribution Goals Content Creation Write Blog Posts: Written blogs on medium related to Devops tools which helped me to explore and learn more.
