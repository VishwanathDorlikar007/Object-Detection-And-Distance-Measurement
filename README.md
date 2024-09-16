**Methodology**
**OpenCV Setup**: We initiated by setting up OpenCV to access the camera and capture video frames.

**Model Loading:** We loaded the pre-trained object detection model which is SSD MobileNet v3 Large Coco 2020 into memory.

**Inference on Video Frames**: For each captured frame, we performed inference using the loaded model. This involves passing the frame through the model's convolutional layers.

**Bounding Box and Confidence Score Extraction**: The model's output provides bounding boxes encompassing the detected objects within the frame and corresponding confidence scores for each detection.
**Bounding boxes**: These define rectangular regions around the detected objects.
**Confidence scores**: These represent the model's certainty for each detection, ranging from 0 (low confidence) to 1 (high confidence).

**Thresholding**: We set a confidence threshold (e.g., 0.5) to filter out detections with low confidence, improving the accuracy of our results.

![image](https://github.com/user-attachments/assets/d5986826-3434-42f6-8421-0586a8e4e0ab)

