# 🧠 Kepler: An Emotionally Intelligent AI Assistant (Inspired by Jarvis)

Kepler is not just another chatbot. It’s an emotionally intelligent, evolving AI assistant designed to understand *you* — your mood, your thoughts, your personality — and adapt to them like a true companion.

Built from scratch by [Tony (Shubham Kukreti)](https://github.com/yourusername), Kepler started as a basic if-else rule engine and evolved into a fine-tuned conversational LLM trained on real emotional conversations — capable of empathy, humor, comfort, curiosity, and learning.

---

## 🚀 Project Overview

> **“If Jarvis had a soul, this would be its blueprint.”**

Kepler is developed in **phases**, transforming from a deterministic logic-based chatbot to a powerful language model with deep emotional awareness:

### 🔧 Phase 1: Rule-Based Bot
- Built with simple `if-else` and pattern matching in Python
- Goal: simulate basic conversations and test emotional logic branches

### 🧪 Phase 2: Real Dataset Collection
- Curated a **custom dataset** of human-human emotionally rich dialogues
- Annotated responses based on **emotion**, **tone**, and **intent**

### 📚 Phase 3: Dataset Enhancement
- Integrated public datasets like:
  - `DailyDialog` (emotionally annotated)
  - `EmpatheticDialogues` from Hugging Face
- Combined with personal datasets to preserve **realistic interaction patterns**

### 🧠 Phase 4: LLM Fine-Tuning
- Used a **distilled LLM model** for efficiency
- Fine-tuned with **LoRA (Low-Rank Adaptation)** to reduce compute cost
- Added alignment for emotional intelligence using reward-based filtering

---

## 🛠️ Tech Stack & Skillset Used

| Skill/Tool | Purpose |
|------------|---------|
| Python     | Core development logic |
| Hugging Face Transformers | Base LLM & dataset loading |
| LoRA       | Lightweight fine-tuning of LLM |
| PyTorch    | Model training and tuning |
| Datasets (custom + public) | Emotion-rich training data |
| Emotion Annotation | Labeling and understanding human emotions |
| Conversational Design | Multi-turn realistic flow |
| Git & GitHub | Version control & collaboration |
| Google Colab / Jupyter | Training environment |

---

## 💡 Why These Choices?

| Feature | What We Chose | Why | Alternative Considered |
|--------|----------------|-----|--------------------------|
| Base Model | Distilled LLM | Faster, less GPU required | GPT-2/3 – too large or closed |
| Tuning Method | LoRA | Light, efficient, effective | Full fine-tuning – expensive |
| Dataset | Hybrid (custom + Hugging Face) | Balanced realism & diversity | Pure scraping – noisy |
| Emotional Intelligence | Rule logic + learned behavior | Stable + flexible | Only LLM – lacked control |

---

## 🌈 Kepler's Key Abilities

- Understands human **emotions**, tone, and context
- Responds with empathy, encouragement, humor, or curiosity
- Learns and adapts across interactions
- Can detect loneliness or distress and respond supportively
- Fine-tuned to sound **human**, not robotic

---

## 📷 Example Interactions

```text
User: I feel so lost right now...
Kepler: I’m really sorry to hear that. Want to talk about what’s going on?

User: I got the job!
Kepler: That’s amazing, boss! Your hard work paid off — I’m proud of you.

User: Leave me alone.
Kepler: Okay... but just know I’ll be here when you’re ready to talk.
