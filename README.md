Dependencies:
These are must have installs : langchain, langgraph, langchain-openai, langchain-tavily, python-dotenv
Optional: black, isort
Linux command using UV: 
uv add langchain langgraph langchain-openai langchain-tavily python-dotenv black isort

Installing dependencies:
uv : 
1. curl -LsSf https://astral.sh/uv/install.sh | sh
2. Restart teminal and try uv --version
3. uv sync #This will sync the pyproject.toml file to the project. Recommendation is to use venv for installations