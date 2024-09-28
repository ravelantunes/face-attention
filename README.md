# Face Attention

This project aims to create a system that uses facial landmarks to determine whether someone is looking towards the camera, and therefore maintaining a level of attention.
The project consists of the following parts:

- A script that continuously captures image frames to for training.
- A model pipeline that detect individual faces in the image frames and extracts facial landmarks.
- A simple xgboost model that uses the landmarks to classify level of attention.
- An inference system that leverages the pipeline in real-time

## Installation

Make sure python3 is installed on your system. Then, create a virtual environment and install the required packages using the following commands:

Create a virtual environment and install the required packages using the following commands:

```bash
python3 -m venv venv
source venv/bin/activate
pip install .
```


