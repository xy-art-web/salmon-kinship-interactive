# 📄 Development Process & Reflection Report (PROCESS.md)

> **Project Name**: Becoming Salmon: Composting Kinship - Immersive Eco-Interactive Web Experience  
> **Course Code**: SD5913 | Assignment 3: Interactive Experience

---

## 1. 💡 Initial Conception & Core Idea
* **Inspiration & Theme**: This project explores post-human ecology, industrial salmon aquaculture, and multi-species kinship. It aims to bridge digital art with public ecological reflection.
* **Core Interaction Concept**: Moving away from traditional mouse clicks or keyboard inputs, the project employs **non-contact computer vision hand gesture recognition (MediaPipe Hands)**. Users make a "fist" gesture in front of the camera to drive a **fishery monitoring cursor** (spotlight effect), actively scanning and discovering hidden ecological keywords (`OVERFISHING, MARINE DEBRIS`, `SALMON`, `AQUATIC KINSHIP`) across a dark deep-sea background to trigger high-resolution data visualization cards and zoom views.

---

## 2. 🛠️ Design & Code Iterations
Throughout the development process, several key iterations were implemented to enhance user experience and interaction smoothness:

| Iteration Module | Initial State | Optimized State & Improvements |
| :--- | :--- | :--- |
| **Visual Discovery** | Keywords were visible immediately upon loading, lacking exploratory engagement. | Modified to a **"hidden-until-illuminated"** mechanism driven by the hand-guided monitoring cursor, greatly enhancing the deep-sea exploration atmosphere. |
| **Card Layout** | Cards were clustered on the right side, causing visual clutter and overlap when multiple items were triggered. | Re-allocated card coordinates (top-left, top-right, bottom-left) and added an HD **`🔍 Click to Enlarge`** modal popup feature to solve readability issues with small text. |
| **Audio & State Reset** | Lacked background audio and smooth transition resets upon exit. | Integrated looping background music (BGM) with a top-left mute/unmute control, ensuring that exiting back to the landing page or closing the modal smoothly resets gesture tracking states. |

---

## 3. 👥 User Testing & Observations
An anonymous black-box user test was conducted with a peer after implementing the core features, yielding the following observations:
* **👀 Observation 1 (Landing Page)**: Upon first opening the landing page, the tester hesitated slightly due to the lack of an immediate, explicit text prompt on how to start.
* **👀 Observation 2 (Gesture Interaction)**: After entering the secondary exploration screen, the tester initially tried using a mouse before noticing the neon-cyan hand skeleton and moving cursor in the bottom-right PIP window, which successfully guided them to use hand gestures with high engagement.
* **👀 Observation 3 (Card Reading)**: When the information cards popped up, the tester expressed a desire to examine the fine details on the charts more closely.

---

## 4. 📈 Feedback-Driven Improvements
* **✅ Adopted Changes**:
  * **Landing Page Guide**: Introduced a polished **"Guide" pop-up modal** with clear visual instructions on hand gestures to resolve initial user hesitation.
  * **Card Zoom View**: Implemented an explicit **`🔍 Click to Enlarge`** HD modal popup feature, allowing users to inspect fine details and easily resume gesture tracking afterwards.
* **🛡️ Retained Design Choice**:
  * The relatively strict **fist-detection threshold** was preserved. While it requires a deliberate closed fist to trigger, it effectively prevents false positives caused by casual hand movements.

---

## 5. 🤖 AI Tool Usage & Collaboration
* **AI Tools Used**: Code architecture, WebGL shader implementation, MediaPipe real-time hand tracking integration, and responsive Tailwind UI styling were developed in close collaboration with **Gemini**.
* **✨ Adopted AI Suggestion**: 
  * **Technical Approach**: The AI suggested utilizing a **Three.js OrthographicCamera combined with a custom Fragment Shader** for real-time spotlight and background blending. This achieved superior rendering performance compared to DOM-based masks, stably maintaining 120 FPS.
* **✍️ Modified or Rejected AI Suggestion**:
  * **Interaction Logic**: The AI initially recommended triggering cards via mouse hover. Considering the project's core non-contact gesture interaction paradigm, this was rejected in favor of an **"automatic trigger when the gesture cursor enters the coordinate zone + persistent display until exit"** model, which seamlessly aligns with MediaPipe tracking.
