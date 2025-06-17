#  Mikasa v2.0 — Intelligence, Personalized

> “Designed not just to respond — but to *remember*, *evolve*, and *understand you.*”

## ✨ 1. Executive Summary

**Mikasa v2.0** is a breakthrough in locally-run conversational AI. Meticulously engineered for deep personalization, it goes beyond the conventional assistant. Mikasa doesn’t just chat — she **learns who you are**, remembers what matters, and evolves with your intentions.

Built on a seamless architecture of **cutting-edge LLMs**, **intuitive memory systems**, and **web intelligence**, Mikasa speaks with the clarity of now — and the memory of yesterday.

Every response is informed. Every interaction, personal. Every feature, intentional.

---

## 🌟 2. Core Features — Crafted for Meaning

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

### 🌐 Web Intelligence 

To overcome the limitations of static LLMs, Mikasa integrates a **web intelligence layer designed by Charan** — a dynamic solution for a dynamic world:

* Trigger real-time knowledge access with web search button, and Mikasa will:

  1. Perform a smart Google search based on your intent 🧭
  2. Scrape content from the top trusted sources 📄
  3. Feed that content to the LLM for contextual synthesis 🧠
  4. Deliver a distilled, useful summary + clickable source links 🔗

* With **contextual carryover**, Mikasa refines your next query using recent chat — giving you answers that are not only accurate, but *relevant*.

> This module ensures Mikasa always stays updated — even when models fall behind. ⚙️🌍

### 🎭 Customize Behavior, Instantly

* Shape Mikasa’s tone with `from now on...`

  * *Example: “from now on, use emojis” → Mikasa gets expressive 🥰*
* View settings with `show settings` 📋
* Remove quirks with `stop doing [behavior]` 🚫

---

## 🏗️ 3. Architecture — Elegant in Layers

### 🖥️ Interface (Frontend)

* Minimalist HTML page. One screen. One chat. Total focus.

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
| `search that ...`       | Live web answer                   | `search that iPhone 16 features` 📱      |
| `from now on ...`       | Modify personality/response style | `from now on, speak casually` 😎         |
| `show settings`         | Show behavior settings            |                                          |
| `stop doing [behavior]` | Undo a behavioral tweak           | `stop doing emoji_usage` 🙅‍♀️           |

---

## 🧡 Designed by Charan

Mikasa isn’t just a chatbot. She’s memory. She’s voice. She’s *presence.*

Every line of code. Every design choice. It’s all for one reason:

> **To make your AI finally feel like *yours*.**
