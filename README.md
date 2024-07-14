PDF Text Extraction, Embedding, and Question Answering Pipeline

This project demonstrates a comprehensive pipeline for extracting text from PDF documents, embedding the text using Hugging Face models, and performing question answering using a retrieval-based approach with LangChain and OpenAI's GPT models.

Features
PDF Text Extraction: Extracts text from uploaded PDF files.
Text Splitting: Splits extracted text into manageable chunks for embedding.
Text Embedding: Uses Hugging Face embeddings for text chunks.
Question Answering: Utilizes LangChain and Hugging Face pipelines for answering questions based on the embedded text.

How It Works

PDF Text Extraction:
Upload a PDF file and extract its text content using a PDF reader library.

Text Splitting:
Split the extracted text into smaller, manageable chunks to facilitate embedding and retrieval.

Text Embedding:
Convert the text chunks into high-dimensional vectors using Hugging Face embeddings, allowing for efficient similarity searches.

Question Answering:
Retrieve relevant text chunks based on a user query. Use a pre-trained language model to generate answers from the retrieved chunks.
