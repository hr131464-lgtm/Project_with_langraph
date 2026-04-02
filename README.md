# Graph Database Question Answering System

Graph-based Question Answering system using Neo4j, LangChain, and LLMs to convert natural language queries into Cypher queries.

## Project Overview
This project demonstrates how to build a Question Answering (QA) system using a graph database. The system allows users to ask natural language questions about movie data, which are automatically converted into Cypher queries and executed on a Neo4j graph database.

The project integrates LangChain and Large Language Models (LLMs) to generate Cypher queries from user questions and retrieve accurate answers from the graph database.

## Technologies Used
- Python
- Neo4j Graph Database
- LangChain
- Groq LLM
- Cypher Query Language
- Jupyter Notebook

## Key Features
- Connects to Neo4j graph database
- Converts natural language queries into Cypher queries
- Uses LangChain GraphCypherQAChain
- Retrieves answers directly from graph data
- Applies prompt engineering strategies for better query generation

## How It Works
1. Connect to the Neo4j graph database  
2. Load the movie dataset  
3. Retrieve the graph schema  
4. Use LangChain GraphCypherQAChain  
5. Convert natural language questions into Cypher queries  
6. Execute queries on the database  
7. Return answers to the user  

## Example Questions
- Who directed the movie Casino?
- Which actors worked in the movie Casino?
- How many artists are there in the dataset?
- How many movies has Tom Hanks acted in?

## Future Improvements
- Build a Streamlit web interface
- Integrate Graph + Vector RAG
- Improve prompt engineering
- Support larger knowledge graphs

## Author
Harsh Raj