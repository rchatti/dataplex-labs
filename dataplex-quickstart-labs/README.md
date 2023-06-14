# Dataplex Quickstart for Cloud Architects and Engineers

## 1. About

Dataplex is a Google Cloud service for Data Governance and Management. Using Dataplex and complementary Data Analytics services, enterprises can stand up Data Mesh architecture in their Google Cloud data estate. To get started with Data Mesh on Google Cloud, one of the prerequisites is knowledge of Dataplex.<br>

This repository is designed to demystify Dataplex features, through a series of self-contained instructional lab modules, with minimal automation, detailed instructions with screenshots for the full developer experience. Once you are well versed with Dataplex, you can proceeed to the advanced labs that feature Data Mesh. The labs are product sponsored and you can expect to see new modules released as and when there are new features/updates to features announced.

<hr>

## 2. Format & Duration
The lab is fully scripted (no research needed), with (fully automated) environment setup, data, code, commands, notebooks, orchestration, and configuration. Clone the repo and follow the step by step instructions for an end to end developer experience. <br><br>

Expect to spend ~8 hours to fully understand and execute if new to GCP and the services and at least ~6 hours otherwise.

<hr>

## 3. Level
L200 - L300 (includes Apache Spark code, Apache Airflow orchestration, Data Science notebooks and more)

<hr>

## 4. Audience
The intended audience is anyone with interest in architecting governance and Data Mesh on Google Cloud.

<hr>

## 5. Prerequisites
Foundational knowledge of governance, and GCP products would be beneficial but is not entirely required, given the format of the lab. Access to Google Cloud is a must unless you want to just read the content.

<hr>

## 6. Goal
Simplify your learning and adoption journey of our product stack for governance with - <br> 
1. Just enough product knowledge of Dataplex for governance<br>
2. Quick start code that can be repurposed for your use cases<br>
3. Terraform for provisioning a variety of Google Cloud data services, that can be repurposed for your use case<br>

<hr>

## 7. Use cases covered
There are various usecases covered including Chicago Crimes Analytics, TelCo Customer Churn Prediction, Cell Tower Anomaly Detection, Icecream Sales Forecasting and more. This is an ever-evovlving lab series, we recommend reviewing the release history for updates on use cases.

<hr>

## 8. Flow of the lab

![LP-00](01-images/landing-page-00.png)   
<br><br>

For your convenience, all the code is pre-authored, so you can focus on understanding product features and integration.

<hr>

## 9. The lab modules
Complete the lab modules in a sequential manner. For a better lab experience, read *all* the modules and then start working on them.

