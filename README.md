# ai-chatbot-langchain
This is a demo of an LLM-based chatbot using RAG within Databricks. This chatbot incorporates knowledge on menstrual cycle and mental health from relevant academic papers. Here’s a brief overview of the steps:  
1. Created a Unity Catalog Volume to store the PDFs;  
2. Extracted and chunked text into tables;  
3. Built a vector index using the DatabricksEmbedding model;  
4. Created a RAG pipeline using LangChain;  
5. Registered the model to Unity Catalog and deployed a serving endpoint;  
6. Set up a task to trigger ingestion and retraining when new PDFs are added.  

Please find the code in the html files for setting up the tables, handling incremental PDF ingestion, and deploying the RAG chatbot, in case you're interested in taking a look.
