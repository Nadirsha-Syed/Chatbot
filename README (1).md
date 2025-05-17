
# Basic Chatbot using NLTK with Fuzzy Matching

This is a simple text-based chatbot built using the Python NLTK library.  
It can carry out basic conversations using predefined patterns and includes fuzzy matching to handle typos and missing punctuation.

## Features

- Pattern-based responses using regex (with optional question marks).
- Fuzzy matching of user input with `difflib` for better understanding.
- Handles user input with or without punctuation.
- Simple, interactive command-line interface.
- Easily customizable conversation patterns.

## Requirements

- Python 3.x
- nltk library

## Installation

1. Clone or download this repository.
2. Install required Python packages:

```bash
pip install nltk
```

3. Download NLTK data files (done automatically by the script):

```python
import nltk
nltk.download('punkt')
nltk.download('stopwords')
```

## Usage

Run the chatbot script:

```bash
python chatbot.py
```

Type your messages to chat with the bot.  
Type `quit` to exit the conversation.

### Example conversation:

```
You: hi
Chatbot: Hello! How can I assist you today?

You: what is your name
Chatbot: I'm a chatbot created by Syed.

You: tell me a joke
Chatbot: Why don't skeletons fight each other? They don't have the guts!

You: quit
Chatbot: Goodbye! Take care!
```

## Customization

- Modify the `self.pairs` list in `BasicChatbot` class to add, remove, or change conversation patterns.
- Add more sophisticated NLP or external API integration as needed.


## Author
If you have any questions or feedback, feel free to reach out:
- Email: nadirshasyed835@gmail.com  
- GitHub: Nadirsha-Syed(https://github.com/Nadirsha-Syed)

