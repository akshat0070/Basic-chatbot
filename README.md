🤖 Basic Rule-Based Chatbot

A simple rule-based chatbot built using Python. The chatbot takes input from the user and provides predefined responses based on specific messages.

This project is designed to practice fundamental Python concepts such as functions, loops, conditional statements, and user input/output.

🚀 Features

- 👋 Responds to greetings like "hello" and "hi"
- 😊 Responds to "how are you"
- 🤖 Can tell the user its name
- 💬 Explains what it can do
- 🙏 Responds to "thank you" and "thanks"
- 👋 Exits when the user types "bye"
- ⚠️ Handles unknown messages with a default response
- 🔄 Runs continuously until the user exits

🛠️ Technologies Used

- Python 3
- Functions
- "if-elif-else"
- "while" loop
- "input()" and "print()"
- String methods
- "break"

▶️ How to Run

1. Clone the repository

git clone https://github.com/akshat0070/basic-chatbot.git

2. Open the project folder

cd basic-chatbot

3. Run the program

python3 chatbot.py

On Windows, you can also use:

python chatbot.py

💻 Example

===== BASIC CHATBOT =====
Type 'bye' to exit the chatbot.

You: hello
Bot: Hi! 👋

You: how are you
Bot: I'm fine, thanks! 😊

You: what is your name
Bot: I'm a simple Python chatbot.

You: what can you do
Bot: I can respond to a few predefined messages.

You: thanks
Bot: You're welcome! 😊

You: bye
Bot: Goodbye! 👋

📁 Project Structure

basic-chatbot/
│
├── chatbot.py
└── README.md

🧠 How It Works

The chatbot continuously takes input from the user using "input()".

The input is converted to lowercase and checked using "if-elif-else" statements.

For example:

if user_input == "hello" or user_input == "hi":
    print("Bot: Hi! 👋")

If the user enters an unknown message, the chatbot provides a default response:

else:
    print("Bot: Sorry, I don't understand that.")

The chatbot uses "break" to stop the loop when the user types:

bye

🎯 Learning Goals

This project helps practice:

- Creating and calling functions
- Using "while" loops
- Using "if-elif-else"
- Taking user input
- Processing strings
- Using "break"
- Building a simple interactive Python program

🔮 Future Improvements

Possible improvements for future versions:

- Add more questions and responses
- Add time/date responses
- Add random responses
- Store conversations in a file
- Add a graphical user interface (GUI)
- Connect it to an AI API in a future version

👨‍💻 Author

Akshat Saini

BCA Student | Python Learner

---

⭐ If you found this project useful, consider giving the repository a star!
