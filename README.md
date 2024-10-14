# COMP5241 LLM Streamlit App

## How to Use

This application allows you to generate funny responses to your questions using a language model.

### Steps to Use the App

1. **Input Your Question**: Open the app and type your question into the text input box.
2. **Submit Your Question**: Click the "Submit" button to send your question to the language model.
3. **View the Response**: The app will display a humorous response with emojis.

### Example

1. **Input**: "Why did the chicken cross the road?"
2. **Output**: "To get to the other side! 🐔😂"

### Preparation

The dependencies are listed in the `requirements.txt` file.

Install the dependencies using:

```bash
pip install -r requirements.txt
```

### Running the App

To run the app, use the following command:

```bash
streamlit run app2.py
```

### API Key Setup

Make sure you manually create a `credentials` file with the necessary API key as described in `llm.py`. The file should be in the following format:

```
[OPENROUTER]
OPENROUTER_API_KEY = "[your OPENROUTER API key]"
```

You can create the API key via [OpenRouter API Key Settings](https://openrouter.ai/settings/keys).
