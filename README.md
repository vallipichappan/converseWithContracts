# Converse with your Contracts (OpenAI's GPT + Neo4j + Langchain)

This repository explores the integration of OpenAI's GPT, Neo4j, and Langchain to facilitate communication with contracts through knowledge graphs. The project investigates the potential of utilizing knowledge graphs to address complex inquiries within contract documents.

## Overview
This project aims to leverage knowledge graphs to enable advanced querying and analysis of contract documents. By combining the capabilities of OpenAI's GPT for natural language understanding, Neo4j for graph database management, and Langchain for document transformations, the goal is to extract valuable insights from unstructured text and structured data within contracts.

### Theory
For a deeper understanding of the theoretical background behind using knowledge graphs for contract analysis, refer to this [Medium article](https://medium.com/@valli99/why-could-should-you-use-knowledge-graphs-to-talk-with-your-contracts-835b04ba7f73). In summary, knowledge graphs offer a transformative approach to interact with contract documents, unlocking new insights through contextual understanding and multi-hop reasoning.

## Data
A sample contract PDF obtained online serves as the dataset for this project.

### Complicated Questions
The project addresses various complex questions, including:
- Cost-Benefit Analysis
- Timeframe and Scheduling
- Resource Allocation

## Work Done
The project workflow involves several key steps:

1. **Setup**: Import necessary libraries and tools including OpenAI, Langchain, and Neo4j.
2. **Data Preparation**: Load, tokenize, and split the contract text using appropriate tools.
3. **Graph Construction**: Utilize Neo4j to construct a knowledge graph representing the contract's entities and relationships.
4. **Querying and Analysis**: Employ different methods for querying the knowledge graph and retrieving relevant information, including vector search and Cypher queries.
5. **Agent Development**: Develop an intelligent agent capable of interacting with multiple tools to answer complex questions.

### Final Agent with Tools that Interact
The final agent incorporates tools for structured and unstructured information retrieval, as well as document transformation for long context reordering.

## Usage
The repository provides a notebook detailing the project's implementation, including code snippets and responses to various questions posed to the contract document. Users are encouraged to experiment with their own contract data and explore different types of inquiries.

## Additional Content
The project offers avenues for further exploration, including:
- Performance Metrics
- Risk Assessment
- Quality Standards
- Compliance and Legal Obligations
- Collaboration and Communication
- Technology and Tools
- Change Management

Feel free to reach out for questions or discussions!

---

**Reference**: [Constructing Knowledge Graphs from Text using OpenAI Functions](https://bratanic-tomaz.medium.com/constructing-knowledge-graphs-from-text-using-openai-functions-096a6d010c17)
