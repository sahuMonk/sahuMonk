# Hi, I'm Mayank Sahu 👋

### Data Engineer | Azure | Databricks | PySpark | SQL

I'm a Data Engineer with **2+ years of experience** focused on building scalable data pipelines and analytics-ready data platforms using Microsoft Azure.

I enjoy working with large datasets, designing efficient ETL/ELT pipelines, implementing incremental data processing, and building reliable data solutions using modern cloud technologies.

---

## 🚀 About Me

* 🔹 Data Engineering professional with 2+ years of experience
* 🔹 Hands-on experience with **Azure Data Factory, ADLS Gen2 and Azure Databricks**
* 🔹 Strong working knowledge of **PySpark, Apache Spark, Python and SQL**
* 🔹 Experience building **ETL/ELT pipelines**
* 🔹 Implemented **incremental loading using watermark-based processing**
* 🔹 Worked with **Medallion Architecture (Bronze → Silver → Gold)**
* 🔹 Experience with **Delta Lake** and analytics-ready datasets
* 🔹 Interested in scalable cloud data platforms and big data engineering
* 🔹 Currently looking for opportunities in **Data Engineering**

---

## 🛠️ Tech Stack

## 🛠️ Languages and Tools

<h3 align="center">☁️ Cloud & Data Engineering</h3>

<p align="center">

<a href="https://azure.microsoft.com/" target="_blank">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/azure/azure-original.svg" height="55" alt="Azure" />
</a>
&nbsp;&nbsp;&nbsp;

<a href="https://azure.microsoft.com/products/data-factory/" target="_blank">
<img src="https://code.benco.io/icon-collection/azure-docs/data-factory.svg" height="55" alt="Azure Data Factory" />
</a>
&nbsp;&nbsp;&nbsp;

<a href="https://azure.microsoft.com/products/storage/data-lake-storage/" target="_blank">
<img src="https://iconvault.app/icon/azure-core--azure-data-lake-storage-gen2-adls.svg" height="55" alt="ADLS Gen2" />
</a>
&nbsp;&nbsp;&nbsp;

<a href="https://www.databricks.com/" target="_blank">
<img src="https://cdn.simpleicons.org/databricks" height="55" alt="Databricks" />
</a>
&nbsp;&nbsp;&nbsp;

<a href="https://spark.apache.org/" target="_blank">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/apachespark/apachespark-original.svg" height="55" alt="Apache Spark" />
</a>

</p>

<h3 align="center">💻 Programming & Databases</h3>

<p align="center">

<a href="https://www.python.org/" target="_blank">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original.svg" height="55" alt="Python" />
</a>
&nbsp;&nbsp;&nbsp;

<a href="https://www.postgresql.org/" target="_blank">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/postgresql/postgresql-original.svg" height="55" alt="PostgreSQL" />
</a>
&nbsp;&nbsp;&nbsp;

<a href="https://www.mysql.com/" target="_blank">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/mysql/mysql-original.svg" height="55" alt="MySQL" />
</a>
&nbsp;&nbsp;&nbsp;

<a href="https://git-scm.com/" target="_blank">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/git/git-original.svg" height="55" alt="Git" />
</a>
&nbsp;&nbsp;&nbsp;

<a href="https://github.com/" target="_blank">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/github/github-original.svg" height="55" alt="GitHub" />
</a>
&nbsp;&nbsp;&nbsp;

<a href="https://code.visualstudio.com/" target="_blank">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/vscode/vscode-original.svg" height="55" alt="VS Code" />
</a>
&nbsp;&nbsp;&nbsp;

<a href="https://jupyter.org/" target="_blank">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/jupyter/jupyter-original.svg" height="55" alt="Jupyter" />
</a>

</p>

<h3 align="center">🔄 Data Engineering Concepts</h3>

<p align="center">

