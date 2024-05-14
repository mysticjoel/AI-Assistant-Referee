Virtual Assistant Referee - A Streamlit Web App

This project is a Streamlit web application for detecting player contact and fouls in sports videos using machine learning.

Description

This app allows users to upload a video clip and utilizes a Convolutional Neural Network (CNN) model to analyze the video and predict whether a foul has occurred. It offers two model options:

* V1 (RGB Rendering): This model analyzes the video in its original RGB format.
* V2 (Grayscale Rendering): This model analyzes the video converted to grayscale format.

Features

* Upload video files in various formats (mp4, avi, mov, 3gp).
* Choose between two pre-trained CNN models.
* View the uploaded video.
* Get a prediction on whether a foul occurred in the video.

Installation

This project requires the following Python libraries:

* streamlit
* tensorflow
* keras
* opencv-python
* numpy

You can install them using pip:


pip install streamlit tensorflow keras opencv-python numpy


Usage

1. Clone this repository or download the project files.
2. Ensure you have the required libraries installed (see Installation).
3. Run the application using:


streamlit run app.py


4. This will launch the Streamlit app in your web browser.
5. Upload a video file using the file uploader.
6. Select the desired model version (V1 or V2) from the sidebar.
7. Click "Predict" to analyze the video and get a prediction on whether a foul occurred.




 Run

Package Requirements: `TensorFlow`,`OpenCV`,`Numpy`,`Streamlit`

To run the project:

```bash
git clone "https://github.com/mysticjoel/AI-VAR.git"

cd Virtual-Assistant-Referee

python3 -m venv venv
or
python3.11 -m venv venv

source ./venv/bin/activate

pip install -r requirements.txt

streamlit run app.py
```
