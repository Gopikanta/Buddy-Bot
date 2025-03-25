# Buddy-Bot
# 🤖 BuddyBot – A Simple Rule-Based Chatbot  

Welcome to **BuddyBot**! This is a beginner-friendly **rule-based chatbot** built using **Python** and **NLTK**. It can process user inputs, understand basic questions, and reply with predefined responses.  

🚀 **BuddyBot is lightweight and does not require any APIs, making it easy to run on any system!**  

---

## 🌟 **Features**  
✅ Responds to basic user queries (greetings, farewells, small talk)  
✅ Uses **NLTK** for text processing and tokenization  
✅ Rule-based keyword matching for responses  
✅ Works **offline** without external APIs  
✅ Simple, interactive console-based chat  

---

## 🛠️ **Tech Stack**  
- **Language:** Python 🐍  
- **Libraries:** NLTK (Natural Language Toolkit)  
- **Platform:** Google Colab / Local Machine  

---

💬 How to Use BuddyBot
Run the chatbot script, and it will greet you.

Type your messages, and BuddyBot will respond based on pre-defined rules.

Type "bye" to exit the conversation.

📌 Example Chat Session

BuddyBot: Hello! Type 'bye' to exit.
You: Hi
BuddyBot: Hello! How can I assist you?
You: How are you?
BuddyBot: I'm a chatbot, but I'm doing great! How about you?
You: What can you do?
BuddyBot: I can chat with you! Ask me anything.
You: Bye
BuddyBot: Goodbye! Have a nice day!

🔍 How BuddyBot Works
BuddyBot uses a simple rule-based approach to understand and respond to user queries:

1️⃣ Preprocess user input (lowercasing, removing punctuation, tokenization) using NLTK

2️⃣ Match input words with predefined response patterns

3️⃣ Return a random response from the matching category

4️⃣ If no match is found, respond with a default message like "I don't understand. Can you rephrase?"

🚀 Future Improvements
💡 Some planned enhancements for BuddyBot:
✅ Better Text Matching: Use NLP techniques (TF-IDF, word embeddings)
✅ Synonym Recognition: Improve understanding with WordNet
✅ Learning Ability: Store previous chats and improve responses
✅ GUI/Web Interface: Convert it into a web app using Flask or Streamlit
