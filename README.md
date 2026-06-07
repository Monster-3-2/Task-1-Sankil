# Task-1-Sankil

```
## Decodelabs.py

A simple rule-based chatbot assistant that responds to predefined conversational prompts.

### Features
- **Interactive chat interface**: Run the script to start a conversation
- **Pre-trained responses**: Built-in knowledge base with common greetings and questions
- **Easy to use**: Just type your message and press Enter; type "exit" to quit

### How to Use
1. Run the script:
   ```bash
   python decodelabs.py
   ```
2. Type your message and press Enter to get a response
3. Type `exit` to quit the chatbot

### Example Conversation
```
hello
Hi there! Welcome!
what is your name
I'm DecoBot, your rule-based AI assistant!
thanks
You're welcome! Happy to help.
exit
```

### Supported Queries
- `hello` - Greet the bot
- `bye` - Say goodbye
- `how are you` - Ask about the bot's status
- `what is your name` - Ask the bot's name
- `what can you do` - Learn the bot's capabilities
- `thanks` / `thank you` - Express gratitude
- `help` - Get usage tips
- `who made you` - Learn about the creator
- Any other input will receive a default response

### Notes
- Input is case-insensitive and trimmed of whitespace
- Queries are matched exactly; phrases must match key strings in the responses dictionary
- Built by an AI intern at DecodeLabs
```


