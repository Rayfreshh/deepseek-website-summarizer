# DeepSeek Website Summarizer

A Jupyter notebook that automatically summarizes website content using DeepSeek AI via Ollama.

## Features

- 🌐 Extract and clean website content
- 🤖 Generate AI-powered summaries using DeepSeek R1 model
- 📝 Display results in formatted markdown
- 🛡️ Handles various website structures with proper headers

## Quick Start

1. **Install Ollama and pull DeepSeek model:**
   ```bash
   # Install Ollama (visit https://ollama.com)
   ollama pull deepseek-r1:1.5b
   ```

2. **Install Python dependencies:**
   ```bash
   pip install requests beautifulsoup4 openai python-dotenv ipython
   ```

3. **Run the notebook:**
   - Open `DeepSeek_webaite_Summerizer.ipynb`
   - Execute all cells
   - Use `display_summary("your-url-here")` to summarize any website

## Example Usage

```python
# Summarize any website
display_summary("https://example.com")
```

## Requirements

- Python 3.7+
- Ollama running locally
- DeepSeek R1 model

Perfect for researchers, content creators, and anyone who needs quick website summaries!
