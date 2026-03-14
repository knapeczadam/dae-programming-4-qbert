# 🟠 Programming 4 – Q*bert  

Hey fellow DAE student, game dev enthusiast, or curious visitor 👋  
Welcome to my **Programming 4 – Q*bert** repository — the final project for [Programming 4](https://github.com/knapeczadam/programming-4).

---

## 🗄️ About this repository

This repo contains my **final project** for Programming 4, where I was randomly assigned **Q*bert** out of ten possible games.  
The main goal was to implement the **first three levels** with **pixel-perfect accuracy**, replicating enemy AI and behavior as closely as possible.  

> ⚠️ Note: this project applies patterns and concepts learned in Programming 4.  
> It’s a **snapshot of my learning journey**, not a polished commercial product.

---

## 🏗️ Engine: Minigin

The project is built on **[Minigin](https://github.com/avadae/minigin)**, a minimal SDL2 & glm setup created by **Alex Vanden Abeele**.  
Minigin is not a full game engine — it provides a small framework for 2D C++ games with:

- SDL2 setup for rendering/input  
- glm for vector and matrix math  
- Scaffolding to quickly start a project  

In this project, I extended Minigin to implement a **component-based GameObject system**, **event queue**, **dedicated audio thread**, and all other game patterns required for Q*bert.

---

## 🧩 Key Patterns and Concepts

- **Programming Patterns Implemented:** Singleton, Factory, Observer, Service Locator, Command, Pimpl  
- **Event system:** Queue-based event handling  
- **Object management:** Unity-inspired GameObject system with component-based architecture  
- **Audio:** Runs on a dedicated thread  
- **Execution order:** Unity-inspired essential functions  

---

## 🚀 Releases

This project contains **two release builds**, available in the [📦 Releases](../../releases) section:

- `programming_4-qbert-1.0.0-windows-x64.zip` → normal game build  
- `programming_4-qbert-debug-1.0.0-windows-x64.zip` → debug build with **999 lives** (effectively infinite) and **sprite/logical debug visualization**

---

## 🧠 Final Thoughts

This project demonstrates how **game programming patterns** improve code structure, memory access, and decoupling.  
It also showcases how best practices like **event-driven systems, threading, and modular architecture** can be applied in game development.  
If you’re exploring Programming 4 projects: **study, experiment, and enjoy a classic arcade revival** 🟠🕹️

---

### ⚖️ License
This repository is licensed under the **MIT License** — feel free to explore, learn, or fork for educational purposes.
