
# 🛡️ Drowsiness Detection with Face Recognition

This project is a real-time **driver drowsiness detection system** that authenticates the user through **face recognition** before monitoring begins. It alerts the driver when drowsiness is detected using facial landmarks and eye aspect ratio.

---

## 📌 Features

- 🔐 **Face Recognition**: Ensures only authorized users can start the system
- 👁️ **Drowsiness Detection**: Uses Eye Aspect Ratio (EAR) to detect prolonged eye closure
- 🔊 **Alarm Trigger**: Sounds an alert when drowsiness is detected
- 🎥 **Real-time Processing** using OpenCV and live webcam feed

---

## 🛠️ Tech Stack

- **Python**
- **OpenCV**
- **dlib**
- **face_recognition**
- **NumPy**

---

## 📂 Project Structure

| File | Description |
|------|-------------|
| `register_face.py` | Capture and save an authorized user's face encoding |
| `drowsiness_with_face_recognition.py` | Main script: face recognition + drowsiness detection |

---

## 🚀 How to Run

### 1. Clone the repository
```bash
git clone https://github.com/yourusername/rohitsproject.git
cd rohitsproject
```

### 2. Install required packages
```bash
pip install opencv-python dlib face_recognition numpy
```

> ⚠️ Make sure `dlib` is installed correctly (it may require CMake and Visual Studio Build Tools or Xcode on macOS)

### 3. Register your face
```bash
python register_face.py
```

- A webcam window will open
- Press `'s'` to capture your face
- Your face encoding will be saved

### 4. Run the main detection script
```bash
python drowsiness_with_face_recognition.py
```

- The program will first verify your face
- Once verified, it will monitor your eye activity
- If your eyes stay closed too long, an alarm will sound

---

## 📸 Example

![demo](https://user-images.githubusercontent.com/example/demo.gif)

---

## 📃 License

This project is licensed under the [MIT License](LICENSE)

---

## 🙋‍♂️ Author

**Rohit**  
🔗 [GitHub](https://github.com/rohits0209)
