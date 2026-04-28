# 🚦 Real-Time Traffic Signal Optimization System

## 📌 Overview
A Java-based OOP project that simulates a smart traffic signal management system using real-time traffic density analysis. The system dynamically adjusts signal timings based on vehicle count and prioritizes emergency vehicles to reduce congestion.

---

## 🎯 Features
- Real-time traffic simulation
- Density-Priority Optimization Algorithm
- Emergency vehicle prioritization
- Dynamic green signal timing
- GUI dashboard using Java Swing
- Modular OOP architecture
- Random traffic generation
- Rush hour simulation support

---

## 🧠 OOP Concepts Used
- Encapsulation
- Inheritance
- Polymorphism
- Abstraction

---

## 📂 Project Structure
src/
├── model/
│   ├── Road.java
│   ├── Vehicle.java
│   └── TrafficSignal.java
│
├── controller/
│   ├── TrafficController.java
│   └── SmartTrafficController.java
│
├── service/
│   └── OptimizationService.java
│
├── simulation/
│   └── TrafficSimulator.java
│
├── ui/
│   └── TrafficDashboard.java
│
└── main/
    └── Main.java

---

## ⚙️ Simulation Engine
Custom-built Java discrete-time stochastic simulation engine using `TrafficSimulator`.

---

## 🚨 Optimization Algorithm
Density-Priority Optimization:
- Higher vehicle density = Higher signal priority
- Emergency vehicles override density priority

---

## 🖥️ Technologies Used
- Java
- Java Swing
- OOP
- Multithreading
- VS Code

---

## ▶️ How to Run
### Windows:
```bash
build_and_run.bat
