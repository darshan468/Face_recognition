# Face_recognition
This is a real-time face recognition script built with Python, face_recognition, and OpenCV. The program uses your webcam to detect faces and identify them based on a directory of known images.

# What It Does
The script performs the following steps:

Loads known faces: It reads images from a specified directory (face_recognition/darshan). It then creates a digital "encoding" for each face and stores the associated name (the filename).

Activates the webcam: It uses your computer's webcam to capture video in real-time.

Detects and recognizes faces: For each frame from the webcam, it:

  Finds all faces.

  Compares the detected faces to the known face encodings.

  If a match is found, it labels the person with the name from the image file. If no match is found, the person is labeled as "Unknown".

Displays the result: It draws a green box around each detected face and displays the person's name above it.

Exits gracefully: The program runs continuously until you press the ESC key.

# Customization
You can change the known_faces_dir variable to a different folder path if you wish.

You can create multiple folders inside face_recognition to organize different groups of people.

# Technologies Used
Python 3: The core programming language.

face_recognition: A powerful library for face detection and recognition.

OpenCV (cv2): A library used for capturing video from the webcam and displaying the output.

os: A standard Python library for interacting with the operating system, used here for managing file paths.


