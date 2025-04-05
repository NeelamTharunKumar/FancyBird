# 🐦 Flappy Bird - Hand Controlled (Python + MediaPipe + Pygame)

A fun and interactive version of the classic Flappy Bird game that you can control with your hand gestures!  
Built using **Python**, **MediaPipe**, and **Pygame**, this project uses your webcam to detect hand movements and flap the bird.

---

## 🎮 How It Works

- Raise your hand to make the bird flap.
- Lower your hand or keep it steady to let the bird fall.
- Try to navigate through the pipes without crashing!

---

## 🛠️ Technologies Used

- Python 3
- [MediaPipe](https://google.github.io/mediapipe/)
- Pygame
- OpenCV

---

## 📦 Installation

### 1. Clone the repository
```bash
git clone https://github.com/NeelamTharunKumar/FlappyBird.git
cd FlappyBird
```

### 2. Create a virtual environment (optional but recommended)
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install dependencies

If `requirements.txt` is available:
```bash
pip install -r requirements.txt
```

If not, install manually:
```bash
pip install pygame opencv-python mediapipe
```

---

## 🚀 Running the Game

```bash
python flappybird_hand_control.py
```

Make sure your webcam is connected and accessible.

---

## 🧠 How Hand Detection Works

- Uses **MediaPipe Hands** to track your hand landmarks in real-time.
- Based on the vertical position of your hand:
  - Raise your hand → bird flaps up
  - Lower or steady hand → bird falls
- This replaces traditional key controls for a gesture-based game experience.

---

## 🖼️ Screenshots



---

## 🧑‍💻 Author

- **Neelam Tharun Kumar**  
  GitHub: [@NeelamTharunKumar](https://github.com/NeelamTharunKumar)

---

## ⭐️ Show Your Support

If you like the project, please give it a ⭐️ on GitHub!

---

Feel free to fork, contribute, or suggest improvements!
