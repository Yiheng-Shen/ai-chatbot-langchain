# ai-chatbot-langchain
This is a demo of an LLM-based chatbot using RAG within Databricks. This chatbot incorporates knowledge on menstrual cycle and mental health from relevant academic papers. Here’s a brief overview of the steps:  
1. Created a Unity Catalog Volume to store the PDFs;  
2. Extracted and chunked text into tables;  
3. Built a vector index using the DatabricksEmbedding model;  
4. Created a RAG pipeline using LangChain;  
5. Registered the model to Unity Catalog and deployed a serving endpoint;  
6. Set up a task to trigger ingestion and retraining when new PDFs are added.  

Please find the code in the zip folder for setting up the tables, handling incremental PDF ingestion, and deploying the RAG chatbot. 
  
A demo of interacting with the chatbot  
<img width="400" alt="WechatIMG8991" src="https://github.com/user-attachments/assets/e6edb26e-7567-435e-a006-e751c91238ce" />
