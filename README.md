# YouTube-Analytics-using-AWS
This project leverages AWS services to transform raw YouTube data into structured formats, automate ETL workflows, and visualize insights, demonstrating a comprehensive data analytics solution.

## Data Flow:
![Data Flow 2](https://github.com/user-attachments/assets/cc249e9d-7bb4-4b17-ad31-5c3616695e55)


## Following is a list of the AWS services used in the project and how they were utilized:

### 1) AWS S3 (Simple Storage Service):
Landing Area: Used to store raw data ingested from source systems.
Cleansed/Enriched: Stores data that has been processed and cleaned.
Analytics/Reporting: Holds the final data ready for analysis and reporting.

### 2) AWS IAM (Identity and Access Management):
Manages access and permissions for AWS services and resources, ensuring secure operations.

### 3) AWS Glue:
Data Processing: Crawls and catalogs the raw data stored in S3, creating a metadata repository.
Data Catalog: Maintains metadata about data stored in the data lake, making it searchable and easier to manage.

### 4) AWS Lambda:
Performs ETL (Extract, Transform, Load) operations, transforming raw JSON data into structured formats like Parquet and automating data processing workflows.

### 5) AWS Athena:
Provides analytical data access, allowing SQL queries on the data stored in S3. Used for querying both raw and processed data.

### 6) Amazon QuickSight:
Used for data visualization, creating dashboards and reports to uncover insights from the processed data.

### 7) AWS CloudWatch:
Monitors the performance and health of the AWS services involved in the project, setting alerts for any issues.
