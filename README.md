# FAQ Chatbot CLI

This project is a simple command-line chatbot that answers frequently asked questions (FAQ) using semantic similarity with Sentence Transformers.

## Features

- Loads FAQ data from a text file
- Uses sentence embeddings to match user questions with FAQ
- Provides answers or a fallback message if no match is found

## Requirements

- Python 3.x
- [sentence-transformers](https://www.sbert.net/)
- torch

## How to Run

1. Install the required packages:
   ```
   pip install sentence-transformers torch
   ```

2. Run the notebook or script:
   - If using Jupyter Notebook, run all cells in `FAQChatbotCLI.ipynb`.
   - If using as a script, ensure `faq.txt` is present and run the Python code.

3. Interact with the chatbot in the terminal. Type your question or `exit` to quit.

## FAQ Data

The FAQ data is stored in `faq.txt` with the following format:
```
Q: Your question?
A: The answer.

Q: Another question?
A: Another answer.
```

## Example

```
You: What is AI?
Chatbot: AI stands for Artificial Intelligence.
```
