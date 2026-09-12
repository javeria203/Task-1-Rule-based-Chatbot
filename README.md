# Rule-Based Chatbot

## Project Description

This project is a simple rule-based chatbot developed in Python. 
The chatbot responds to user messages by matching the user's input 
with predefined rules and responses.

## Features

- Responds to common greetings such as "hello", "hi", and "hey"
- Answers simple questions about AI
- Responds to questions about the chatbot
- Handles "thanks"
- Supports exit commands such as "bye", "exit", and "quit"
- Provides a default response when it does not understand the input

## Technologies Used

- Python
- Google Colab / Jupyter Notebook

## How It Works

The chatbot uses a predefined dictionary containing user inputs 
and corresponding responses. The user's input is converted to 
lowercase and matched with the available rules.

If a matching rule is found, the chatbot provides the corresponding 
response. Otherwise, it displays a default message.

## How to Run

1. Open `Rule_based_chatbot.ipynb` in Google Colab or Jupyter Notebook.
2. Run the code cells.
3. Enter a message when prompted with `You:`.
4. Type `bye`, `exit`, or `quit` to end the conversation.

The Python version can also be run using:

```bash
python rule_based_chatbot.py