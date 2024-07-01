# Advanced-RAG-Series
This repository hosts an advanced LLM-based chatbot for Retrieval Augmented Generation (RAG) and Q&A interactions with various databases such as VectorDB, GraphDB, SQLite, CSV, XLSX, and more. 

## General structure of the projects:

```
Project-folder
  ├── README.md           <- Primary README file for developers.
  ├── HELPER.md           <- Additional information for project execution.
  ├── .env                <- Environment configuration file.
  ├── .here               <- Marker indicating project root.
  ├── configs             <- Configuration files in YML format.
  ├── explore             <- Exploration notebooks and YouTube teaching material.
  ├── data                <- Sample data for the project.
  ├── src                 <- Source code for project execution.
  |   └── utils           <- Essential project modules.
  └── images              <- Images for the user interface and README.
```

## Key Notes:
- Azure OpenAI Usage: All projects use Azure OpenAI. To switch to OpenAI API, update the credentials and model configurations accordingly.
- Informative Column Names: When using LLM agents with databases, informative column names facilitate easier navigation.
- Read-Only Databases: Use databases with READ privileges only to prevent data manipulation by users.
- Query Language Familiarity: Knowledge of database query languages like Pandas for Python, SQL, and Cypher enhances the ability to ask better questions and interact effectively with the graph agent.
- 
## Project description:
<!-- ==================================== -->
<!-- Q&A-and-RAG-with-SQL-and-TabularData -->
<!-- ==================================== -->
<a id="Chat-SQL"></a>
<h3><a style=" white-space:nowrap; " href="https://github.com/Farzad-R/Advanced-RAG-Series/tree/main/Q&A-and-RAG-with-SQL-and-TabularData"><b>Q&A-and-RAG-with-SQL-and-TabularData:</b></a></h3>

`Q&A-and-RAG-with-SQL-and-TabularData` is a chatbot project that utilizes <u>GPT 3.5</u>, <u>Langchain</u>, <u>SQLite</u>, and <u>ChromaDB</u> and allows users to interact (perform <u>Q&A</u> and <u>RAG</u>) with SQL databases, CSV, and XLSX files using natural language.


**Features:**
- Chat with SQL data.
- Chat with preprocessed CSV and XLSX data.
- Chat with uploaded CSV and XSLX files while interacting with the user interface.
- RAG with Tabular datasets.

**Databases:**
- Diabetes dataset: [Link](https://www.kaggle.com/datasets/akshaydattatraykhare/diabetes-dataset?resource=download&select=diabetes.csv)
- Cancer dataset: [Link](https://www.kaggle.com/datasets/rohansahana/breast-cancer-dataset-for-beginners?select=train.csv)
- Chinook SQL database: [Link](https://database.guide/2-sample-databases-sqlite/)

