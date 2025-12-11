AtliQ Tees: Talk to a Database (NL → SQL)

This project is an end-to-end Generative AI system built using Google PaLM and LangChain, designed to convert natural-language questions into SQL queries and execute them on a MySQL database for AtliQ Tees, a T-shirt store.


---

Features

Converts natural language queries into SQL

Executes SQL on MySQL database

Uses LangChain + Google PaLM

Streamlit UI for asking questions

Supports few-shot learning and embeddings



---

Tech Stack

Python

Google PaLM

LangChain

Streamlit

MySQL

ChromaDB

HuggingFace Embeddings



---

Installation

pip install -r requirements.txt

Add your API key in .env:

GOOGLE_API_KEY="your_api_key_here"

Set up the database:

Run database/db_creation_atliq_t_shirts.sql in MySQL Workbench


---

Usage

streamlit run main.py

Ask questions like:

“How many Adidas white T-shirts are in stock?”

“How much sales will we generate if all XS shirts sell after discount?”