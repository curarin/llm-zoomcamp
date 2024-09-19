# Learnngs from 'LLM Bootcamp' (by zoomcamp)
Documentation of my learnings from this course.

 - Goal: Put LLMs into production
 - Course Link: https://github.com/DataTalksClub/llm-zoomcamp

## Preperations

 - get .env file and put the following variables:
 ```
 OPENAI_API_KEY=<your_key>
 ```

## Week 1: 

 - **What are LLMs?**
Language Models predict the next token based on previous token. 
Large Language Models have billions of parameters and are trained on tons of data. 
It receives an input (usually called a prompt) and returns an output (a prediction).

 - **What are RAGs?**
RAG stands for Retrieval Augmented Generation. 
It is a type of LLM that uses external data sources to improve its performance.
Retrieval is search and generation is prediction for output.
We put data into a knowledge base / data base, the prompt is sent to the knowledge base, relevant documents are retrieved and sent to the LLM as context.

