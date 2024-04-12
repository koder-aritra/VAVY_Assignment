# Computer Vision and Deep Learning Toolkit

Welcome to the Computer Vision and Deep Learning Toolkit! This repository houses a comprehensive collection of Python scripts designed to facilitate various tasks in computer vision and deep learning projects. Whether you're working on object detection, image classification, or data preprocessing, this toolkit provides the necessary tools to streamline your workflow.

## Features

### 1. Custom Dataset Handling
The `CustomDataset.py` script offers a flexible solution for creating custom datasets for deep learning models. It allows you to load images and their corresponding bounding box annotations from a text file, with support for resizing, padding, and normalization.

### 2. Dataset Generation
With the `GenerateDataset.py` script, you can easily generate datasets by processing image and annotation files from a specified folder. This script automates the process of preparing dataset information and ensures uniformity in dataset structure by handling padding of bounding box annotations.

### 3. YOLOv3 Model Training
TrainYOLO.py simplifies the training process for YOLOv3 object detection models. It prepares the dataset, updates the YOLOv3 configuration for rectangle detection, and fine-tunes the model with the specified dataset.

### 4. Object Detection
Both `ObjectDetectionYOLO.py` and `ObjectDetection.py` scripts enable object detection in images using pre-trained YOLOv3 models. They detect objects with bounding boxes and class labels, providing a seamless solution for object detection tasks.

### 5. Image Overlay
The `ImageOverlay.py` script offers a convenient way to overlay multiple images with adjustable transparency. This functionality is particularly useful for visualizing multiple images simultaneously, aiding in data analysis and model evaluation.

### 6. Rectangle Detection
RectangleDetection.py detects rectangles in images using contour detection and approximation techniques. It draws bounding boxes around detected rectangles, facilitating tasks such as document scanning and object localization.

## Dependencies

- Python 3.x
- OpenCV
- NumPy
- PyTorch

Ensure all dependencies are installed before running the scripts.

## Usage

1. Clone the repository to your local machine.
2. Navigate to the desired script based on your task.
3. Execute the script using a Python interpreter with the appropriate arguments and configurations.

## Contribution

Contributions to this repository are welcome! If you have any ideas for improvement, new features to add, or issues to report, please feel free to create a pull request or submit an issue.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

This toolkit utilizes various open-source libraries and frameworks, including OpenCV, NumPy, and PyTorch. Special thanks to the contributors of these projects for their invaluable contributions to the field of computer vision and deep learning.
