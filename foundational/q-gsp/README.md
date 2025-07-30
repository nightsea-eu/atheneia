# Quantum Gate Sequence Predictor (Q-GSP)

**AI-aided quantum reasoning tool for learners and researchers**  
An open-source interface for building, predicting, and understanding quantum circuit logic — with real-time guidance and explainability.


---

## 🔍 About the Project

**Quantum Gate Sequence Predictor (Q-GSP)** is part of the **Atheneia** platform's foundational suite of quantum learning tools. It helps users construct valid quantum circuits by offering:

- Predictive suggestions for the next logical gate
- Explanatory overlays for reasoning and learning
- Modular architecture designed for educational and research use

This project aims to lower the barrier to quantum programming by combining visual interactivity with explainable AI.

---

## 🎯 Key Features

- **Context-aware gate predictions**
- **Interactive circuit builder** (drag-and-drop)
- **Explainable AI logic modules**
- **Export to QASM-lite or JSON**
- **Embeddable components for reuse**

All features are designed for local/offline use with no vendor lock-in.

---

## 🧪 Initial Functional Prototype

This repository currently hosts the first modular release, which includes:

- Basic UI for 1–3 qubit circuits
- Rule-based prediction engine
- Reasoning overlay with educational feedback
- JSON export format
- React-based component design (Vite + Storybook)

---

## 📦 Tech Stack

- **Frontend:** React, TypeScript, Vite, Storybook  
- **Backend:** Python (FastAPI)  
- **Prediction Logic:** Rule-based (LLM optional module planned)  
- **Data Format:** QASM-lite + JSON

---

## 🚀 Getting Started

To run locally:

```bash
# Clone the repo
git clone https://github.com/nightsea-eu/atheneia/foundational/g-gsp
cd g-gsp

# Install frontend
cd frontend
npm install
npm run dev

# Install backend
cd ../backend
pip install -r requirements.txt
uvicorn main:app --reload
```

More setup instructions available in `/docs/setup.md`.

---

## 📚 Documentation

- **Architecture** → `/docs/architecture.md`  
- **Design Decisions** → `/docs/design-notes.md`  
- **Learning Path Integration** → `/docs/learning-flow.md`

We welcome educational reuse and remixing. Contributions are open.

---

## 🌐 License

Licensed under **Apache 2.0**.  
All code and models are open, local-first, and privacy-preserving.

---

## 🤝 Maintainer

**Night Sea (NIGHT SEA EURL)**  
[https://nightsea.eu](https://nightsea.eu/research.html)  
Paris, France — SIREN 987 943 107

---

## 🧭 Part of the Atheneia Platform

Q-GSP is a foundational project of **Atheneia**, an open research initiative building modular tools at the intersection of:

> 🧠 Cognition — 🧮 Quantum Computing — 🤖 AI — 🌍 Sustainability



---
