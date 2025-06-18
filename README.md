# 🕹️ Temple Run Controlled with Hand Gestures

Play Temple Run using only your hand gestures — no keyboard or mouse needed!  
This project uses **Computer Vision** to detect hand gestures in real-time and map them to game actions, creating a fun and touchless gaming experience.

---

## ✨ Features

- 🎮 Control Temple Run with **hand gestures**
- ✋ **Open Palm** → Jump (`Up Arrow`)
- ✊ **Fist** → Slide (`Down Arrow`)
- 📷 Uses **webcam** for live hand tracking
- ⚡ Real-time detection with **MediaPipe** and **OpenCV**
- 🧪 Ideal for learning about gesture recognition and automation

---

## 🛠️ Tech Stack

| Technology    | Purpose                          |
|---------------|-----------------------------------|
| Python        | Core programming language         |
| MediaPipe     | Hand gesture detection            |
| OpenCV        | Webcam access and image handling  |
| PyAutoGUI     | Simulate keyboard actions         |

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/Alamin0x01/HandPowerGame.git
cd HandPowerGame
```
### 2. Install Dependencies

```bash
pip install opencv-python mediapipe pyautogui
```

### 3. Run the Script

```bash
python Main.py
```

✅ Make sure:

* Your webcam is connected
* Temple Run is open and focused

---

## 📌 How It Works

1. **Webcam** captures your hand.
2. **MediaPipe** identifies key hand landmarks.
3. The program detects if your hand is open or closed (fist).
4. Based on the gesture:

   * Sends `Up Arrow` to jump (open palm)
   * Sends `Down Arrow` to slide (fist)

---

## 📷 Demo

> *[Demo Video Link](https://www.linkedin.com/posts/mdalaminali_computervision-mediapipe-opencv-activity-7341082171060719618-e72M?utm_source=social_share_send&utm_medium=member_desktop_web&rcm=ACoAAC3TqDUBblFzFomfotvqMHeVzdp4Viz4QEo)*
---

## 📁 Project Structure

```
📦temple-run-gesture-control
 ┣ 📜main.py
 ┣ 📜README.md
 ┗ 📜requirements.txt (optional)
```

---

## 🤝 Contributing

Pull requests are welcome!
If you have new ideas or want to expand this with more gestures, feel free to fork and contribute.

---

## 📄 License

This project is licensed under the **MIT License**.

---

## 🔗 Connect with Me


🌐 LinkedIn: [https://linkedin.com/in/mdalaminali](https://linkedin.com/in/mdalaminali)

---

```
