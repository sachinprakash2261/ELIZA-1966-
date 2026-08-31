# ELIZA — A Classic Rule-Based Chatbot

> A recreation of **ELIZA**, one of the earliest chatbots, originally created by Joseph Weizenbaum at MIT in the 1960s.

ELIZA is a simple **rule-based conversational program** that simulates a psychotherapist by recognizing patterns in a user's input and generating responses based on predefined rules.

This project recreates the core idea behind ELIZA to demonstrate how a chatbot can work **without machine learning, APIs, or modern AI models**.

---

## 🤖 How It Works

ELIZA does not actually understand what the user is saying.

Instead, it:

1. Takes the user's message as input.
2. Searches for specific **keywords and patterns**.
3. Applies predefined rules to the matching pattern.
4. Extracts relevant parts of the user's sentence.
5. Rearranges those parts into a response.
6. Returns the generated response to the user.

For example:

```text
You: I feel sad

ELIZA: Why do you feel sad?
```

Another example:

```text
You: My mother doesn't understand me

ELIZA: Tell me more about your family.
```

The interesting part is that the chatbot can appear conversational even though its responses are generated entirely through rules.

---

## ✨ Features

* 💬 Interactive chatbot conversation
* 🧠 Keyword-based response system
* 🔄 Pattern matching
* 📝 Predefined conversation rules
* 🔁 Pronoun transformation
* 🛡️ Fallback responses for unknown inputs
* 🚫 No external AI API required
* ⚡ Lightweight and fast
* 📚 Simple code structure for learning

---

## 🛠️ Technologies Used

* **Programming Language:** `YOUR_LANGUAGE`
* Pattern Matching
* String Processing
* Rule-Based Artificial Intelligence

> Replace `YOUR_LANGUAGE` with the language you used, such as Python, JavaScript, Java, etc.

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git
```

### 2. Navigate to the project

```bash
cd YOUR_REPOSITORY
```

### 3. Run the chatbot

```bash
YOUR_RUN_COMMAND
```

For example, if your project is written in Python:

```bash
python eliza.py
```

---

## 💻 Example Conversation

```text
====================================
          ELIZA CHATBOT
====================================

You: Hello

ELIZA: How do you do. Please tell me your problem.

You: I am feeling lonely.

ELIZA: Why do you feel lonely?

You: I don't have many friends.

ELIZA: Why don't you have many friends?

You: My family doesn't understand me.

ELIZA: Tell me more about your family.

You: quit

ELIZA: Goodbye. Have a nice day!
```

---

## 🧩 Project Structure

```text
ELIZA/
│
├── eliza.py              # Main chatbot program
├── README.md             # Project documentation
└── ...
```

> Update the structure above according to the actual files in your repository.

---

## 🧠 What I Learned

Building this project helped me understand the fundamentals of early conversational systems, including:

* How **pattern matching** can be used to process natural language.
* How keyword-based systems generate responses.
* How simple rules can create the appearance of conversation.
* How pronoun transformation works in conversational systems.
* The difference between **rule-based AI** and modern machine-learning-based chatbots.
* How early chatbots worked without neural networks or large language models.

---

## 🔍 ELIZA vs Modern AI

| ELIZA                       | Modern AI Chatbots                    |
| --------------------------- | ------------------------------------- |
| Rule-based                  | Machine-learning based                |
| Predefined responses        | Dynamically generated responses       |
| Keyword matching            | Neural language models                |
| No training data required   | Requires large-scale training         |
| Does not understand context | Can maintain contextual conversations |
| Lightweight                 | Computationally intensive             |
| No external API required    | Often uses large AI models            |

ELIZA demonstrates an important idea in AI: **a system can produce convincing conversational behavior without actually understanding language.**

---

## 📜 Historical Background

ELIZA was created by **Joseph Weizenbaum** at MIT in the 1960s. Its most famous script, **DOCTOR**, simulated a Rogerian psychotherapist by responding to users with questions and reflections.

Despite its simple rule-based design, some users believed that ELIZA genuinely understood them. This became an important early example in the history of human-computer interaction and artificial intelligence.

---

## 🎯 Purpose of This Project

This project was created as an educational implementation inspired by the original ELIZA concept.

The goal is to make the underlying chatbot logic easy to understand and demonstrate that sophisticated-looking conversations can sometimes be produced using surprisingly simple algorithms.

---

## ⚠️ Disclaimer

This project is **not a real therapist or mental-health service**.

ELIZA only generates responses according to predefined rules and does not understand emotions, thoughts, or personal circumstances.

---

## ⭐ Future Improvements

Possible improvements include:

* [ ] Add a graphical user interface
* [ ] Add more conversation patterns
* [ ] Improve keyword matching
* [ ] Add conversation history
* [ ] Add multiple chatbot personalities
* [ ] Add voice input/output
* [ ] Add a web-based interface
* [ ] Compare rule-based responses with modern LLM responses

---

## 👨‍💻 Author

**Sachin Prakash**

B.Tech Computer Science Engineering

---

## ⭐ Support

If you found this project interesting, consider giving the repository a ⭐ on GitHub.
