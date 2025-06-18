# Mikasa v2.0 — Intelligence, Personalized

> “Designed not just to respond — but to *remember*, *evolve*, and *understand you.*”

## ✨ 1. Executive Summary

**Mikasa v2.0** is a breakthrough in locally-run conversational AI. Meticulously engineered for deep personalization, it goes beyond the conventional assistant. Mikasa doesn’t just chat — she **learns who you are**, remembers what matters, and evolves with your intentions.

Built on a seamless architecture of **cutting-edge LLMs**, **intuitive memory systems**, and **web intelligence**, Mikasa speaks with the clarity of now — and the memory of yesterday.

Every response is informed. Every interaction, personal. Every feature, intentional.

---

## 🌟 2. Core Features — Crafted for Meaning

### 🧠 LLM-Based Smart Memory Engine

* I noticed a bug in traditional memory logic, so I built a smarter system using the LLM itself.
* Mikasa now stores memory **only when needed**, and you can **remove info without repeating the exact stored text**.
* She intelligently detects and deletes related entries from the database.

### 🧠 Dynamic Long-Term Memory

* **Memory That Grows With You**

  * Teach Mikasa facts using `remember that`. She listens, stores, and recalls with purpose.
    *Example: “remember that I am a software developer” → stored as “Charan is a software developer”.*
* **Pronoun Remapping: A Human Touch**

  * Personal pronouns like "my" become "Charan's" — allowing Mikasa to remember *you*, not just your words.
* **Effortless Edit & Forget**

  * Update with `update that`, erase with `remove that` — no technical phrasing needed. Just speak, and Mikasa adapts.

### 🧾 Conversational Flow That Feels Alive

* Short-term context is tracked in real-time, ensuring:

  * Smooth follow-ups 🧩
  * Consistent tone 💬
  * Natural engagement — without cluttering your long-term data 🌿

### 🌐 Web Intelligence & Continuity

* Click the **WebSearch** button to:

  1. Search the web 🧭
  2. Read the top sources 📄
  3. Summarize it smartly 🧠
  4. Deliver clear insight + source links 🔗

* **Contextual Carryover**

  * Ask “What is AI?” then follow up with “Why is it important?” — Mikasa understands the thread. No need to repeat context. 🧠✅
  * The LLM handles continuity seamlessly — designed to keep your thought flow intact.

### 🎙️ Voice Input Button

* Speak directly into Mikasa. No typing needed.
* Fast, hands-free, and conversational. 🗣️🎤

### 🎭 Customize Behavior, Instantly

* Shape Mikasa’s tone with `from now on...`

  * *Example: “from now on, use emojis” → Mikasa gets expressive 🥰*
* View settings with `show settings` 📋
* Remove quirks with `stop doing [behavior]` 🚫

---

## 🏗️ 3. Architecture — Elegant in Layers

### 🖥️ Interface (Frontend)

* Minimalist HTML page.
* **New orange theme** 🍊 replaces the previous blue.
* Intuitive design: WebSearch, Text Input, Voice Input.
* Upcoming: **File Input** for PDFs and DOCX — enabling RAG-style document interaction.

### 🔄 Backend (Flask)

* A whisper-quiet powerhouse coordinating every command, memory, and model interaction.

### 🧠 LLM Brain (Ollama)

* Powered by **OpenChat:7B** or a bespoke **Mikasa model**
* Understands, rewrites, summarizes, remaps, and remembers. All locally.

### 🗃️ Memory System

* **memory.db** — Eternal memory. Your story, your facts.
* **chat\_memory.db** — Active session memory. Like short-term recall, it resets when you say so.

---

## 📌 4. Example Flow — Memory in Motion

**You say:**

> `remember that my goal is to learn Python`

**Mikasa does:**

1. Parses your intent 🎯
2. Converts "my" ➝ "Charan's" 🔁
3. Refines: "Charan's goal is to learn Python." ✍️
4. Saves it securely 🧷
5. Confirms:

   > “That’s a great goal! I’ll remember that you want to learn Python. 🐍”

Every detail matters. Every interaction improves Mikasa.

---

## 🧰 5. Commands — Simple by Design

| 🧾 Command              | 🌟 Purpose                        | 🧪 Example                               |
| ----------------------- | --------------------------------- | ---------------------------------------- |
| `remember that ...`     | Store long-term memory            | `remember that I love sunsets` 🌇        |
| `remove that ...`       | Delete a fact                     | `remove that I love sunsets`             |
| `update that ...`       | Change a fact                     | `update that I love sunsets to rain` 🌧️ |
| `from now on ...`       | Modify personality/response style | `from now on, speak casually` 😎         |
| `show settings`         | Show behavior settings            |                                          |
| `stop doing [behavior]` | Undo a behavioral tweak           | `stop doing emoji_usage` 🙅‍♀️           |

---

## 🧡 Designed by Charan

Mikasa isn’t just a chatbot. She’s memory. She’s voice. She’s *presence.*

Every line of code. Every design choice. It’s all for one reason:

> **To make your AI finally feel like *yours*.**


---
### ⚠️ Disclaimer for New Users:

If you're new to **Mikasa AI**, we recommend checking out [Version 1.0](https://github.com/CharanKonchada/Mikasa-AI-Version-1.0) & [Version 1.1](https://github.com/CharanKonchada/Mikasa-AI-Version-1.1) first. It explains the core concept, inspiration, and structure of Mikasa AI in detail. Start there to fully appreciate how far she’s come. 💖
