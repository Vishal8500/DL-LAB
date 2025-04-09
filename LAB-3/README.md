This project demonstrates transfer learning using PyTorch to classify images from two different datasets:
Hymenoptera Dataset: distinguishing between bees and ants [LINK](https://www.kaggle.com/datasets/thedatasith/hymenoptera)
Custom Pizza Dataset: training and testing classification for pizza images [LINK](https://www.kaggle.com/datasets/projectshs/pizza-classification-data)
It leverages pre-trained models (ResNet18) to fine-tune and adapt for these specific tasks with limited data, showcasing how powerful transfer learning can be for real-world image classification problems.

🔍 Key Features
🔄 Transfer Learning with ResNet18:
Uses a pre-trained ResNet18 model from torchvision.models as a feature extractor.
Final fully connected layer replaced to adapt for binary classification tasks (e.g., bees vs ants, pizza vs non-pizza).

📦 Multi-Dataset Support:
Handles Hymenoptera dataset (bees 🐝 vs ants 🐜).
Processes a custom pizza dataset and supports prediction on individual images (e.g., pizza.jpg).

🧠 Fine-Tuning Pipeline:
Efficient training with support for GPU acceleration (cuda:0).
Training/validation split with performance tracking (loss + accuracy).
Implements learning rate scheduling for improved convergence.
Saves the best model based on validation performance.

🖼️ Data Augmentation & Normalization:
Training: Random resized crop, horizontal flip, normalization.
Validation: Resize, center crop, normalization.
Built using torchvision.transforms.

📊 Visualization & Inference:

Displays sample predictions for visual inspection.
Supports standalone image inference (e.g., classifying a pizza image using the trained model).
Visual output shows both image and predicted class label.
