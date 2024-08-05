# Object Detection with YOLOv3

This project implements real-time object detection using the YOLOv3 model. The script captures video from your webcam and detects objects in real-time.
Features

-Real-time object detection using YOLOv3.

-Draws bounding boxes around detected objects.

-Displays the class label and confidence score for each detected object.

## Preview

![ObjectDetection](https://github.com/user-attachments/assets/d5c7ecbe-a8a6-42b3-b14b-134420c8e886)


## Requirements

Before running the script, make sure to install the necessary Python libraries and download the required YOLOv3 files.
Dependencies

Create and activate a virtual environment (optional but recommended):

bash

python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

Install dependencies:

bash

pip install -r requirements.txt

## YOLOv3 Files

To get started with YOLOv3, download the following files and save them in your project directory:

1. **YOLOv3 Weights**: [Download yolov3.weights](https://pjreddie.com/media/files/yolov3.weights)
2. **YOLOv3 Configuration**: [Download yolov3.cfg](https://github.com/pjreddie/darknet/blob/master/cfg/yolov3.cfg)
3. **COCO Names File**: [Download coco.names](https://github.com/pjreddie/darknet/blob/master/data/coco.names)

Ensure that these files are located in the same directory as the `main.py` script.


## Usage

Run the script to start the object detection:

bash

python main.py

The script will open a webcam feed and start detecting objects in real-time.
Configuration

Confidence Threshold: Adjust the confidence variable in the script to set the minimum confidence level for object detection.

Frame Resolution: The frame is resized to 416x416 to speed up processing. Modify this size in the script if needed.

## Troubleshooting

Camera Issues: Ensure your webcam is properly connected and accessible.

Performance: Reducing the frame resolution or processing fewer frames per second can help with performance.


