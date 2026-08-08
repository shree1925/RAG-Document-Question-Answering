# RAG-Based Document Question Answering System

## Overview

This project implements a Retrieval-Augmented Generation (RAG) system that answers questions using information retrieved from PDF documents.

The system combines document processing, semantic embeddings, vector search, and generative AI into an end-to-end question-answering pipeline.

## Architecture

PDF Documents
↓
Text Extraction
↓
Text Cleaning
↓
Text Chunking
↓
Sentence Embeddings
↓
FAISS Vector Database
↓
User Question
↓
Question Embedding
↓
Semantic Retrieval
↓
Relevant Context
↓
FLAN-T5
↓
Generated Answer
↓
Source Attribution

## Features

* Multiple PDF document support
* PDF text extraction
* Text preprocessing
* Text chunking
* Semantic embeddings
* FAISS vector search
* Retrieval-Augmented Generation
* Question answering
* Source document and page identification
* Evaluation results
* Processed document chunks

## Technologies Used

* Python
* Google Colab
* PyMuPDF
* Sentence Transformers
* FAISS
* Hugging Face Transformers
* FLAN-T5
* NumPy
* Pandas
* Matplotlib

## Project Files

| File                                           | Description                                         |
| ---------------------------------------------- | --------------------------------------------------- |
| `RAG_Document_Question_Answering_System.ipynb` | Complete Google Colab implementation                |
| `rag_evaluation_results.csv`                   | Questions, generated answers, and retrieved sources |
| `document_chunks.csv`                          | Processed document chunks                           |
| `rag_faiss_index.faiss`                        | FAISS vector index                                  |

## How to Run

1. Open the `.ipynb` notebook in Google Colab.
2. Install the required libraries.
3. Upload PDF documents when prompted.
4. Run the notebook cells in order.
5. The system extracts and processes the documents.
6. The documents are converted into embeddings.
7. FAISS performs semantic retrieval.
8. FLAN-T5 generates an answer using the retrieved context.
9. The system displays the relevant source documents and pages.

## Important Note

The original PDF lecture materials used during development are not included in this repository. Users should provide documents that they are legally permitted to use and upload.

## Learning Outcomes

This project demonstrates practical use of:

* Natural Language Processing
* Semantic Search
* Vector Databases
* Information Retrieval
* Embeddings
* Generative AI
* Retrieval-Augmented Generation
* Document Question Answering

## Project Type

End-to-End AI / NLP / Generative AI Project
