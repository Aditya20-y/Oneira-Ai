# 🌌 Oneira: Dream Reflection & Emotional Insight App

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Author](https://img.shields.io/badge/Author-Aditya-purple.svg)](https://github.com/Aditya20-y)
[![Status](https://img.shields.io/badge/Status-Active-success.svg)]()

> An immersive, dual-layer NLP web application for dream journaling, automated symbol extraction, and emotional tone analysis. 

Oneira bridges the gap between sleep and waking reflection. By utilizing advanced NLP and a curated psychological framework, it provides deep contextual insights into your dream narratives without venturing into clinical diagnosis.

[**Explore the Live Demo**](#) ---

## ✨ Key Features

* **🧠 Dual-Layer Analysis Engine:** Connects to the Anthropic Claude API for sophisticated, context-aware dream analysis. Features a graceful failover to a robust, local keyword-scoring NLP engine if the API is unavailable.
* **🕸️ Symbolic Knowledge Graph:** Cross-references dream text against a framework of 20+ common dream symbols (e.g., flying, falling, water) drawn from empirical research and Jungian literature.
* **📊 Dynamic Emotion Metrics:** Evaluates and visualizes the emotional spectrum of the dream across 6 dimensions (*Anxiety, Wonder, Sadness, Conflict, Curiosity, and Joy*) using real-time animated charts.
* **🧘 Suggested Practices:** Tailors evidence-informed behavioral prompts (like Box Breathing, Morning Pages, or Narrative Reframing) based on the dominant emotion detected in the narrative.
* **💾 Session Persistence:** Saves user dream history locally via `localStorage`, featuring automated snippet generation and emotion badging.
* **✨ Immersive Aesthetic:** Designed with a "liminal void" color palette, an interactive starfield canvas animation background, and elegant typography to match the nighttime mood.

---

## 🛠️ Tech Stack & Architecture

* **Frontend:** Semantic HTML5, Modular CSS3 (Custom Variables, Flexbox, CSS Grid), Vanilla JavaScript (ES6+).
* **Animation Engine:** HTML5 Canvas Context (2D) for randomized, twinkling starry backdrops.
* **NLP / Logic:** Local keyword mapping and statistical scoring arrays integrated natively into a client-side execution loop.
* **API Integration:** Async/Await integration structured for Anthropic's Messages API (`claude-sonnet`).

---

## 🚀 Getting Started

Since Oneira is completely self-contained, getting it running locally takes less than a minute.

### Prerequisites
To unlock the primary AI layer, you will need an **Anthropic API Key**. *(Note: If omitted, the app will automatically run on its built-in local NLP fallback engine).*

### Installation
1. **Clone this repository:**
   ```bash
   git clone [https://github.com/Aditya20-y/Oneira-Ai.git](https://github.com/Aditya20-y/Oneira-Ai.git)
