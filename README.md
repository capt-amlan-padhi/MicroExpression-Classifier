# README.md

---

# Microexpressions Classification

Welcome to the Microexpressions Classification repository. This project is an application of Convolutional Neural Networks (CNNs) for classifying microexpressions in images into seven categories: anger, disgust, fear, happiness, neutral, sadness, and surprise. The model was trained using TensorFlow and Keras libraries, and it uses image augmentation for improving the model's performance.

## Dataset

The dataset used for this project is the [Micro Expressions Dataset](https://www.kaggle.com/datasets/kmirfan/micro-expressions) from Kaggle. It consists of images of facial expressions labeled into seven categories.

## Project Files

This repository includes the following files:

1. `Untitled.ipynb`: This is the main Jupyter notebook file that contains all the Python code for the project.
2. `microexpressions_model2.h5`: This is the pre-trained model file that can be loaded directly to make predictions.
3. `anger.jpg`, `microexpression.jpg`, `microexpression1.jpg`: These are sample images that the model is tested on.

## How the Project Works

The project involves the following steps:

1. Loading and preprocessing of images for training and validation.
2. Defining and compiling the CNN model architecture.
3. Training the CNN model using the training data, while also validating using the validation data.
4. Evaluating the model's performance using the validation data.
5. Saving the model for future predictions.
6. Loading the model and making predictions on unseen data.

## How to Run the Project

- Clone this repository to your local machine.
- Navigate to the directory of the project.
- You can run the `Untitled.ipynb` notebook to see how the model is trained. However, if you simply want to load the pre-trained model and make predictions, you can load the `microexpressions_model2.h5` file using TensorFlow and Keras.

```python
from tensorflow.keras.models import load_model
model = load_model('microexpressions_model2.h5')
```
- After loading the model, you can use it to make predictions.

## Prerequisites

- This project requires Python 3. Python can be downloaded from [here](https://www.python.org/downloads/).
- The project also requires the following Python libraries: os, cv2, numpy, tensorflow. These can be installed using pip.

## Contributing

- We love to have your help to make this project better. All contributions are welcome!
- For major changes, please open an issue first to discuss what you would like to change.
- Please make sure to update tests as appropriate.

## License

- This project is licensed under the [MIT License](https://choosealicense.com/licenses/mit/).

---

We hope you find this project useful for your learning or research in microexpression classification using deep learning. Your satisfaction is our priority. Happy learning!
