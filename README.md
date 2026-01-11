# AI Celeb Info

A simple project to fetch and display information about celebrities using Google Gemini LLM via LangChain. The notebook guides you through building a multi-step chain to get:
- General info about a celebrity
- Their date of birth
- Major world events around their birth date

## Tech Stack

- **Python** (Jupyter Notebook)
- **LangChain** (prompt templates, chains, memory)
- **Google Gemini API** (via `langchain_google_genai`)
- **Streamlit** (optional, for web app interface)

## How It Works

1. **Import Libraries**: Uses LangChain, Google Gemini, and memory buffers.
2. **Set API Key**: Requires a Google Gemini API key.
3. **Prompt Templates**: Defines prompts for info, date of birth, and world events.
4. **Chains**: Each step is a chain; all are combined in a `SequentialChain`.
5. **User Input**: Enter a celebrity's name to get info.
6. **Output**: Prints the info, date of birth, and major events.

## Setup

1. Clone this repo or copy the notebook.
2. Install dependencies:
   ```bash
   pip install langchain langchain-google-genai
   ```
3. Get a Google Gemini API key and set it in the notebook.
4. Run the notebook and follow the prompts.

## Example Usage

```
Enter the name of a celebrity: Taylor Swift

🎤 Celebrity Information:
[Info about Taylor Swift]

🎂 Date of Birth:
[Date]

🌍 Major Events Around That Time:
[List of events]
```

## Notes
- Streamlit code is commented; you can adapt this for a web app.
- The project is for educational/demo purposes.

## License
MIT License
