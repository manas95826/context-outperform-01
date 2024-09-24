# AgentWrite LangGraph

AgentWrite LangGraph is a rewrite and extension of AgentWrite using LangGraph, designed to create an advanced writing assistant powered by language models and graph-based workflows.

## Description

This project leverages LangGraph to orchestrate a series of language model interactions, creating a powerful tool for automated content generation. It breaks down complex writing tasks into manageable steps, including planning, writing, and refining content.

## Features

- Automated content planning
- Paragraph-by-paragraph content generation
- Integration with multiple language models (OpenAI, GROQ, OLLaMA)
- Flexible workflow management using LangGraph
- Markdown output for generated content


## Usage

1. Set up your environment variables in a `.env` file:
   ```
   GROQ_API_KEY=your_groq_api_key
   ```

2. Install requirements
   ```
   pip install -m requirements.txt
   ```

3. Run the main script:
   ```
   streamlit run streamlit-chat.py
   ```

## For claude:

1. Replace api_key with claude api key from LLMs.claude-llm.py
2. Run claude script:
   ```
   streamlit run claude-app.py
   ```





