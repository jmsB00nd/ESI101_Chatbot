# ESI Student Assistant Chatbot

This project is a chatbot designed to assist new students at ESI by providing concise and factual responses to their queries. The chatbot uses advanced AI technologies, including LangChain, FAISS, and Cohere, to retrieve information and generate accurate responses based on a provided document.

## Features

- **Document Processing:** Loads and splits documents into manageable chunks for efficient search and retrieval.
- **Vector Search:** Utilizes FAISS for semantic similarity search to find relevant document chunks.
- **Language Model Integration:** Uses Cohere's API to generate natural language responses.
- **RESTful API:** Offers a `/chat` endpoint to interact with the chatbot.
- **Cross-Origin Resource Sharing (CORS):** Enabled to allow requests from different origins.

## Tech Stack

- **Python**: Core programming language.
- **LangChain**: For embedding generation and vector store integration.
- **FAISS**: For similarity-based vector search.
- **Cohere**: For natural language generation.
- **Flask**: Web framework for building the RESTful API.
- **dotenv**: For managing environment variables.
- **Google Docs**: Source of document data.
- **Flask-CORS**: To handle CORS policies.

## Prerequisites

- Python 3.8 or above
- A Cohere API key
- Required Python packages (see below)
- A publicly accessible Google Document containing the source content

## Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/esi-student-assistant.git
   cd esi-student-assistant
