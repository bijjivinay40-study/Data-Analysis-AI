# Rwanda IMF Financial Analysis Using LLMs

**Country:** Rwanda (2024–2025)  
**Dataset:** IMF Country Report No. 25/319

## Project Overview
This project uses Large Language Models (LLMs) to analyse Rwanda's IMF Country Report. It extracts financial indicators, summarises important sections, identifies economic risks, and creates a financial dashboard.

## Models Used
- **Qwen3-8B:** Text summarisation, financial extraction and RAG question answering.
- **Mistral-7B-Instruct-v0.3:** LLM-as-a-Judge evaluation.
- **all-mpnet-base-v2:** Text embeddings for FAISS retrieval.

## Tools and Technologies
Python, Google Colab, PyMuPDF, Transformers, Sentence-Transformers, FAISS, Pandas and Matplotlib.

## Project Outputs
- 9 section summaries and an executive summary
- 6 financial indicator fields
- 7 financial themes
- 6 economic strengths and 6 vulnerabilities
- 4 economic trend series
- 4 RAG question-answer evaluations
- High-resolution 4-panel dashboard

## How to Run
1. Open the notebook in Google Colab.
2. Select an A100 GPU runtime.
3. Upload the Rwanda IMF PDF.
4. Run all cells sequentially.

