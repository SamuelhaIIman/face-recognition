# Face Recognition

This project leverages OpenCV and DeepFace to implement real-time face recognition. The application captures video feed from your webcam, compares faces in the live video to a reference image, and displays whether a match is found. This project is ideal for learning about computer vision, facial recognition, and multithreading in Python.

---

## Features

- Real-time video feed with OpenCV.
- Face matching using the DeepFace library.
- Multithreading for efficient face verification.
- Easy-to-use interface with on-screen match status.
- Fully customizable reference images.

---

## Prerequisites

Make sure you have the following installed on your system:

    - Python 3.7 or later
    - Webcam (for live video feed)

---

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/face-recognition.git
cd face-recognition
```
2. Install the required Python packages:
```bash
pip install -r requirements.txt
```
3. The key dependencies include:

- `opencv-python`: For video capture and image processing.
- `deepface`: For facial recognition and verification.

4. Add your reference image:

    - Save the image of the person you want to recognize in the person1 folder.
    - Name it `my-face.jpg` (or update the code to use a different file name).
---

## Usage

1. Run the script:
```bash
python face.py
```
2. The webcam will open, and the application will start processing video frames.

3. On-Screen Indicators:

    - A green "MATCH!" message will appear if the face in the video matches the reference image.
    - A red "NO MATCH!" message will appear otherwise.

4. Press 'q' to quit the application.