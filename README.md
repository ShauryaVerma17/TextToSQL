## TextToSQL

This repo contains projects which enable natural language conversations with databases by harnessing the power of LLMs and RAG (Retrieval Augmented Generation). This will be done using pre-built libraries such as Vanna.ai as well as by implementing it from scratch.

## Pre-requisites 

To run this repo using VS code you will need to first run a few commands. Here are the steps :

1. Once you've cloned the repository open up VSCode and open the project folder.
2. Start the terminal and run the following commands :
   #### 1. Creating a virtual environment
       python -m venv .venv
   #### 2. Running the virtual environment
       .venv\scripts\activate
   #### 3. Installing all the required libraries into the virtual environment (Make sure virtual environment is enabled and you are in the main parent folder of the project)
       pip install -r requirements.txt
3. You will also have to create a .env file containing any required api-keys
