# Developing Artificial Intelligence Agents with ADK

This project demonstrates how to build a **personal AI assistant** using the **Google AI Agents Development Kit (ADK)**.  
The assistant is designed to answer user questions and can be extended with additional tools such as currency rate lookups and web search.

## Features
- Root agent powered by **Gemini-2.5-Flash**.
- Configured to answer user questions to the best of its knowledge.
- **Custom function integration**: Currency exchange rate lookup (`get_fx_rate`).
- **Built-in tool integration**: Google Search Tool (optional, subject to ADK’s single-tool limitation).
- Project synchronized with GitHub for version control and collaboration.

## Usage
1. Add your required API keys to the `.env` file.
2. Start the project with:
   ```bash
   uv run adk web
