#  Rule-Based AI Chatbot

A foundational Rule-Based AI Chatbot developed in Python using deterministic control-flow logic and exact string matching techniques.

This project demonstrates the fundamentals of conversational AI before moving into advanced machine learning and neural network architectures.

---

#  Project Overview

Unlike modern generative AI systems powered by Large Language Models (LLMs), this chatbot operates entirely through predefined conversational rules.

The chatbot:
- Accepts user input
- Normalizes text into lowercase
- Matches inputs using conditional logic (`if-elif-else`)
- Returns predefined responses

The system is lightweight, beginner-friendly, and ideal for understanding the foundations of chatbot architecture.

---

#  Technologies Used

- Python 3
- Google Colab / Jupyter Notebook
- Conditional Logic
- String Matching
- Control Flow Programming

---

#  Features

✔ Greeting interactions  
✔ AI-related responses  
✔ Exit commands  
✔ Infinite conversation loop  
✔ Case-insensitive input handling  
✔ Beginner-friendly architecture  

---

#  System Architecture

The chatbot follows a deterministic architecture:

1. User enters text input
2. Input is normalized using `.lower()`
3. Conditional statements evaluate the input
4. Matching response is returned
5. Loop continues until exit command is detected

---

#  Project Structure

```bash
Rule_Based_AI_Chatbot.ipynb
README.md
```

---

#  How to Run

## Option 1: Google Colab
1. Upload the notebook to Google Colab
2. Run all cells
3. Start chatting with the bot

## Option 2: Jupyter Notebook
1. Open the notebook locally
2. Execute the notebook cells
3. Interact through terminal-style input prompts

---

#  Example Interaction

```text
You: hello
Bot: Hello! Nice to meet you.

You: what is ai
Bot: AI stands for Artificial Intelligence.

You: bye
Bot: Goodbye. Have a great day.
```

---

#  Advantages

- Predictable and safe responses
- Extremely lightweight
- No external dependencies
- Easy to understand and modify
- Excellent introduction to conversational AI

---

#  Limitations

- Cannot understand typos or synonyms
- No memory or contextual awareness
- Responses are fully hardcoded
- Limited scalability for large conversations

---

#  Future Improvements

Possible upgrades include:
- Natural Language Processing (NLP)
- Machine Learning integration
- Context-aware conversations
- Speech recognition
- GUI/Web deployment
- Deep Learning chatbot models


#  License

This project is open-source and available for educational purposes.
