A Claude AI-powered conversational chatbot designed to search and retrieve academic research papers from arXiv. This interactive Jupyter notebook demonstrates tool use capabilities with Claude, allowing users to ask natural language questions about research papers.

What It Does:
Core Functionality:

Intelligent Paper Search - Ask the chatbot to find research papers on any topic. It uses the arXiv API to search for the most relevant papers and stores metadata (titles, authors, summaries, URLs, publication dates) in JSON format
Paper Information Retrieval - Query for details about previously searched papers across all topics using paper IDs
Interactive Chat Interface - Type natural language queries and the chatbot interprets them, deciding which tools to use automatically
Key Features:
Two Smart Tools:

search_papers: Searches arXiv for papers by topic, returns up to 5 results by default, and organizes results in a papers/ directory structure
extract_info: Retrieves detailed information about any paper that's been previously searched
Tool Use Implementation - Demonstrates Claude's tool use (function calling) capabilities where the AI model decides when and how to use available tools based on user queries

Persistent Paper Storage - Papers are saved as JSON files organized by topic, making them accessible for future queries within the same session

Robust Error Handling - Includes exception handling for file I/O and API errors
