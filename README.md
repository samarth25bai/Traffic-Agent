# Traffic-Agent
# 🚦 Adaptive Traffic Signal Control System using Learning Agent

## 📌 Overview

This project simulates an intelligent traffic signal system that dynamically adjusts green signal timing based on traffic density. It uses a simple learning agent approach with a reward mechanism to improve decision-making over time.

---

## 🎯 Problem Statement

Traffic congestion is a major issue in urban areas. Fixed-time traffic signals are inefficient because they do not adapt to changing traffic conditions. This project aims to design a system that adjusts signal timing based on real-time traffic levels.

---

## 💡 Solution

The system monitors the number of vehicles and classifies traffic as:

* High Traffic
* Medium Traffic
* Low Traffic

Based on this, it dynamically increases or decreases signal timing. A reward-based mechanism evaluates whether the decision was effective, allowing the system to behave like a learning agent.

---

## ⚙️ Features

* 🚗 Traffic density detection
* ⏱️ Dynamic signal timing adjustment
* 🧠 Reward-based learning system
* 📊 Traffic pattern analysis (peak & low hours)
* 📈 Visualization of signal behavior

---

## 🛠️ Technologies Used

* Python
* Pandas
* Matplotlib

---

## ▶️ How to Run

1. Install dependencies:

```
pip install -r requirements.txt
```

2. Run the project:

```
python main.py
```

---

## 📊 Output

* Console-based traffic simulation
* Identification of peak and low traffic times
* Graph showing adaptive signal timing

---

## 📁 Project Structure

```
Traffic-Agent/
│── main.py
│── model.py
│── analysis.py
│── README.md
│── report.txt
│── requirements.txt
│── screenshots/
```

---

## 🚀 Future Improvements

* Integration with real-time traffic data
* Advanced AI using Reinforcement Learning
* GUI-based traffic simulation
* Multi-signal traffic management system

---

## 🧠 Learning Outcome

This project demonstrates how a simple learning agent can adapt to environmental conditions using feedback (reward system) and improve decision-making in real-world scenarios.

---

## 👨‍💻 Author

Your Name
