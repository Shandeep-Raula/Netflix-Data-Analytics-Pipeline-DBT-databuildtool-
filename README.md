# 📺 Netflix Data Analysis with DBT

Welcome to the **Netflix Data Analysis** project, built using **DBT (Data Build Tool)**.  
This project demonstrates how to transform and analyze Netflix viewing data with modern data engineering practices.

---

## 📌 Project Overview

This project shows how to:
- Build modular, reusable SQL models with DBT.
- Create a clear data lineage.
- Test and document your analytics pipeline.
- Generate business insights from raw Netflix data.

---

## Working Architecture
![](https://github.com/Shandeep-Raula/Netflix-Data-Analysis-DBT-databuildtool-/blob/main/project_workflow.jpg)

## 📂 Project Structure
```
├── models/                # DBT models (staging, intermediate, marts)
│   ├── staging/           # Raw data cleaned and staged
│   ├── intermediate/      # Business logic transformations
│   └── marts/             # Final models for analysis & reporting
├── snapshots/             # Data versioning (optional)
├── tests/                 # Custom data tests
├── macros/                # Custom Jinja macros
├── analyses/              # Ad-hoc analyses (if any)
├── dbt_project.yml        # DBT project configuration
└── README.md              # Project documentation
```
## Tools
- Snowflake , DBT , VS Code , AWS(S3,IAM)