| # | Feature | Module | Duration<br>minutes | 
| -- |:--- | :--- | :--- |
| 01 |  | [Lab environment overview](02-lab-guide/module-01-lab-environment-overview.md) | 10  |
| 02 |  | [Lab environment provisioning with Terraform](02-lab-guide/module-02-terraform-provisioning.md) | 45  |
| 03 | Organize | [Organize your data lake with Dataplex](02-lab-guide/module-03-organize-your-data-lake.md) | 15  |
| 04 | Organize | [Register assets into your Dataplex lake zones](02-lab-guide/module-04-register-assets-into-zones.md) | 15  |
| 05 | Discovery |[Create an Exploration Environment Dataplex Exploration Workbench](02-lab-guide/module-05-create-exploration-environment.md) | 15  |
| 06 | Discovery |[Discovery of structured Cloud Storage objects - study of entities, schemas, automated external table defintions in Dataproc Metastore Service and BigQuery](02-lab-guide/module-06-discovery.md) | 15  |
| 07 | Explore | [Exploring data & metadata with Spark SQL workbench in Dataplex Explore](02-lab-guide/module-07-1-explore-with-spark-sql.md) | 15  |
| 08 | Explore | [Exploring data with Jupyter notebooks in Dataplex Explore](02-lab-guide/module-07-2-explore-with-jupyter-notebooks.md) | 15  |
| 09 | Catalog | [Dataplex Catalog basics](02-lab-guide/module-08-1-catalog-basics.md) | 10  |
| 10 | Catalog | [Creating a tag template in Dataplex and populating tags](02-lab-guide/module-08-2-create-tag-template-for-catalog-entry.md) | 15  |
| 11 | Catalog | [Creating a custom metadata entry in Dataplex Catalog](02-lab-guide/module-08-3-custom-entry-in-catalog.md) | 10  |
| 12 | Catalog | [Create an overview of a Dataplex Catalog entry](02-lab-guide/module-08-4-create-overview-for-catalog-entry.md) | 10  |
| 13 | Catalog | [Searching the Dataplex Catalog](02-lab-guide/module-08-5-search-catalog.md) | 10  |
| 14 | Lineage | [Out of the box lineage capture for BigQuery objects](02-lab-guide/module-09-1-data-lineage-with-bigquery.md) | 15  |
| 15 | Lineage | [BigQuery lineage with Apache Airflow on Cloud Composer for orchestration ](02-lab-guide/module-09-2-data-lineage-with-cloud-composer-bq.md) | 15  |
| 16 | Lineage | [Custom lineage for Apache Spark applications on Cloud Dataproc with Apache Airflow on Cloud Composer pipelines ](02-lab-guide/module-09-3-data-lineage-with-cloud-composer-spark.md) | 30  |
| 17 | Lineage | [Custom lineage for custom entries in Catalog & managing lineage with Dataplex Lineage API](02-lab-guide/module-09-4-custom-lineage.md) | 15  |
| 17 | Profiling | [Data profiling by example](02-lab-guide/module-10-1-data-profiling.md) | 15  |
| 18 | Quality | [Auto Data Quality for completeness - null checks](02-lab-guide/module-11-1a-auto-dq-completeness.md) | 15  |
| 19 | Quality | [Auto Data Quality for validity - pattern checks](02-lab-guide/module-11-1b-auto-dq-validity.md) | 15  |
| 20 | Quality | [Auto Data Quality for validity - allowed values checks](02-lab-guide/module-11-1c-auto-dq-value-set.md) | 15  |
| 21 | Quality | [Auto Data Quality for uniqueness - cell value checks](02-lab-guide/module-11-1d-auto-dq-uniqueness.md) | 15  |
| 22 | Quality | [Auto Data Quality for validity - date checks with SQL row function](02-lab-guide/module-11-1e-auto-dq-sql-row-date.md) | 15  |
| 17 | Lineage | [Custom lineage for custom entries in Catalog with Dataplex Lineage API](02-lab-guide/module-09-4-custom-lineage.md) | 15  |
| 18 | Lineage | [Managing lineage with Dataplex Lineage API](02-lab-guide/module-09-5-manage-lineage.md) | 15  |
| 19 | Quality | [Data profiling by example](02-lab-guide/module-10-1-data-profiling.md) | 15  |
| 20 | Quality | [Auto Data Quality for completeness - null checks](02-lab-guide/module-11-1a-auto-dq-completeness.md) | 15  |
| 21 | Quality | [Auto Data Quality for validity - pattern checks](02-lab-guide/module-11-1b-auto-dq-validity.md) | 15  |
| 22 | Quality | [Auto Data Quality for validity - allowed values checks](02-lab-guide/module-11-1c-auto-dq-value-set.md) | 15  |
| 23 | Quality | [Auto Data Quality for uniqueness - duplicate checks](02-lab-guide/module-11-1d-auto-dq-duplicates.md) | 15  |
| 24 | Quality | [Auto Data Quality for validity - date checks with SQL row function](02-lab-guide/module-11-1e-auto-dq-sql-row-date.md) | 15  |
| 25 | Quality | [Auto Data Quality for validity - volume checks with SQL aggregate function](02-lab-guide/module-11-1f-auto-dq-sql-aggregates.md) | 15  |
| 26 | Quality | [Auto Data Quality for validity - data freshness checks with SQL aggregate function](02-lab-guide/module-11-1g-auto-dq-freshness-check.md) | 15  |
| 27 | Quality | [Auto Data Quality challenge lab](02-lab-guide/module-11-1h-auto-dq-challenge-lab.md) | 15  |
| 28 | Quality | [Data Quality Task - YAML authoring primer -1](02-lab-guide/module-12-1a-dq-task-rule-authoring-1.md) | 30  |
| 29 | Quality | [Data Quality Task - YAML authoring primer -2](02-lab-guide/module-12-1b-dq-task-rule-authoring-2.md) | 10  |
| 30 | Quality | [Data Quality Incident Management](02-lab-guide/module-12-1c-dq-incident-mgmt.md) | 10  |
| 31 | Quality | [Data Quality Dashboard](02-lab-guide/module-12-1d-dq-task-dq-dashboard.md) | 10  |
| 32 | Quality | [Data Quality Score Tags in Dataplex Catalog tags](02-lab-guide/module-12-1e-dq-task-dq-tags.md) | 15  |
| 33 | Quality | [Data Quality process automation with Apache Airflow on Cloud Composer](02-lab-guide/module-12-1f-dq-automation.md) | 15  |
| 34 | Quality | [Data Quality operationalization end to end](02-lab-guide/module-12-1g-dq-complete-automation.md) | 15  |
| 35 | BigLake | [Upgrading external tables to BigLake and performance acceleration](02-lab-guide/module-13-1a-big-lake-basics.md) | 30 |

<hr>

## 10. Dont forget to 
Shut down/delete resources when done to avoid unnecessary billing.

<hr>

## 11. Credits
| # | Google Cloud Collaborators | Contribution  | 
| -- | :--- | :--- |
| 1. | Anagha Khanolkar | Creator |
| 2. | Mansi Maharana | Data Quality Task labs are evolved from [Banking Data Mesh labs](https://github.com/GoogleCloudPlatform/dataplex-labs/tree/main/data-mesh-banking-labs/lab6-data-quality)  |


<hr>

## 12. Contributions welcome
Community contribution to improve the lab is very much appreciated. <br>

<hr>

## 13. Getting help
If you have any questions or if you found any problems with this repository, please report through GitHub issues.

<hr>

## 14. Release History
| Date | Details | 
| -- | :--- | 
| 20230227 |  Initial release |
| 20230320 |  Added modules for Dataplex Auto Data Quality|
| 20230321 |  Added modules for Dataplex Data Quality Tasks|
| 20230328 |  Added additional modules for Dataplex Data Quality Tasks|
| 20230411 |  Added BigLake module|
