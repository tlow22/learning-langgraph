# learning-langgraph

A repo of `marimo` notebooks for learning `LangGraph`.

## Quick Setup

1. **Install Python 3.12+**  
   Download: https://www.python.org/downloads/

2. **Install uv**  
   ```bash
   curl -LsSf https://astral.sh/uv/install.sh | sh
   ```

3. **Install dependencies**  
   ```bash
   uv sync
   ```

4. **Set up environment variables** (if needed)  
   ```bash
   cp .env.example .env
   # Edit .env to add your API keys and secrets
   ```

5. **Start marimo**  
   ```bash
   uv run marimo edit tutorials/<notebook>.py
   ```

You're ready to explore the LangGraph tutorials!



