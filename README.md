### Hi, I'm Pedro, a Senior Data Engineer

I build data platforms that are **cheap to run, easy to trust, and boring in production**. For 5+ years I've been moving enterprise data (SAP, PIM, ERP) into cloud lakehouses. I work at Bosch, live in Porto, Portugal, and I'm **open to B2B contracts**.

**What I can do for your team**

- **Get data out of SAP** (ECC / S/4HANA) and into a modern lakehouse: incremental loads, CDC, and the SAP quirks handled (leading zeros, `00000000` dates, currency decimal shifts)
- **Cut platform cost**: I replaced ~€60k of Talend licensing with a pipeline stack that costs ~€150/month on AWS
- **Make pipelines visible**: with only 2 Talend licenses for 3 teams, I built a self-service monitoring app (Streamlit behind Nginx) so everyone on the VPN can check job health
- **Ship it properly**: infrastructure as code, CI/CD, tests, data-quality checks, and docs people actually read

### Featured projects

| Project | What it shows | Stack |
|---|---|---|
| [**SAP → Iceberg Lakehouse**](https://github.com/pedro-mesquita7/sap-iceberg-lakehouse) · [live docs](https://pedro-mesquita7.github.io/sap-iceberg-lakehouse/) | SAP Order-to-Cash data with ODP-style CDC into Iceberg: SAP format quirks handled, SCD2 from change events, enforced contracts. One command runs it. | Iceberg · dbt · Dagster · DuckDB · GitHub Actions |
| [**IronLog**](https://github.com/pedro-mesquita7/IronLog) · [live app](https://pedro-mesquita7.github.io/IronLog/) | A serverless PWA with a CDC data lake behind it, built entirely in Terraform. It runs for **~€0.07/month**. | AWS Lambda · DynamoDB Streams · S3 · dbt + Athena · Terraform · React |
| [**OpenClaw Security Lakehouse**](https://github.com/pedro-mesquita7/openclaw-security-lakehouse) | A medallion lakehouse with SCD Type 2 history, risk scoring and a dashboard that refreshes daily | Databricks · Delta Lake · PySpark · Asset Bundles · GitHub Actions |
| [**Portfolio site**](https://pedro-mesquita7.github.io/pm-portfolio/) | Work projects, impact metrics, resume | HTML · CSS · JS |

### Tech stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white)
![Apache Iceberg](https://img.shields.io/badge/Iceberg-2B6CB0?style=flat-square&logo=apache&logoColor=white)
![Delta Lake](https://img.shields.io/badge/Delta_Lake-00ADD4?style=flat-square&logo=delta&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![Talend](https://img.shields.io/badge/Talend-FF6D70?style=flat-square&logo=talend&logoColor=white)
![SAP](https://img.shields.io/badge/SAP-0FAAFF?style=flat-square&logo=sap&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

### Get in touch

[Portfolio](https://pedro-mesquita7.github.io/pm-portfolio/) · [LinkedIn](https://www.linkedin.com/in/pedro-mesquita/) · [Email](mailto:mesquitapedro17@gmail.com)
