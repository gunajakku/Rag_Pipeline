# Rag_Pipeline

Objective - The main objective is to create a rag pipeline to which data is ingested in the form of PDFs, Txt and Html formats.

<b>Ingestion<\b> - Data preparation >> Encoding >> Stored in Vector DB. 
<b>Retreival<\b> - User_Query >> encoded rep of query >> Vector DB (similarity check) >> LLM
<b>Text Generation<\b> - Context from Vector DB + Prompt >> LLM >> LLM Generates responses.

