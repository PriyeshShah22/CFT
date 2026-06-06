# 🌍 Carbon Footprint Tracker

A desktop application built using **Java Swing** that helps users track, analyze, and reduce their carbon footprint based on daily activities such as transportation, energy usage, and dietary choices.

---

## 🚀 Features

* **✅ User-Friendly Interface** – Simple, interactive GUI built with Java Swing.
* **✅ Activity Logging** – Log daily habits like travel distance, electricity use, and food consumption.
* **✅ Carbon Calculation Engine** – Estimates total $\text{CO}_2$ emissions based on standardized emission factors.
* **✅ Visualization** – Displays results via progress bars or charts for better understanding.
* **✅ History Tracking** – Keeps records of previous days to monitor your footprint over time.
* **✅ Tips for Sustainability** – Suggests tailored ways to reduce your environmental impact.

---

## 🧠 How It Works

```text
[Input Activities] ──> [Emission Calculation] ──> [Visualization & Feedback]
  User logs daily        Backend estimates CO₂       App displays total footprint 
  habits & usage         using emission factors      & provides reduction tips

```

1. **Input Activities:** Users fill out forms tracking daily energy usage, transportation modes, and diet habits.
2. **Emission Calculation:** The backend logic aggregates total $\text{CO}_2$ equivalents based on user inputs using predefined conversion algorithms.
3. **Visualization & Feedback:** The app dynamically displays your emission metrics alongside actionable advice to reduce your daily footprint.

---

## 📊 App Screenshots

To show the interface and backend logic clearly, I have organized the screenshots below.

### System Dashboard (Key Views)

| Main Login & Tracker | Comparison Charts |
| :--- | :--- |
| <p align="center"><img src="https://github.com/user-attachments/assets/0399d53d-0b57-445a-b963-b7f1ab6d7724" width="100%" alt="Main Login Screen"/></p> | <p align="center"><img src="https://github.com/user-attachments/assets/194b6382-57a8-4c14-a79f-4b92f23814ad" width="100%" alt="Charts and Analysis View"/></p> |

---

### Backend Database Logs

We use MySQL (managed by XAMPP/phpMyAdmin) to store persistent historical data.

<p align="center">
  <img src="https://github.com/user-attachments/assets/7f4a628e-8c66-4e58-8410-b30e4c4a0092" width="70%" alt="Database View showing phpMyAdmin logs"/>
</p>
---

## ⚙️ Tech Stack

| Component | Technology |
| --- | --- |
| **Language** | Java |
| **GUI Framework** | Swing |
| **Data Storage** | MySQL (Managed via XAMPP & phpMyAdmin) |
| **IDE Used** | IntelliJ IDEA / Eclipse / NetBeans |

---

## 🧮 Example Calculation

The engine calculates metrics mathematically based on active variables:

* **Driving a petrol car:**

$$10\text{ km} \approx 2.4\text{ kg of CO}_2$$


* **Dietary Footprint:**

$$\text{Vegetarian Meal} \approx 0.5\text{ kg CO}_2 \quad \text{vs.} \quad \text{Non-Vegetarian Meal} \approx 1.7\text{ kg CO}_2$$



The app aggregates these baseline formulas across all logged sectors to display your final net daily footprint.

---

## 👨‍💻 Contributors

| Name | Role |
| --- | --- |
| **Priyesh Shah** | Developer, GUI, Database |
| **Yash Shinde** | Database and Coding |
| **Harshal Vaghela** | Main GUI, Report |

---

## 🪴 Motivation

> “You can’t manage what you don’t measure.”

This project aims to make environmental awareness actionable — helping individuals explicitly measure their daily carbon output so they can make informed, positive lifestyle choices.

