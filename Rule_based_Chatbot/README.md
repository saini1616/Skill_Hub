# Rule-Based Chatbot

## Overview
This project implements a rule-based chatbot capable of interacting with users by recognizing specific intents and responding with pre-defined answers. The chatbot demonstrates the use of pattern matching to simulate intelligent conversational behavior.

## Features
- **Negative Responses**: Detects phrases like "no" or "nah" to identify a refusal.
- **Exit Commands**: Recognizes commands like "quit", "pause", or "ok thanks" to end the conversation.
- **Random Questions**: Initiates a conversation by asking one of several predefined random questions.
- **Intent Matching**: Uses regular expressions to identify the following intents:
  - Describe the chatbot's "planet".
  - Explain the chatbot's purpose.
  - Discuss "Intellipaat" (as referenced in the bot's dataset).
  - Handle questions about disaster management.
- **Fallback Responses**: Provides generic responses when no specific intent is matched.

## Technologies Used
- **Programming Language**: Python
- **Libraries**: 
  - `re`: For regular expression-based intent matching.
  - `random`: To randomly select responses and questions.

## How It Works
1. The chatbot starts by greeting the user and asking for their name.
2. It initiates a conversation with a random question.
3. Based on the user's input:
   - It matches the input against predefined regular expressions to detect an intent.
   - If an intent is matched, it provides a relevant response.
   - If no intent is matched, it gives a fallback response.
4. The user can exit the conversation by typing an exit command.

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/rule-based-chatbot.git