<img src="https://img.shields.io/badge/ETL%2FELT-0078D4?style=for-the-badge" alt="ETL ELT" />
&nbsp;
<img src="https://img.shields.io/badge/Incremental_Loading-0078D4?style=for-the-badge" alt="Incremental Loading" />
&nbsp;
<img src="https://img.shields.io/badge/Delta_Lake-00ADD8?style=for-the-badge" alt="Delta Lake" />
&nbsp;
<img src="https://img.shields.io/badge/Medallion_Architecture-0078D4?style=for-the-badge" alt="Medallion Architecture" />
&nbsp;
<img src="https://img.shields.io/badge/SQL-336791?style=for-the-badge" alt="SQL" />
&nbsp;
<img src="https://img.shields.io/badge/PySpark-E25A1C?style=for-the-badge" alt="PySpark" />

</p>


## 📂 Featured Data Engineering Projects

### 🥇 Azure End-to-End Data Engineering Pipeline

**Azure Data Factory → ADLS Gen2 → Databricks → PySpark → Delta Lake**

An end-to-end Azure data engineering project implementing a modern Medallion Architecture.

**Key Features:**

* Metadata-driven and parameterized ADF pipelines
* Incremental data loading
* Watermark-based processing
* Bronze, Silver and Gold layers
* PySpark data transformation
* Data cleansing and validation
* Delta Lake storage
* Analytics-ready datasets

🔗 **[View Project →](https://github.com/sahuMonk/Azure_DE_Project)**

---

### 🥈 Paris 2024 Olympic Data Engineering Project

An Azure-based data engineering pipeline designed to ingest, transform and prepare Olympic datasets for analytics.

**Technologies:**

`Azure Data Factory` · `ADLS Gen2` · `Azure Databricks` · `PySpark` · `SQL`

🔗 **[View Project →](https://github.com/sahuMonk/Paris-2024-Olympic-DE-Project)**

---

### 🥉 Adventure Works Data Engineering Project

A data engineering project demonstrating data ingestion, transformation and analytics workflows using Azure data engineering technologies.

**Technologies:**

`Azure` · `ADF` · `Databricks` · `PySpark` · `SQL`

🔗 **[View Project →](https://github.com/sahuMonk/Adventure-Works-Data-Engineering-Project)**

---

## 🏗️ Data Engineering Architecture

```text
             DATA SOURCES
                  │
       ┌──────────┼──────────┐
       │          │          │
    Database     Files       API
       │          │          │
       └──────────┼──────────┘
                  ↓
        Azure Data Factory
                  ↓
            ADLS Gen2
                  ↓
        ┌─────────────────┐
        │  Bronze Layer   │
        │    Raw Data     │
        └────────┬────────┘
                 ↓
        Azure Databricks
              PySpark
                 ↓
        ┌─────────────────┐
        │  Silver Layer   │
        │ Cleaned Data    │
        └────────┬────────┘
                 ↓
        ┌─────────────────┐
        │   Gold Layer    │
        │ Business Data   │
        └────────┬────────┘
                 ↓
            Analytics
```

---

## 📜 Certifications

* 🎓 **Databricks Data Engineer Associate**
* ☁️ **Microsoft Azure Fundamentals — AZ-900**

---

## 🎓 Education

**Bachelor of Technology — Computer Science & Engineering**

Samrat Ashok Technological Institute, Vidisha
2023

---


## 🤝 Let's Connect

<a href="https://www.linkedin.com/in/mayank-sahu-6b89681a1/">
<img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/linkedin/default.svg"
       width="80"
       height="50"
       alt="linkedin logo" />
</a>

<a href="mailto:mayanksahu212@gmail.com">
  <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/gmail/default.svg"
       width="80"
       height="50"
       alt="gmail logo" />
</a>

---

### 💡 Currently looking for Data Engineering opportunities

**Azure | Databricks | PySpark | SQL | ETL/ELT**

<!--
**sahuMonk/sahuMonk** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
