# Initialize the project
uv init .
# Install the dependencies
uv add python-dotenv langgraph "langchain[anthropic]" ipykernel
# Run the chatbot
uv run main.py
