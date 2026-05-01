# HW10 – Pinecone + Airflow Pipeline

This project implements an end-to-end data pipeline using Apache Airflow and Pinecone to perform semantic search on a Medium articles dataset. The pipeline downloads and preprocesses the data, generates sentence embeddings using a transformer model, creates a Pinecone index, ingests the embeddings, and executes similarity search queries. All steps are orchestrated as Airflow tasks and executed within a Docker-based environment.
