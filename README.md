# 🌊 Becoming Salmon: Composting Kinship - Immersive Eco-Interactive Web Experience

> An interactive web art project blending computer vision (MediaPipe), real-time WebGL shaders (Three.js), and post-human ecological speculation.

[![Status](https://img.shields.io/badge/Status-Completed%20%2F%20Ready%20for%20Submission-66C4BF?style=flat-square)](https://github.com/xy-art-web/salmon-kinship-interactive)
[![License](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)](LICENSE)

---

## 📌 1. Design Philosophy
*Becoming Salmon: Composting Kinship* is a digital art and interactive design project exploring post-human ecology, industrial salmon aquaculture, and ecological deconstruction. 
* By leveraging non-contact computer vision gesture recognition, the project breaks away from traditional one-way presentations, guiding viewers to transition from passive "spectators" to active "ecological explorers."
* It aims to provoke public reflection on symbiotic relationships and ecological ethics in the post-human era through immersive deep-sea lighting and tactile interaction.

---

## 🎯 2. Target Audience
* Digital media art enthusiasts and new media interaction designers.
* Ecological design researchers and individuals interested in post-humanist themes and sustainable futures.

---

## 🛠️ 3. Core Interactions & Mechanics
The project adopts a dual-layer viewport architecture driven by real-time shaders. Its core interactive features include:

| Module | Technology | User Action & Feedback |
| :--- | :--- | :--- |
| **🏠 Landing Page & Atmosphere** | HTML5 / Tailwind CSS / CSS3 Animations | Features a deep-sea particle background and breathing glowing effects upon load; clicking the **"Guide"** button triggers a smooth spring-bounce modal animation with precisely aligned borders. |
| **🖐️ Computer Vision Gesture Tracking** | MediaPipe Hands + Camera Utils | The bottom-right Picture-in-Picture (PIP) window displays a privacy-blurred camera feed overlaid with glowing neon-cyan hand tracking skeleton bones. |
| **🔍 Fishery Monitoring Cursor** | WebGL 2D/3D Shader Blending | When the user makes a **"fist"** gesture in front of the camera, the system dynamically drives and controls the fishery monitoring cursor to scan and reveal hidden ecological keywords (`OVERFISHING, MARINE DEBRIS`, `SALMON`, `AQUATIC KINSHIP`) across the dark deep-sea background, automatically triggering high-resolution data visualization cards with zoom-in capabilities. |
| **🌊 Immersive Environment & Reset** | JavaScript State Management | The top-left corner of the secondary exploration view features an **"Exit"** button paired with a background music (BGM) toggle, allowing users to smoothly return to the main login page at any time. |

---

## 📸 4. 界面截图与视觉展示 (Screenshots & Visual Showcase)

* **1. 主着陆页与氛围粒子 (Primary Landing Page)**：
  <img src="主界面.jpg" width="700" alt="Primary Landing Page">
  > *✨ 注释：页面加载时呈现深海粒子背景与呼吸微光效果。用户可点击 **“Get Started”** 进入探索，或点击 **“Guide”** 查看手势操作指南。*

* **2. 渔场显示器监控光标与手势识别触发 (Fishery Monitoring & Gesture Interaction)**：
  <img src="次要界面 - 交互前的深色背景.jpg" width="700" alt="Secondary Exploration View">
  > *✨ 注释：进入二级探索视口后，右下角展示实时手势追踪骨骼。用户通过“握拳”手势驱动聚光灯光标，在黑暗深海中主动扫描并发现隐藏的生态词汇。*

* **3. 悬浮数据可视化卡片与多维生态解构 (Floating Data Cards & Ecological Deconstruction)**：
  <img src="水生亲缘关系.png" width="700" alt="Data Visualization Cards">
  > *✨ 注释：当手势光标成功命中隐藏关键词（如 `OVERFISHING, MARINE DEBRIS`、`SALMON`、`AQUATIC KINSHIP`）时，系统会自动在屏幕关键坐标处弹出**悬浮数据可视化卡片**。卡片展示了多物种亲缘、工业化养殖解构与海洋生态数据，支持高清查看，完成了完整的互动闭环。*

---

## 🚀 5. Quick Start & Usage
This is a purely front-end-based browser project requiring no complex backend setup.

1. **Video Demo**: [📺 Watch the Full YouTube Demonstration Video](https://youtu.be/xU7JrCWnEGs)
2. **Clone the Repository**:
   ```bash
   git clone [https://github.com/xy-art-web/salmon-kinship-interactive.git](https://github.com/xy-art-web/salmon-kinship-interactive.git)
