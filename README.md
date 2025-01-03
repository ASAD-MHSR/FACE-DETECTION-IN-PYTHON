# FACE-DETECTION-IN-PYTHON
This project utilizes Python to implement a simple yet effective face detection system using the OpenCV library. The aim of the project is to demonstrate how machine learning techniques can be applied to real-time computer vision tasks, specifically detecting human faces in images or video streams.


# Method One

How to Run

Clone the Repository:

`git clone https://github.com/AXAD-MHSR/face-detection.git
cd face-detection`

Set Up the Environment:

Create a virtual environment (optional but recommended):

`python -m venv venv
source venv/bin/activate`  # On Windows: `venv\Scripts\activate`

Install dependencies:

`pip install opencv-python opencv-python-headless`

Run the Script:

`python main.py`

Usage:

Real-Time Mode: Use your webcam to detect faces.

Image Mode: Edit the script to process a specific image file.

Exit: Press the 'a' key to quit the application during runtime.

Requirements

Python 3.x

OpenCV library

# Method Two: Setting up Face Detection with Jupyter Notebook
Step 1: Download the Notebook file to your system.

Step 2: Open Command Prompt (CMD) and install JupyterLab and Jupyter Notebook using the following commands:

`pip install jupyterlab
pip install notebook`

Step 3: Start Jupyter Notebook by running this command in the Command Prompt:

`jupyter notebook`

Step 4: Open the downloaded notebook file from your browser and run the cells.

Important Notes:

Before running the code, ensure that the path to the haarcascade_frontalface_default.xml file is correctly specified in the code. For example:
```face_cap = cv2.CascadeClassifier("C:/path/to/haarcascade_frontalface_default.xml")```

Make sure your camera is accessible and not being used by any other application.

That's it! You're ready to detect faces!
