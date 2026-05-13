# 🌲 VR Forest Environment — Unity + Meta Quest 3

A small immersive VR forest environment built in Unity
using the XR Interaction Toolkit and tested on Meta Quest 3.
Built as a personal learning project to explore VR development
and 3D environment design.
<!--
---

## 📸 Preview
[Insert screenshot or GIF of the environment here]

---
-->
## 🛠️ Built With
- Unity 6 LTS (URP — Universal Render Pipeline)
- XR Interaction Toolkit
- Meta Quest 3

---

## ✨ Features
- Immersive forest environment using Unity Terrain tools
- Atmospheric fog and depth haze
- XR player character with smooth locomotion
- Compatible with Meta Quest 3

---

## 🚀 How to Run
1. Clone this repository
   git clone https://github.com/NTarun-111/ForestVirtualEnvironment-VR-.git

2. Open in Unity 2022.3 LTS or later

3. Install required packages via Package Manager:
   - XR Interaction Toolkit (v3.2.1) https://docs.unity3d.com/2021.3/Documentation/Manual/com.unity.xr.interaction.toolkit.html
   - XR Plugin Management
   - OpenXR Plugin https://docs.unity3d.com/Packages/com.unity.xr.openxr@1.17/manual/index.html
   - Meta XR SDK https://developers.meta.com/horizon/downloads/package/meta-xr-sdk-all-in-one-upm/
   - Low Poly Environment Assets https://assetstore.unity.com/packages/3d/environments/low-poly-environment-nature-free-lowpoly-medieval-fantasy-series-187052?srsltid=AfmBOoo40FyS9nFaYfFdV01ikJ69IVW2D4Zf9uIN2SX7ZOxKo2H7jZYC

4. Set up Meta Quest Link on your PC:
   - Download and install Meta Quest Link app:
     https://www.meta.com/en-gb/help/quest/articles/headsets-and-accessories/oculus-rift-s/install-app-for-link/
   - Open Meta Quest Link app on PC
   - Put on your Quest 3
   - Accept the Link connection prompt in headset

5. Connect via Air Link (Wireless — Recommended):
   - Make sure your PC is connected to
     your router via LAN cable
   - Quest 3 and PC on same Wi-Fi network
     (5GHz band recommended)
   - On Quest 3 → Quick Settings
     → Meta Quest Link → Air Link
   - Select your PC from the list → Connect

6. Play in Unity:
   - Once Air Link is connected
   - Press Play in Unity Editor
   - Experience the VR environment directly through your Quest 3

---

## 📁 Project Structure
```
Assets/
│
├── 🖐️ Animated Hands/          → Hand models and animations
│       AnimateHandOnInput.cs   → Script that animates hands
│       InputSystem_Actions     → Input action mappings for
│       .inputactions             controllers and hand tracking
│
├── 🌲 Polytope Studio/         → Third-party forest asset pack
│                                 (trees, bushes, nature props)
│
├── 🎮 Samples/                 → XR Interaction Toolkit
│                                 sample scenes and prefabs
│
├── 🗺️ Scenes/                  → Main VR scene files
│       New Terrain.asset       → Forest terrain data
│
├── ⚙️ Settings/                → URP renderer and
│                                 graphics pipeline settings
│
├── 🚀 StarterAssets/           → Unity starter character
│                                 and controller assets
│
├── 📖 TutorialInfo/            → XR Toolkit tutorial
│                                 references and info
│
├── 🥽 XR/                      → XR plugin settings and
│                                 OpenXR configuration
│
└── 🎛️ XRI/                     → XR Interaction presets
                                  (locomotion, ray interactor,
                                   teleportation settings)
```
---

## 📋 Requirements
- Unity 2022.3 LTS or newer
- Meta Quest 3 (or other OpenXR compatible headset)

---

## 🧠 What I Learned
- Setting up a VR project in Unity with URP
- Using XR Interaction Toolkit for player locomotion
- Unity Terrain tool for environment design
- Building and deploying to Meta Quest 3

---

## 📌 Status
🟡 In Progress — actively adding more environments and interactions

---

## 📄 License
MIT License — feel free to use or learn from this project

---

## 🙋 Author
Tarun Nixon

LinkedIn: https://www.linkedin.com/in/n-tarun09/

GitHub: https://github.com/NTarun-111
