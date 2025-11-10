# Rag_Pipeline

Objective - The main objective is to create a rag pipeline to which data is ingested in the form of PDFs, Txt and Html formats.

1. <b>Ingestion - Data preparation >> Encoding >> Stored in Vector DB. 
2. <b>Retreival - User_Query >> encoded rep of query >> Vector DB (similarity check) >> LLM
3. <b>Text Generation - Context from Vector DB + Prompt >> LLM >> LLM Generates responses.

