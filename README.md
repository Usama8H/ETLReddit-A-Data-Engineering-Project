**Motivation:**

Project was based on an interest in Data Engineering and the types of Q&A found on the official subreddit.

It also provided a good opportunity to develop skills and experience in a range of tools. As such, project is more complex than required, utilising dbt, airflow, docker and cloud based storage.

**Architecture:**

<img width="592" alt="workflow" src="https://github.com/Usama8H/Reddit_Pipeline/assets/147407087/8f07bce1-513f-4cb6-a212-206e24690f6f">


1. Extract data using Reddit API
2. Load into AWS S3
3. Copy into AWS Redshift
4. Transform using dbt
5. Create PowerBI or Google Data Studio Dashboard
6. Orchestrate with Airflow in Docker
7. Create AWS resources with Terraform

**Output:**

<img width="889" alt="GDS-Dashboard" src="https://github.com/Usama8H/Reddit_Pipeline/assets/147407087/21f3b64b-327f-404c-af6b-0fe4c5df05d5">

Final output from Google Data Studio. Note that the dashboard is reading from a static CSV output from Redshift. Redshift database was deleted so as not to incur cost.
