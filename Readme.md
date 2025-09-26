# 🧠 Chat with Einstein

**Chat with Einstein** is an interactive AI-powered chatbot where you can have fun, thought-provoking conversations with **Albert Einstein** himself.
The bot is designed to respond in Einstein’s voice, combining **reasoning, humor, and personal anecdotes** from his life, while also answering your questions about science, philosophy, and beyond.

## 🎯 Project Overview

This project creates a **persona-driven chatbot** using:

* **LangChain** for message management and prompting
* **Google Generative AI (Gemini)** as the LLM engine
* **Gradio** for a user-friendly interface
* **dotenv** for secure environment variable handling

The goal is to make conversations more engaging by embedding **Einstein’s personality** into responses. 
Instead of just answering directly, the AI includes reflections, stories, and jokes—making it feel like you're really talking to Einstein.

## ✨ Key Features

* **👨‍🔬 Einstein Persona**
  * Answers are styled with Einstein’s perspective, mixing curiosity, humor, and anecdotes.
  * Example: Instead of simply explaining relativity, Einstein might recall his famous tram thought experiment.

* **💬 Conversational Memory**
  * Maintains chat history so Einstein can respond contextually during the session.

* **🎨 Custom Interface**
  * Simple and elegant Gradio interface.
  * Einstein’s avatar (einstein.png) displayed for assistant responses.

* **⚙️ Configurable Prompt**
  * System prompt defines Einstein’s personality traits (reasoning, humor, life stories).
  * Can be tweaked to create other personas (e.g., Newton, Tesla, Shakespeare).

* **🌐 Shareable Web App**
  * Gradio generates a local and public share link for easy access.

## 🛠️ Tech Stack

* **Python** – Core language
* **LangChain** – Prompt handling & conversation history
* **Google Generative AI (Gemini)** – Large language model for responses
* **Gradio** – Web-based chatbot UI
* **dotenv** – Secure API key management

## 📂 Project Structure

│── **main.py**              # Main application file (Einstein chatbot)

│── **einstein.png**        # Avatar for Einstein in the chat UI

│── **.env**                # API key stored here (not for version control)

│── **README.md**           # Project documentation

## 💡 Example Conversation

**User:** Explain relativity in simple terms.
**Einstein:** "Ah, relativity! Imagine you sit with a pretty girl for an hour—it feels like a minute. Sit on a hot stove for a minute—it feels like an hour. That’s relativity for you! Though, of course, my equations are a bit less romantic."

**User:** Did people believe you at first?
**Einstein:** "Not quite! Many thought I was just a wild-haired dreamer. But when Eddington’s 1919 solar eclipse experiment proved me right, I suddenly became rather fashionable in the newspapers!"

## 🎨 UI Preview

* Chatbot built using **Gradio’s Chatbot** component.
* Messages appear with user and Einstein roles.
* Einstein’s avatar (einstein.png) gives a personal touch.

## 📌 Future Improvements

* 🖼 Add more persona modes (e.g., switch between Einstein, Newton, or Tesla).
* 🎙 Integrate text-to-speech for Einstein’s voice.
* 📖 Add session saving (download chat history).
* 📱 Optimize design for mobile devices.
* 🔐 Include authentication for private deployments.

## 📜 License

This project is licensed under the MIT License. Feel free to fork, modify, and create your own persona-based chatbots!