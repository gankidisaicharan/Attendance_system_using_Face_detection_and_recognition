# Attendance System using Face Detection and Recognition
Utilizing PyTorch and Gradio, this system employs a refined ResNet-18 model for face detection and recognition to automate attendance management. It identifies individuals from images, ensuring accurate and efficient attendance logging in various educational and organizational contexts.



Introduction

The Attendance System using Face Detection and Recognition is an innovative solution designed to automate the attendance management in various domains like educational institutions, organizations, or events. The system utilizes deep learning to detect and recognize faces, thus logging the attendance of individuals in a seamless manner.

Features

Automated Attendance Management: Eliminate manual entry by automatically recognizing and logging individuals' attendance.
Face Detection and Recognition: Utilize a robust model for accurate face detection and recognition even in diverse scenarios.
Data Pre-processing and Augmentation: Enhance model training with augmented data, improving recognition capabilities.
Comprehensive Model Evaluation: Employ various metrics for detailed model performance analysis.
Hyperparameter Tuning: Optionally explore different model hyperparameters for improved performance.
User-Friendly Visualization: Visualize face recognition results and model performance metrics in a comprehensible manner.


System Workflow

Data Pre-processing: Implement transformations and augmentations to enhance the training dataset.
Model Definition and Training: Employ a pre-trained ResNet-18 model, fine-tuned to recognize faces from a custom dataset, with an integrated training loop for optimization.
Model Evaluation: Utilize metrics like classification reports and confusion matrices to assess and visualize the model's predictive performance.
Face Detection and Recognition: Use MTCNN for face detection and the trained ResNet model for face recognition.
Attendance Logging: Recognized faces are logged into the attendance system, ensuring accurate and efficient management.

Prerequisites


Python 3.x
TensorFlow 2.x
Torch & torchvision
OpenCV
MTCNN
Gradio (for optional GUI components)
Optuna (for optional hyperparameter tuning)

Usage

Training the Model: Ensure your dataset is structured appropriately and adjust the paths in the script. Train the model using the provided training script.
Recording Attendance: Utilize the face detection and recognition script to identify individuals and log their attendance automatically.
Visualizing Results: Run the visualization script to see the model predictions and evaluation metrics.
Contributing

Feel free to fork the project, create a feature branch, and send us a pull request. For bugs, feature requests, or additional help, please open an issue.
