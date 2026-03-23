# InsightForge-AI-BI-Capstone

**AI-Powered Business Intelligence Assistant**

---

## Project Description

InsightForge is an end-to-end AI-powered Business Intelligence assistant that transforms raw sales and business data into actionable insights through a conversational AI interface. Built using Python, LangChain, RAG, FAISS, LLMs, Streamlit, and Pandas, it allows users to explore sales performance, customer behavior, and trends interactively.

This project demonstrates skills in data analysis, visualization, AI-powered retrieval, prompt engineering, and building portfolio-ready applications.

---

## Features

- **AI Chat Assistant:** Ask questions about sales data and get accurate, data-grounded responses.  
- **Interactive Dashboard:** Explore metrics via multiple visualizations:  
  - Monthly Sales Trend  
  - Product Performance Comparison  
  - Regional Sales Analysis  
  - Customer Demographics & Satisfaction  
- **RAG-Powered Intelligence:** FAISS vector store enables retrieval-augmented generation for smarter AI answers.  
- **Live Data Insights:** Pandas-based retriever injects live statistics for precise context in AI responses.  
- **Model Evaluation:** QAEvalChain evaluates AI answers against ground-truth QA pairs.  
- **Memory & Stateful Conversations:** ConversationBufferMemory & LangGraph allow multi-turn context-aware interactions.  
---

## Dataset

- **sales_data.csv** – 2,500+ rows  
  Fields: Date, Product (Widget A-D), Region (North/South/East/West), Sales, Customer_Age, Customer_Gender, Customer_Satisfaction (0-5)  
- **records.xlsx** – supplemental business records  
- **PDF reports** – optional for knowledge base ingestion  

---

## Tech Stack

| Layer | Technology | Purpose |
|-------|------------|---------|
| Data Processing | Pandas, OpenPyXL | Load, clean, summarize data |
| Embeddings & Retrieval | FAISS + sentence-transformers | RAG vector store |
| LLM Orchestration | LangChain, LangGraph | Prompt chains, memory management |
| LLM Backend | OpenAI GPT / Groq API | Fast inference |
| PDF Ingestion | PyPDF, pdf2image | Load reports into knowledge base |
| Evaluation | QAEvalChain | Automated model evaluation |
| UI | Streamlit | Interactive dashboard |
| Visualization | Matplotlib, Seaborn | Charts & plots |

---

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/yourusername/InsightForge-AI-BI-Capstone.git
cd InsightForge-AI-BI-Capstone
