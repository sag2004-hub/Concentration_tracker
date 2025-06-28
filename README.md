# 🧠 Concentration Tracker

A real-time concentration tracking system using webcam input and facial analysis powered by **MediaPipe**, **OpenCV**, and **Python**. This tool detects eye blinks, gaze direction, and head orientation to compute and visualize a user's focus level.

---

## 🎯 Features

- 👁️ Blink detection using Eye Aspect Ratio (EAR)
- 🎯 Gaze direction estimation (using iris position)
- 🤳 Head pose alignment detection
- 📊 Real-time concentration score with color-coded bar
- ⚠️ Distraction alert counter
- 🖥️ FPS display and visual feedback for user state (Active/Distracted)

---

## 🚀 How It Works

The app uses:
- **MediaPipe Face Mesh** to detect facial landmarks (e.g., eyes, nose)
- **Custom scoring algorithm** to assess:
  - Eye blink frequency (low EAR)
  - Iris position (gaze direction)
  - Nose position (head orientation)
- A concentration score is computed from these cues and visualized in real time.

---

## 🛠️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/sag2004-hub/Concentration_tracker.git
cd Concentration_tracker
