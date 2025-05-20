PDF & DOCX Summarizer Application
Live Demo

Overview
This Streamlit-based app enables users to upload PDF or DOCX files and receive concise AI-generated summaries of the document content. Leveraging Google Generative AI, it extracts text from uploaded files and produces clear, readable summaries. Users can easily copy the summary to their clipboard.

Features
File Upload: Upload PDF or DOCX documents with ease.

Text Extraction: Extracts text seamlessly from PDFs and DOCX files.

AI-Powered Summarization: Utilizes Google Generative AI for accurate and meaningful summaries.

Clipboard Copy: Copy summaries instantly with a single click.

Prerequisites
Before running the app, ensure you have the following installed:

Python 3.7 or later

Streamlit

Google Generative AI API key

PyPDF2 (for PDF text extraction)

python-docx (for DOCX text extraction)

Pyperclip (for clipboard support)

Installation & Running
Clone the repository:


git clone <repository-url>
cd <repository-folder>
Install dependencies:


pip install -r requirements.txt
Set your Google Generative AI API key as an environment variable:


export GOOGLE_API_KEY="your_api_key_here"
Run the Streamlit app:


streamlit run app.py
Open your browser at http://localhost:8501 to access the app.
