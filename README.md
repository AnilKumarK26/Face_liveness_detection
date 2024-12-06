# 🛠️ Face Liveness Detection Project

## 🚀 Overview
This project implements a **Face Liveness Detection System** to prevent spoofing attacks during facial authentication processes. The system ensures that the detected face is real and not a spoof (e.g., photo, video, or mask). It is designed to operate efficiently within a browser environment and supports real-time detection.

---

## 🧠 Features

- 🎥 **Real-Time Detection**: Supports live webcam feeds for liveness detection.
- 🔍 **Spoof Detection**: Differentiates between real and spoof faces (photo, video, mask).
- ⚡ **High Performance**: Works in under 500ms with a model size less than 5MB.
- 🌐 **Browser Compatibility**: Operates in modern browsers (Chrome, Firefox, Edge) using ONNX.js or TensorFlow.js.

---

## 🛠️ Technologies Used

- **Programming Language**: Python 🐍, JavaScript
- **Deep Learning Frameworks**: TensorFlow/Keras, ONNX.js
- **Web Integration**: Flask 🌐
- **Dataset**: CelebA-Spoof, iBeta, Anti-Spoofing Real Dataset

---

## ⚙️ How It Works
1. **Webcam Integration**:
   - Captures live video feed via the browser or desktop webcam.
2. **Preprocessing**:
   - Extracts frames from the video feed and prepares them for model inference.
3. **Liveness Detection**:
   - The deep learning model classifies each frame as **real** or **spoof**.
4. **Output**:
   - Displays detection results on the browser interface.

---

## 🧑‍💻 Setup & Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/face-liveness-detection.git
   cd face-liveness-detection
   ```

2. **Install Requirements**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Application**:
   ```bash
   python app.py
   ```

4. **Access the Application**:
   Open the application in your browser (e.g., `http://localhost:5000`).

---

## 📂 Directory Structure

```
├── static/           # Static files (CSS, JS, images)
├── templates/        # HTML templates
├── app.py            # Main Flask application
├── requirements.txt  # Python dependencies
└── README.md         # Project documentation
```

---

## 🔬 Future Improvements

- 🌍 **Multi-Language Support**: Add support for multiple languages in the browser interface.
- 📊 **Advanced Spoof Scenarios**: Enhance model performance for complex spoof types (e.g., 3D masks).
- ☁️ **Cloud Integration**: Enable cloud-based deployment for scalability.
- 📱 **Mobile Optimization**: Adapt the system for mobile browser compatibility.

---

## 🤝 Contributing
Contributions are welcome! Feel free to submit a pull request or report an issue.

---

## 📜 License
This project is licensed under the MIT License. See the LICENSE file for details.

---

## ❤️ Acknowledgements
Special thanks to open-source contributors and the research community for datasets and resources.

---

## 📧 Contact
For questions or support, reach out at anilkumarkedarsetty@gmail.com.

