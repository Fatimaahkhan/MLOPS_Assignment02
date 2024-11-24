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
 Machine Learning Operations (MLOps) is a discipline that bridges the gap between machine learning (ML) and IT operations, leveraging DevOps principles to optimize the lifecycle of ML models. The objective is to automate processes such as data extraction, model training, deployment, monitoring, and maintenance. A well-designed MLOps pipeline ensures model reliability, scalability, and reproducibility, which are crucial for production-grade AI systems. Key tools like Apache Airflow, Data Version Control (DVC), and MLflow support the automation and versioning of data, models, and code, while Kubernetes and Docker enhance scalability and consistent deployments. The adoption of MLOps enables organizations to streamline ML workflows, reduce time to market, and drive substantial business value.

However, implementing MLOps comes with challenges, including ensuring data quality and governance, managing infrastructure complexity, and fostering cross-functional team collaboration. Best practices for integrating MLOps into DevOps pipelines involve adopting incremental automation, selecting the right tools aligned with existing tech stacks, implementing robust monitoring systems, and encouraging continuous improvement. With its focus on uniting data science and DevOps teams, MLOps helps organizations maintain the relevance and reliability of their AI-driven applications in dynamic, data-intensive environments.
 
[Blog 1](https://medium.com/@fatimajamshaidkhan2/as-organizations-increasingly-leverage-data-driven-strategies-machine-learning-ml-models-have-9225f21878c8)


# Blog 2

# Estimating AWS Costs and Latency for Global Regions
Deploying applications across AWS global regions requires careful cost and latency considerations. This study evaluated an architecture using Amazon EC2 (t3a.small), RDS MySQL (db.t2.micro), and S3 (50GB/month) in three regions—US East (Ohio), Europe (Frankfurt), and Asia Pacific (Mumbai). Cost estimates using the AWS Pricing Calculator revealed that US East (Ohio) is the most cost-effective at $72.52/month, followed by Europe (Frankfurt) at $84.75 and Asia Pacific (Mumbai) at $85.39. Latency tests from Pakistan indicated Mumbai as the best-performing region at 122ms, compared to Frankfurt (186ms) and Ohio (255ms). While Ohio offers the lowest costs, proximity to users in South Asia justifies the higher Mumbai costs for improved performance.

# Cost Optimization Strategies
To minimize expenses, businesses can leverage AWS features like Reserved Instances for long-term commitments, Savings Plans for flexible discounts, and Spot Instances for non-critical tasks. Optimizing storage through Amazon S3’s Infrequent Access and Glacier tiers can reduce costs for seldom-used data. Using AWS CloudFront minimizes data transfer expenses by caching content closer to users. Additionally, consolidating resources within a single region helps avoid cross-region transfer fees. These strategies, when aligned with specific application needs, ensure cost efficiency without compromising performance.

[BLog2](https://medium.com/@fatimajamshaidkhan2/in-todays-globalized-world-ensuring-that-cloud-based-applications-are-fast-efficient-and-232c06b71450)


# CV

# Hi,'I am Fatima Jamshaid 
As a skilled software engineer, I specialize in developing scalable applications using modern technologies, ensuring optimal performance and security. With experience in backend development, cloud computing, and system architecture, I excel in delivering high-quality solutions that meet business needs.

# round_pushpin Connect With me 
# :e-mail:fatimajamshaidkhan2@gmail.com






   
