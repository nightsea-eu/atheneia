# Open Quantum Data Hub for Research & Teaching

**A commons-oriented platform for quantum datasets and educational reuse**  
This project provides an open-source data portal and interface to access, annotate, and reuse quantum computing datasets for research, reproducibility, and teaching purposes.

![Atheneia Logo](https://atheneia.eu/assets/logo-dark.svg)

---

## 🔍 About the Project

**Open Quantum Data Hub** is designed to foster openness and collaboration in quantum research by enabling:
- Dataset sharing and discovery
- Lightweight metadata curation
- Educational annotations and teaching-ready exports

It enables reproducibility, cross-institutional reuse, and a more accessible entry point for learners and educators.

---

## 🎯 Key Features

- Quantum dataset registry (public or user-added)  
- Tagging and annotation system for educational value  
- Export in teaching formats (CSV, JSON, QASM)  
- API access for reproducibility workflows  
- Search by topic, gate type, algorithm, or author

---

## 📦 Tech Stack

- **Frontend:** React, TypeScript, Vite  
- **Backend:** Python (FastAPI) + SQLite  
- **Storage:** Local-first + cloud-optional JSON/CSV  
- **Format support:** QASM, CSV, JSON, Markdown metadata

---

## 🚀 Getting Started

```bash
git clone https://github.com/nightsea-eu/atheneia/instruments/open-data-hub
cd open-data-hub

cd frontend
npm install
npm run dev
```

Backend setup info in `/docs/setup.md`

---

## 📚 Documentation

- `/docs/dataset-schema.md` – Supported data formats  
- `/docs/use-cases.md` – Example classroom + lab applications  
- `/docs/architecture.md` – Backend and frontend layout

---

## 🌐 License

Licensed under **Apache 2.0**

---

## 🤝 Maintainer

**Night Sea**  
https://nightsea.eu/research.html

---

## 🧭 Part of Atheneia

> Creating open platforms for research reproducibility, knowledge access, and responsible quantum infrastructure.
