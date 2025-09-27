# Collect Resources & Build Prototype (Unreal Engine – C++ & Blueprints)

## 📖 Project Overview
This project, developed as **Artifact 3**, is a prototype built in **Unreal Engine 5** that demonstrates a survival-style resource collection and building system.  
The main focus of the prototype is combining **C++ code** with **Blueprints** to create gameplay mechanics such as resource gathering, AI behavior, player stats, and UI systems.

For a full breakdown with screenshots, check the Behance showcase here:  
👉 [Behance Project Showcase](https://www.behance.net/gallery/235452097/Collect-Resources-Build-PrototypeUE-C-BP)  

You can also watch the gameplay demo video on Vimeo here:  
👉 [Vimeo Demo](https://vimeo.com/1122365856)

---

## 🎮 Features
- **Player Character (C++ & Blueprint):**  
  First-person setup with camera controls, basic movement, and stat management (health, hunger, stamina).  

- **Resource System:**  
  Collect resources (e.g., wood, stone, berries) with amounts tracked in C++.  
  Resources display their type and amount using world text.  

- **Crafting & Building:**  
  Use gathered resources to place simple building parts such as walls.  
  Code handles building meshes, pivot points, and placement logic.  

- **AI System (Blueprint):**  
  Basic wandering AI implemented with an **AI Controller** and NavMesh.  

- **UI System:**  
  HUD elements update player stats in real-time.  
  Win/Lose widget screens with retry/quit buttons.  

---

## 🛠 Tools Used
- Unreal Engine 5  
- C++  
- Blueprints  
- Visual Studio  

---

## 📂 Project Structure
- `PlayerChar` → Handles player movement, camera, and stats.  
- `Resources_M` → Defines resource types and amounts.  
- `BuildingPart` → Manages building meshes and placement logic.  
- `AI` & `AI_Controller` → Basic enemy/AI movement behavior.  
- `Widgets` → Player HUD, crafting menu, win/lose screen.  

---

## 🚀 How to Run
1. Clone the repository:  
   ```bash
   git clone https://github.com/Chiri0330/collectResourcesProjectUE_BP_and_Cplusplus.git
