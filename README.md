# Devops Course 2024

This repository contains the work completed for the DevOps Course 2024 assignment, which includes:

Guide to Learning and Contribution
View Blog Summaries
Sample repo from the internet and applying DevOps tooling.Pick and choose (your existing) knowledge and expand it to guide.
A sample landing page with my CV.
 # Documentation:


   # Quick Guide to DevOps Implementation in the Data Preprocessing Workflow

   This repository applies DevOps principles to automate and streamline a data preprocessing workflow for scraping and processing BBC News website data. Here's a breakdown of how DevOps is utilized and a guide to implementing it:
   # Key DevOps Practices Applied:

1-Automation with Apache Airflow:
An Airflow DAG (bbc_news_dag) automates the daily execution of data extraction and preprocessing tasks, reducing manual intervention and ensuring consistency.
2-Version Control with DVC:
Data Version Control (DVC) tracks versions of the preprocessed data stored in CSV files. This ensures reproducibility, collaboration, and rollback capabilities.
3-Code and Workflow Management:
A structured Python script (fetch_and_preprocess_data.py) performs extraction and preprocessing using libraries like BeautifulSoup and requests.
The GitHub repository maintains documentation and code organization, following DevOps best practices for codebase management.
4-Infrastructure as Code (IaC):
The use of Docker simplifies setting up and running Apache Airflow, encapsulating dependencies and ensuring a consistent environment.

# Step-by-Step Guide to Implementing the Workflow:
"Setting up Environmnet
. Install Python and ensure pip is available.
Clone the repository:
git clone <repository-url>
cd <repository-directory>
.Install required dependencies:
pip install -r requirements.txt
.Run the python script
python fetch_and_preprocess_data.py
.intialzie DVC
dvc init
dvc add preprocessed_data.csv
.Track changes 
git add preprocessed_data.csv.dvc .gitignore
git commit -m "Add preprocessed data with DVC"
dvc push
.automate with apache workflow
docker-compose up
# Conclusion
This workflow demonstrates the effective application of DevOps practices, combining automation, version control, and reproducibility. By integrating Airflow and DVC, the pipeline ensures consistent and scalable data preprocessing.


# Blog summaries 
 # Blog 1
 
[Blog 1](https://medium.com/@fatimajamshaidkhan2/as-organizations-increasingly-leverage-data-driven-strategies-machine-learning-ml-models-have-9225f21878c8)
[BLog2](https://medium.com/@fatimajamshaidkhan2/in-todays-globalized-world-ensuring-that-cloud-based-applications-are-fast-efficient-and-232c06b71450)




   
