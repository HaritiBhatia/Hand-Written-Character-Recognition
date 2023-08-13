
# Gujarati Handwritten Character Recognition

## Description

Welcome to the Gujarati Handwritten Character Recognition project! This endeavor aims to create a user-friendly web application capable of inputting and extracting handwritten Gujarati characters, thereby easing the process of translating and comprehending these characters. The project leverages advanced technologies and libraries to achieve its goals.

The project encompasses several key modules:

- **Image Pre-processing**: Prior to classification, the project applies robust image pre-processing techniques using libraries like OpenCV. These techniques help enhance the quality of input images, making them more suitable for analysis and recognition.

- **CNN Module**: The heart of the project lies in the Convolutional Neural Network (CNN) module. Built using TensorFlow and Keras, this deep learning model has been meticulously trained on an extensive dataset comprising 31,765 images. This dataset encompasses not only handwritten Gujarati characters but also digits ranging from 0 to 9. The CNN model employs its learned features to classify and distinguish these characters with a remarkable accuracy rate of 85%.

- **Classification and Recognition**: Once an image is pre-processed and fed into the CNN module, the classification and recognition phase takes place. The model predicts the character or digit present in the input image, providing users with accurate results in a matter of moments.

The project heavily relies on the following libraries:

- TensorFlow: An open-source machine learning framework that powers the CNN model's training and predictions.
- OpenCV: A versatile computer vision library used for image pre-processing, enhancing image quality, and extracting relevant features.
- Keras: A high-level neural networks API that simplifies the creation and training of deep learning models.
- NumPy: A fundamental package for scientific computing in Python, utilized for array manipulation and numerical operations.
- Matplotlib: A plotting library for creating visualizations and graphs to aid in data analysis.
- Pada: (Please provide a brief description of the Pada library and its role in the project).

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Installation

To set up this project on your local machine, follow these steps:

1. Clone the repository:

```bash
$ git clone https://github.com/HaritiBhatia/HandwrittenGujaratiRecognition.git
$ cd HandwrittenGujaratiRecognition
```

2. Install the required dependencies:

```bash
$ pip install -r requirements.txt
```

3. Start the web application:

```bash
$ python app.py
```

## Usage

Once the project is set up, you can access the web application by navigating to `` in your web browser. Here, you can input handwritten Gujarati characters or digits, and the CNN model will classify them.

Here's an example of how to use the application:

1. Visit `` in your web browser.
2. Draw or upload a handwritten Gujarati character or digit.
3. Click the "Recognize" button.
4. The application will display the recognized character along with its classification.

## Contributing

We welcome contributions from the community! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature-new-feature`
3. Commit your changes: `git commit -am 'Add a new feature'`
4. Push the branch: `git push origin feature-new-feature`
5. Create a pull request.



---

