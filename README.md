
# Chatbot Project

This project is a chatbot application built using LangChain and LangGraph. It supports maintaining conversational history and multi-language responses using the OpenAI API. The chatbot can switch between conversation threads, apply different templates, and manage conversation history efficiently.

## Features

- **Conversational Memory**: Maintains chat history and differentiates between user sessions.
- **Multi-Language Support**: The chatbot can respond in different languages based on user input.
- **Custom Templates**: Includes configurable templates for different chatbot personalities (e.g., pirate, assistant).
- **State Management**: Utilizes LangGraph's state and memory management for effective conversation handling.
- **Message Trimming**: Manages and trims conversation history to stay within token limits.
- **Streaming Mode**: Supports streaming responses for real-time interactions.

## Tech Stack

- **Programming Language**: Python
- **Frameworks/Libraries**:
  - [LangChain](https://www.langchain.com/)
  - [LangGraph](https://github.com/langchain-ai/langgraph)
- **API**: [OpenAI API](https://beta.openai.com/docs/)
- **Tools**: Google Colab, Jupyter Notebook

## Setup

1. **Clone the repository**:
   ```bash
   git clone <repository-url>
    cd chat-bot
   ```
   
2. Setup environemnt variables:
- Set `LANGCHAIN_TRACING_V2` to `"true"`.
- Set `LANGCHAIN_API_KEY` and `OPENAI_API_KEY` (use `getpass` to input these securely).

3. Run the Notebook:
- Open the notebook in Google Colab or Jupyter Notebook.
- Follow the cells to interact with the chatbot.
---
© [Areeb Niyas](https://github.com/areebniyas)