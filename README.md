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
git clone https://github.com/Praneethguduru/FaceRecognition
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
1. Add faces to the Images Folder


2. Update or add the student details to AddDataToDatabase.py according to the the format
```bash
data = {
    "(roll number)":
        {
            "name": "XYZ",
            "major": "XYZ",
            "starting_year": IIII,
            "total_attendance": 0,
            "standing": "X",
            "year": X,
        }
```

4. Run the encoder script:

```bash
python EncodeGenerator.py
```

2. For recognition and attendance, run:

```bash
python main.py
```

3. The system will use your webcam to detect and recognize faces, marking attendance automatically.



## Future Improvements

* Integrate with a database to store attendance records.
* Add support for multiple cameras.
* Improve recognition accuracy.

