# Text_summarization_using_Streamlit_and_Groq
This project demonstrates how to build a Streamlit-based text summarization app that leverages the Groq API for fast, high-performance inference of LLMs — all hosted within Google Colab. It enables users to upload documents, extract content, and generate concise summaries instantly, with a shareable web interface powered by ngrok.

🚀 Project Overview

The notebook Text_summarization_using_Streamlit_and_Groq.ipynb provides an end-to-end workflow for:

1. Environment Setup: Installing required packages (streamlit, PyMuPDF4LLM, pandas, groq, pyngrok) and configuring the Colab environment.

2. Groq Integration: Using Groq’s API to access cutting-edge LLMs such as gemma2-9b-it and llama-3.2-3b-preview for text summarization.

3. Streamlit App Generation: Automatically writing a app.py script that builds an interactive UI for document upload, text extraction, and summary generation.

4. Ngrok Deployment: Creating a secure tunnel to serve the Streamlit app online from within Colab, making it easily shareable.

🧩 Key Features

1. Interactive Summarization Interface: Upload PDF or text files and get AI-generated summaries in seconds.

2. Multiple Model Options: Users can switch between Groq-hosted models (Gemma2_9B, LLaMA 3.2) for experimentation.

3. PDF Text Extraction: Integrates PyMuPDF4LLM for parsing and reading multi-page documents.

4. Real-Time Deployment: Instantly launches a live Streamlit app via ngrok without local setup.

⚙️ Tech Stack

Python, Streamlit, Groq API, PyMuPDF4LLM, Ngrok, Google Colab

💡 Use Cases

1. Automatic document summarization for research papers, reports, or contracts.

2. Building AI-powered summarization tools for business or education.

3. Rapid prototyping of Groq LLM-based applications in Colab.

📦 Output

Once executed, the notebook prints a public Streamlit app URL via ngrok. Users can open the link to interact with the summarizer directly through a web interface, selecting models and generating summaries in real time.
