# ChatBot-CLI
A Chatbot CLI wrapper for ollama. 

---
## Description
I use this app so much, it easily allows me to modify system prompts and experiment with different models. It also saves context if explicitly told to.

## Installation
1) Git Clone
```bash
git clone https://github.com/FINN-2005/ChatBot-CLI.git
```
2) Install Ollama and it's models (the code uses [Gemma3:4b](https://ollama.com/library/gemma3:4b))
```bash
ollama pull gemma3:4b
```

## Usage
Start the app by ```python CLI.py``` and start Chatting.

### Commands:
1) ```/help``` – Show all available commands
2) ```/clear``` – Clear the chat history (memory)
3) ```/save``` – Save the current context to model_context.txt
4) ```/load``` – Load the context from model_context.txt
5) ```/cls``` – Clear the screen
6) ```/mood``` – Change the AI’s behavior/personality (Assistant, Friendly, Humorous, Human, Prompter)
7) ```/change``` – Switch to another available Ollama model
8) ```/bye``` – Exit the chatbot

Or just type your message normally to chat with the AI.

## Features  
- Multiple personalities (assistant, friendly, humorous, human, prompter)  
- Save & load conversation context  
- Switch models dynamically  
- Clear chat history or the terminal easily  
- Simple CLI interface  
