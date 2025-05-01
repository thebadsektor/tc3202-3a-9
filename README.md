# VisageCheckAI – Facial Skin Disease Identifier

![Project Banner](https://via.placeholder.com/1200x400.png?text=VisageCheckAI)

## Table of Contents
- [Introduction](#introduction)
- [Project Overview](#project-overview)
- [Objectives](#objectives)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup and Installation](#setup-and-installation)
- [Usage Instructions](#usage-instructions)
- [Project Structure](#project-structure)
- [Contributors](#contributors)
- [Changelog](#changelog)
- [Acknowledgments](#acknowledgments)
- [License](#license)

---

## Introduction
**VisageCheckAI** is an AI-powered web application designed to help users identify facial skin diseases through natural language and image-based queries. It provides suggestions for remedies and recommends certified dermatologists in Laguna, Philippines.

---

## Project Overview
This project serves as a diagnostic support tool, offering users:
- Preliminary AI-based feedback on skin conditions based on facial image analysis or symptom input.
- Possible remedies and treatment plans.
- Links to local, verified dermatologists.

---

## Objectives
- Identify common facial skin conditions using AI.
- Provide user-friendly chat and image-based diagnosis.
- Recommend local dermatologists for further consultation.

---

## Features
- 🧠 AI chatbot for skin disease symptom discussion.
- 📸 Image upload to detect visible facial skin problems.
- 💊 Suggested treatments and home remedies.
- 👨‍⚕️ Recommended dermatologists in Laguna (with clickable profile links).

---

## Technologies Used
- **Frontend:** React.js, TailwindCSS
- **Backend:** Flask (Python)
- **Machine Learning:** PyTorch, Transformers, Mistral-7B API
- **Other Tools:** Git, GitHub, Git LFS (for model files)

---

## Setup and Installation

### Prerequisites:
- Node.js (LTS) – [Download](https://nodejs.org/)
- Python 3.8+ – [Download](https://www.python.org/)
- Git

---

### Installation Steps:

```bash
# 1. Clone the repository
git clone https://github.com/thebadsektor/tc3202-3a-9.git
cd tc3202-3a-9

# 2. Install React frontend dependencies
cd chat-app
npm install

# 3. Install Python backend dependencies
cd ../server-app
pip install -r requirements.txt
```

---

## Running the Application

```bash
# Terminal 1 – Start Flask backend
cd server-app
python app.py

# Terminal 2 – Start React frontend
cd chat-app
npm start
```

Then open [http://localhost:3000](http://localhost:3000)

---

## Usage Instructions

- Use the chatbot to ask about facial skin symptoms.
- Upload an image to analyze facial skin conditions.
- View treatment advice and doctor recommendations with working profile links.

![Chat UI](https://via.placeholder.com/1200x700.png?text=Chat+Demo)
![Image Upload UI](https://via.placeholder.com/1200x700.png?text=Image+Upload+Demo)

---

## Project Structure

```bash
.
├── chat-app/               # React frontend
│   ├── src/components/
│   └── package.json
├── server-app/             # Flask backend
│   ├── api/
│   ├── app.py
│   └── requirements.txt
├── README.md
```

---

## Contributors

- **Mishael Catignas** – 💻 Lead Developer / Full Stack & AI Integration  
- **Britney Capellan** – UI/UX & Research Support  
- **Howard Candidato** – Data Preparation & Documentation  
- **Rjay Dntcaree** – Testing & Deployment Coordinator  

---

## Changelog

### [v1.0.0] - 2025-05-01
- Added AI chatbot and image upload functionality
- Implemented facial skin disease detection and treatment suggestions
- Linked local dermatologist profiles via clickable URLs

---

## Acknowledgments

Special thanks to:
- [SkinDiseaseAI2](https://github.com/TheUnmeshRaj/SkinDiseaseAI2) – Original project inspiration.
- Mistral-7B via Lepton API – for lightweight open LLM integration.
- Philippine Dermatological Society – for doctor directory.

---

## License

This project is for academic demonstration purposes. Original templates and datasets used under fair educational use. No commercial intent.
