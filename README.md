# LinkedIn Job Market RAG Chatbot
This project is a Retrieval-Augmented Generation (RAG) chatbot that leverages LinkedIn job descriptions to provide intelligent insights for both job seekers and companies.
Kaggle Dataset used in this project: https://www.kaggle.com/datasets/arshkon/linkedin-job-postings/data

## Key Use Cases
For Job Seekers: Identify the best-matching job roles based on your specific skill set, understand what skills are commonly needed for a role, etc.

For Companies: Analyze hiring trends of other organizations to align recruitment expectations with the current job market.

## Technology Stack
* Data Cleaning: PySpark
* LLM Inference: Groq API
* Vector Storage: Chroma Cloud
* Retrieval System: Hybrid search combining semantic search (all-MiniLM-L6-v2) and keyword search (Chroma Splade), aggregated using Reciprocal Rank Fusion (RRF)
* User Interface: Gradio

## Getting Started
Ensure you have active access to Chroma Cloud, the Groq API, and Apache Spark configured in your environment before running the application.

To start the user interface, execute the following command in your terminal:
```python gradioUI.py```
