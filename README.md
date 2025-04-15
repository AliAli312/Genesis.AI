# Genesis.AI

**Genesis.AI** is an experimental AI-powered educational and reasoning assistant designed to go beyond casual conversation. It can understand scientific topics, generate insights, express contextual opinions, and eventually, **create and solve its own problems**. This project aims to build a human-like artificial intelligence with memory, emotional awareness, flexible communication, and deep reasoning capabilities.

---

## Key Features

- **Topic Understanding**: Extracts and understands keywords and concepts from any topic using advanced NLP.
- **Multi-source Knowledge**: Uses Wikipedia, spaCy, and large-scale AI models like Transformers to gather and analyze knowledge.
- **Contextual Reasoning**: Offers meaningful facts, opinions, or interpretations based on logical reasoning.
- **Emotion-Aware Replies**: Responds to user tone (e.g., sad, happy, curious) with emotionally intelligent behavior.
- **Human-Like Chatting**: Interacts flexibly in conversation with random greetings and non-repetitive responses.
- **Beautiful GUI**: A clean, smooth graphical interface designed for comfort and interaction.

---

## Vision

> **“To build an AI system that grows with the user, learns independently, and creates value by thinking, understanding, and innovating like a human being.”**

Genesis.AI is not just a chatbot—it is the first step toward a system that **thinks, explores, and invents**.

---

## Installation

### Requirements

- Python 3.10+
- `transformers`
- `torch`
- `spacy`
- `wikipedia`
- `tkinter`
- `textblob` *(for emotional tone analysis)*

### Setup

```bash
pip install transformers torch spacy wikipedia textblob
python -m textblob.download_corpora
python -m spacy download en_core_web_sm
