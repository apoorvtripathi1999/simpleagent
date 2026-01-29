# Simple RAG Application

This project implements a Retrieval-Augmented Generation (RAG) system to analyze student feedback using Groq and ChromaDB.

## Features
- **Data Source**: Loads student feedback from `summarized_student_feedback.xlsx`.
- **Vector Database**: Uses ChromaDB to store and retrieve relevant feedback.
- **LLM**: Uses Groq (Llama 3) for generating answers.
- **Framework**: Built with LangChain.

## Setup
1. Create a virtual environment and activate it.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Create a `.env` file with your keys:
   ```
   GROQ_API_KEY=your_groq_api_key
   HUGGINGFACE_API_KEY=your_huggingface_api_key
   ```
4. Run the notebook `simple_rag.ipynb`.

## Files
- `simple_rag.ipynb`: Main notebook containing the RAG logic.
- `summarized_student_feedback.xlsx`: Input data containing student feedback.
