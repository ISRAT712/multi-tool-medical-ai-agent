# Building a Multi-Tool AI Agent to Interact with Medical Datasets and Web

## Project Overview

This project develops a multi-tool AI agent that interacts with medical datasets stored in SQLite databases and retrieves general medical information from the web.

The agent automatically selects the appropriate tool based on the user's question.

## Datasets Used

- Heart Disease Dataset: 1025 records
- Cancer Prediction Dataset: 1500 records
- Diabetes Dataset: 768 records

## Technologies Used

- Python
- Pandas
- SQLite
- SQLAlchemy
- LangChain
- Google Gemini
- DuckDuckGo Web Search
- Google Colab

## Database Tools

- HeartDiseaseDBTool
- CancerDBTool
- DiabetesDBTool

## Web Search Tool

- MedicalWebSearchTool

This tool searches for general medical information such as symptoms, causes, prevention, treatment, definitions, and risk factors.

## Agent Routing Logic

- Dataset-related questions are routed to SQLite database tools.
- General medical questions are routed to the web search tool.

## Example Questions

- How many records are in the heart disease dataset?
- What is the average age in the cancer dataset?
- What is the average glucose level in the diabetes dataset?
- What are the common symptoms of diabetes?
- How can cancer be prevented?

## Verified Statistics

| Dataset | Total Records | Verified Statistic |
|---|---:|---|
| Heart Disease | 1025 | Average Age: 54.43 |
| Cancer | 1500 | Average Age: 50.32 |
| Diabetes | 768 | Average Glucose: 120.89 |

## Project Files

- Medical_AI_Agent.ipynb
- README.md
- medical_databases.zip
- heart_disease.db
- cancer.db
- diabetes.db

## Disclaimer

This project is developed for educational and research purposes only. It does not provide personal medical diagnosis and should not replace professional medical advice.
