# whether-quadratic-model-
# Weather Modeling Using a Quadratic Model

This repository implements a simple weather prediction system using a **quadratic mathematical model**.  
It includes project documentation for **Waterfall**, **Iterative**, and **Agile** development modes suitable for a 5-person team.

---

## 📘 Project Overview

Weather variables such as temperature, humidity, or pressure are modeled by a quadratic equation:

T(t+1) = aT(t)^2 + bT(t) + c

The system reads weather data, fits coefficients (a, b, c), and generates predictions.

---

## 📁 Repository Structure

- **docs/** — Planning documents for Waterfall, Iterative, and Agile   
- **src/** — Source code (models, data preprocessing, visualization)  
- **tests/** — Unit tests  
- **requirements.txt** — Python dependencies  

---

## 👥 Team Structure (Teams of 5)

1. Project Manager  
2. System Architect  
3. Data Scientist  
4. Developer  
5. Tester / QA Engineer  

---

## 🛠 Development Modes

### 🔵 1. Waterfall
Document: `docs/waterfall.md`

Phases:
- Requirements → Design → Implementation → Testing → Deployment

### 🟣 2. Iterative
Document: `docs/iterative.md`

Each cycle delivers:
- Prototype v1 → v2 → v3 → Final Model

### 🟢 3. Agile (Scrum)
Document: `docs/agile.md`

Includes:
- Sprint backlogs  
- User stories  
- Incremental development  

---

## ▶️ Running the Project

**1. Install dependencies**
```bash
pip install -r requirements.txt
