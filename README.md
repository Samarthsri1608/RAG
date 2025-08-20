# RAG
PDF Question Answering with RAG

This project demonstrates a simple Retrieval-Augmented Generation (RAG) pipeline in Python.
It can answer questions about the pdf, here Harry Potter and the Prisoner of Azkaban, by retrieving the most relevant context from the text and then generating an answer using the Gemini API.

## Features

Download PDF from the web using requests

Extract text from the PDF using pdfplumber

Generate embeddings using SentenceTransformers

Perform semantic search with cosine similarity (scikit-learn)

Use retrieved context with Gemini API for answer generation

End-to-end pipeline: Retrieve → Augment → Generate

## Tech Stack

Python 3.9+

pdfplumber
 – Extract text from PDFs

SentenceTransformers
 – Embedding generation

scikit-learn
 – Cosine similarity search

Requests
 – Download PDF

Google Gemini API
 – Large Language Model for generation

## Workflow

Download the Harry Potter PDF using requests

Extract text using pdfplumber

Split text into chunks and generate embeddings with SentenceTransformers

Perform similarity search using cosine similarity

Send query + top relevant context to Gemini API for final answer

## Usage

Clone the repository

Install dependencies

Set your Gemini API key as an environment variable

Run the script or notebook


## Example queries:

Who is Sirius Black?

What happens in the Shrieking Shack?

Who is the new Defence Against the Dark Arts teacher?

Example

Query:

Who is the new Defence Against the Dark Arts teacher?


Answer (Gemini):

Professor Remus Lupin is the new Defence Against the Dark Arts teacher in the Prisoner of Azkaban.

## Disclaimer

This project is for educational purposes only.

The PDF was used purely as a test dataset to demonstrate a RAG pipeline.

Please respect copyright laws when working with books and PDFs.
