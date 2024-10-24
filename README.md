# PDF (Retrieval-Augmented Generation)

This repository contains two main components:

1. **pdfrag.py** - A PDF processing and question-answering app built using Streamlit and Google's Gemini model.
2. **Websearch_agent.py** - A web search agent that performs searches and answers questions based on web search results.

## Features

- PDF text extraction using `PyPDF2`.
- Chunking of text and creating a FAISS vector store for similarity searches.
- Integration with Google's Gemini model for QA functionality.
- Web search and QA using `transformers`.

## Requirements

Before running the application, ensure that the following Python dependencies are installed. You can install them using `pip`:

```bash
pip install -r requirements.txt
streamlit run pdfrag.py    
```
![image](https://github.com/user-attachments/assets/5501ebce-66f2-4847-b43a-09c9106fb1b8)
