This project involves downloading a news dataset from huggingface and processing the data. The data is then upserted to Pinecone. An advanced RAG workflow using LLM-based agents was then built. The final agent is a specially finetuned LLM using LoRA that rewrites text in the style and tone of President Trump.  

The data can be found here: https://huggingface.co/datasets/heegyu/news-category-dataset/tree/main 

Please download the data.json and ensure it is in the same folder you are working out of for the upserting.

To run this code: install the required packages using the "requirements.txt" file
To upsert the data into Pinecone run the DataCleaningAndUpserting.ipynb file.
To run the model with the CLI for testing please run AgenticWorkflowWithCLI.ipynb

For security purposes, the keys used have been deleted. You will need your own keys.