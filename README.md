# 🎓 Student Career Path Recommendation System

An AI-powered expert system that simulates a human career advisor to help school students discover their ideal career path based on personality, academic performance, interests, and goals.

---

## 📌 Project Overview

Choosing a future career can be overwhelming for students. This project provides a smart, rule-based decision system that asks targeted questions and delivers personalized recommendations such as Engineering, Medicine, Business, or Research.

---

## 🧠 System Features

- 🧩 **Expert System using Experta (Python)**
- ❓ **Interactive Question Flow** — 8 structured levels (personality, GPA, subjects, skills, motivation, etc.)
- 🔍 **Decision Logic** — Rule-based reasoning with forward chaining
- 🖥️ **Interactive GUI** — Built with ipywidgets on Google Colab for ease of use
---

## 🔄 Logic Flow

1. User answers a series of guided questions (GPA, interests, goals, etc.)
2. Each response is converted into structured facts.
3. The system applies rules using the **Experta** library.
4. A career recommendation is shown based on matched conditions.

---

## 📊 Question Levels

- ✅ Personality Type  
- ✅ Preferred Subjects  
- ✅ Academic Performance (GPA)  
- ✅ Interest (People vs. Tech)  
- ✅ Core Skills  
- ✅ Motivation  
- ✅ Future Goals  
- ✅ Work Environment Preference  

---

## 🧪 Tech Stack

- **Python**
- **Experta** (Expert system framework)
- **ipywidgets** (for interactive UI in Google Colab)
- **Google Colab**

---

## 🎯 Sample Output

> “Based on your responses, a career in **Engineering** aligns well with your skills, interests, and goals.”

---

## 🧩 Future Enhancements

- Add more career domains and subfields  
- Incorporate weighted scoring for nuanced recommendations  
- Export results to PDF or email  
- Add natural language input for more intuitive interactions
