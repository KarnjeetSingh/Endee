# Endee
# AI Financial Research Assistant using Endee Vector Database

## Project Overview
This project demonstrates a simple Retrieval Augmented Generation (RAG) pipeline for financial document search.

## Problem Statement
Financial information is scattered across multiple sources. Investors need a faster way to retrieve relevant insights.

## Solution
This system converts financial documents into vector embeddings and retrieves relevant information using similarity search.

## System Architecture
User Query → Embedding Model → Vector Search → Relevant Document → Response

## Tech Stack
Python
Sentence Transformers
Streamlit
Vector Search

## Setup

Install dependencies

pip install -r requirements.txt

Run ingestion

python backend/ingest.py

Run application

streamlit run frontend/app.py
