# potato_plant_diseases_detector
This project aims to detect various diseases in potato plant leaves using deep learning. The project uses a Convolutional Neural Network (CNN) to classify images of potato leaves as either healthy or diseased.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Introduction
Potato plants are susceptible to various diseases that can significantly impact crop yield. Early and accurate detection of these diseases is crucial for effective treatment and prevention. This project utilizes a CNN to identify diseases in potato plant leaves from images.

## Dataset
The dataset used in this project consists of high-resolution images of potato leaves, categorized into healthy and various diseased classes. The images are preprocessed and split into training, validation, and test sets.

## Model Architecture
The model is a custom CNN built from scratch. It consists of several convolutional layers followed by max-pooling layers, and fully connected layers. The model is trained to classify images into different categories based on the presence of disease.

## Installation
To run this project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/Mayankshambhu/potato_plant_diseases_detector.git
    ```
2. Navigate to the project directory:
    ```bash
    cd potato_plant_diseases_detector
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
1. To train the model, run:
    ```bash
    python model.py
    ```
2. To start the web application, run:
    ```bash
    python app.py
    ```
3. Open a web browser and go to `http://localhost:5000` to use the application.

## Results
The trained model achieves high accuracy in classifying the potato leaf images. The performance metrics such as precision, recall, and F1-score are used to evaluate the model's effectiveness.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any features, bug fixes, or improvements.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgements
- Special thanks to the creators of the dataset.
- Thanks to the contributors and the open-source community for their valuable input and feedback.

---

Feel free to modify this template as per your project specifics.
