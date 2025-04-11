🧠 Features
Uses Faster R-CNN ResNet-50 FPN pre-trained on COCO.
Automatically detects multiple classes such as person, car, truck, bicycle, etc.
Applies a confidence threshold to filter weak detections.
Draws bounding boxes and class labels on the image.

🛠️ Requirements
This notebook is designed to run in Google Colab, but can also work locally with minor changes.

Libraries Used:
torch
torchvision
cv2 (OpenCV)
numpy
matplotlib (optional for visualization)
google.colab.patches (for displaying images in Colab)

🏷️ Classes Detected
The model is trained on the COCO dataset, and can detect 91 classes including:
person, car, truck, bicycle, dog, airplane, traffic light, backpack, laptop, etc.
