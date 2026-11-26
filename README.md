# 🧠 PlanWise — AI Assistant That Asks Before It Plans

> **PlanWise** is an NLP-powered planning assistant that understands a user's goal, identifies missing information, asks relevant questions, and then creates a personalized plan.

Most planning assistants immediately generate a plan from incomplete information. **PlanWise takes a different approach — it asks first, understands the user's requirements, and plans afterward.**

---

## ✨ Why PlanWise?

Suppose a user says:

> "I want to prepare for a software engineering interview."

A normal AI assistant might immediately generate a study plan.

PlanWise first asks:

- What is your current coding level?
- How many hours can you study each day?
- When is your interview?
- Which topics have you already completed?
- Which programming language do you prefer?

After collecting the important information, it generates a more useful and personalized plan.

---

## 🚀 Main Features

- 💬 Natural language conversation
- 🔎 Identifies missing information from user requests
- ❓ Generates relevant follow-up questions
- 🧠 Understands user goals and constraints
- 📋 Creates personalized plans
- 🔄 Allows users to modify their requirements
- 📊 Displays the final plan in an easy-to-read format

---

## 🏗️ How It Works

```text
User Goal
   ↓
NLP Processing
   ↓
Understand Intent
   ↓
Find Missing Information
   ↓
Ask Follow-up Questions
   ↓
Collect User Requirements
   ↓
Generate Personalized Plan
```

### Example

```text
User:
"I want to learn Python."

PlanWise:
"Sure! Before creating your plan, I need a few details."

Q1. What is your current Python level?
Q2. How much time can you study every day?
Q3. What is your goal — college, job, projects, or interview?

User:
"Beginner, 2 hours/day, placement preparation."

PlanWise:
"Here is your personalized Python learning plan..."
```

---

## 🛠️ Technology Stack

| Component | Technology |
|---|---|
| Programming Language | Python |
| NLP | NLTK / spaCy |
| ML | Scikit-learn |
| AI Model | LLM API |
| Backend | FastAPI / Flask |
| Frontend | Streamlit |
| Data | JSON / CSV |

---

## 🧩 NLP Pipeline

PlanWise uses a simple NLP pipeline:

### 1. Text Preprocessing
The user's message is cleaned and prepared for analysis.

### 2. Intent Detection
The system determines what the user wants to accomplish.

Examples:

```text
"Learn DSA"          → Learning
"Plan my trip"       → Travel
"Prepare for exam"   → Education
"Build a project"    → Project
```

### 3. Requirement Extraction

The system tries to identify useful information such as:

- Goal
- Time available
- Deadline
- Experience level
- Preferences
- Constraints

### 4. Missing Information Detection

If important information is unavailable, PlanWise asks the user for it.

### 5. Plan Generation

After collecting enough information, the system creates the final plan.

---

## 📁 Project Structure

```text
PlanWise/
│
├── data/
│   └── intents.json
│
├── models/
│   └── intent_model.pkl
│
├── src/
│   ├── preprocessing.py
│   ├── intent_detection.py
│   ├── question_generator.py
│   ├── requirement_extractor.py
│   └── planner.py
│
├── app.py
├── train.py
├── requirements.txt
└── README.md
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/PlanWise.git
```

Move into the project:

```bash
cd PlanWise
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## 🔑 API Configuration

If an external LLM API is used, create an environment variable for your API key.

```bash
OPENAI_API_KEY=your_api_key
```

Never upload API keys directly to GitHub.

---

## ▶️ Running the Project

Start the application:

```bash
streamlit run app.py
```

The application will open in your browser.

---

## 📌 Example Use Cases

### 🎓 Study Planning

```text
"I want to prepare for DSA in 2 months."
```

PlanWise asks about:

- Current DSA knowledge
- Daily study time
- Preferred language
- Target company/interview
- Completed topics

---

### 💼 Career Planning

```text
"I want to prepare for a software internship."
```

The system collects information about:

- Skills
- Experience
- Available time
- Target role
- Current preparation level

---

### ✈️ Trip Planning

```text
"I want to plan a trip to Jaipur."
```

It can ask:

- Number of days
- Budget
- Number of people
- Travel preferences
- Places of interest

---

## 🎯 Future Improvements

- Voice-based interaction
- Long-term user preferences
- Calendar integration
- Automatic task reminders
- Multi-language support
- Better intent classification
- Personalized recommendations
- Progress tracking

---

## 📚 Learning Outcomes

By building PlanWise, you can learn:

- NLP fundamentals
- Text preprocessing
- Intent classification
- Information extraction
- Conversational AI
- Prompt engineering
- API integration
- Basic recommendation systems
- Building an AI-powered web application

---

## 👨‍💻 Project Goal

The goal of PlanWise is simple:

> **Don't plan too early. Understand the user first.**

The project demonstrates how NLP and conversational AI can be used to turn incomplete user requests into structured, personalized plans.

---

## 📄 License

This project is created for educational and portfolio purposes.
