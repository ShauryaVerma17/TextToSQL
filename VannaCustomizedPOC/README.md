## Contents of this POC

This POC contains multiple notebooks each trying to use one different aspect than what the usual defaults are for Vanna, the other aspects will still remain as the default values given below. 

The defaults for all values are : 
  1. LLM : GPT 3.5 (Provided by vanna)
  2. VectorDB : pgvector (Provided by vanna)
  3. SQL DB : SQLite3 (Easiest one to use also the one used in the Initial POC for it's simplicity)

## What's different for each notebook? 

### VannaCustomDB 

Will try to use the 2 following databases instead of SQLite3 : 
  1. Oracle's SQL Developer
  2. Microsoft SQL Server

### VannaCustomLLM

Instead of GPT-3.5 which is provided we will use : 
  1. Ollama (Model is too quantized to give proper queries)
  2. Krutrim API (Cannot make calls form this server issue in vanna - so doesn't work)

### VannaCustomVectorDB

Will try to use ChromaDB - If we use a different vector db we cannot use the default LLM and the custom LLMs are not working for me :/
