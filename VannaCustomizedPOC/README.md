## Contents of this POC

This POC contains multiple notebooks each trying to use one different aspect than what the usual defaults are for Vanna, the other aspects will still remain as the default values given below. 

The defaults for all values are : 
  1. LLM : GPT 3.5 (Provided by vanna)
  2. VectorDB : pgvector (Provided by vanna)
  3. SQL DB : SQLite3 (Easiest one to use also the one used in the Initial POC for it's simplicity)

## What's different for each notebook? 

### VannaCustomDB 

Will try to use the 2 following databases instead of SQLite3 : 
  1. Oracle's SQL Developer : https://colab.research.google.com/github/vanna-ai/notebooks/blob/main/oracle-openai-vanna-vannadb.ipynb
  2. Microsoft SQL Server : https://colab.research.google.com/github/vanna-ai/notebooks/blob/main/mssql-openai-vanna-vannadb.ipynb

### VannaCustomLLM

Instead of GPT-3.5 which is provided we will use : 
  1. Ollama (Model is too quantized to give proper queries)
  2. Krutrim API (Cannot make calls form this server issue in vanna - so doesn't work)

There are built in options for using openAI as well as Azure OpenAI 
  1. Open AI : https://colab.research.google.com/github/vanna-ai/notebooks/blob/main/sqlite-openai-standard-vannadb.ipynb
  2. Azure OpenAI : https://colab.research.google.com/github/vanna-ai/notebooks/blob/main/sqlite-openai-azure-vannadb.ipynb

### VannaCustomVectorDB

Will try to use ChromaDB - If we use a different vector db we cannot use the default LLM and the custom LLMs are not working for me :/
