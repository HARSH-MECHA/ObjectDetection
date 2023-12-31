# ObjectDetection
This Python script utilizes YOLOv3, a state-of-the-art object detection algorithm, to perform real-time object detection on live webcam feeds. 

# YOLOv3 Object Detection

This Python script utilizes YOLOv3, a state-of-the-art object detection algorithm, to perform real-time object detection on live webcam feeds. The script captures frames from the webcam, processes them using the YOLOv3 model, and annotates the detected objects with bounding boxes and labels in the video stream.

## Features

- **Real-time Object Detection:** Processes frames from a webcam in real-time, identifying and annotating various objects present in the video stream.
- **Flexible Configuration:** Allows users to adjust configuration parameters such as confidence and NMS thresholds for object detection.
- **Speech Synthesis:** Utilizes the `pyttsx3` library to generate spoken alerts for detected objects.

## Technologies Used

- **OpenCV:** Used for video capture, image processing, and drawing bounding boxes on detected objects.
- **YOLOv3:** Leveraged for its high-speed and accurate object detection capabilities.
- **Python:** Scripting language used for implementing the object detection functionality.

## Instructions

1. **Installation:**
   - Clone the repository:

     ```bash
     git clone https://github.com/HARSH-MECHA/ObjectDetection.git
     ```

   - Install required dependencies:

     ```bash
     pip install opencv-python
     ```

2. **Usage:**
   - Run the Python script `object_detection_yolov3.py`.
   - Ensure a webcam is connected and accessible.
   - Objects detected by the YOLOv3 model will be displayed on the live webcam feed.

3. **File Structure:**

- `object_detection_yolov3.py`: Main Python script for object detection.
- `coco.names`: File containing COCO dataset class names.
- `yolov3.cfg`: YOLOv3 configuration file.
- `yolov3.weights`: Pre-trained YOLOv3 model weights.

