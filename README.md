# FaceRecognition

**Facial Recognition System** is a Python-based application that detects and recognizes faces in real-time using **OpenCV** and pre-trained **Haar Cascade classifiers**. It can be used for attendance systems, security, and identity verification.

## Features

* Real-time face detection using webcam.
* Face recognition with pre-trained models.
* Attendance marking functionality.
* Lightweight and easy to deploy.

## Tech Stack

* **Programming Language:** Python
* **Libraries:** OpenCV, NumPy, face\_recognition
* **Model:** Haar Cascade classifier for face detection

## Installation

1. **Clone the repository:**

```bash
git clone <repository_url>
cd Facial-Recognition-System
```

2. **Set up Python environment:**

```bash
python -m venv venv
source venv/bin/activate   # Linux/macOS
venv\Scripts\activate      # Windows
pip install -r requirements.txt
```

## Usage

1. Run the face detection script:

```bash
python detect_faces.py
```

2. For recognition and attendance, run:

```bash
python recognize_faces.py
```

3. The system will use your webcam to detect and recognize faces, marking attendance automatically.

## Project Structure

```
Facial-Recognition-System/
├── detect_faces.py       # Real-time face detection
├── recognize_faces.py    # Face recognition and attendance
├── haarcascades/         # Pre-trained Haar Cascade models
├── dataset/              # Folder to store known faces
├── requirements.txt      # Python dependencies
└── README.md
```

## Future Improvements

* Integrate with a database to store attendance records.
* Add support for multiple cameras.
* Improve recognition accuracy using deep learning models like FaceNet or Dlib.

## License

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.
