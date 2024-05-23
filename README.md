# Wheat Crop Disease Prediction

## Overview

This repository contains code for a machine learning model to predict diseases found in wheat crops. The model utilizes a transfer learning approach, leveraging pre-trained deep learning models for image classification.

## Dataset

The labeled image dataset used for training and evaluation can be found in the "wheat_dataset.zip" file. This dataset consists of images of wheat crops affected by various diseases.

## Getting Started

To train the model or test it on new data, follow these steps:

1. Clone this repository to your local machine:

```bash
git clone https://github.com/your-username/Wheat-Crop-Disease-Prediction.git
```

2. Navigate to the cloned directory:

```bash
cd Wheat-Crop-Disease-Prediction
```

3. Download the dataset and extract it into the "data" directory:

```bash
# Replace <link-to-dataset> with the actual link to the dataset
wget <link-to-dataset> -O wheat_dataset.zip
unzip wheat_dataset.zip -d data/
```

4. Open the Jupyter Notebook "Wheat_Crop_Disease_Prediction.ipynb" to train the model, evaluate its performance, and make predictions.

## Model Architecture

The machine learning model architecture is based on a pre-trained deep learning model (e.g., VGG16) with additional custom layers for classification. For details on the model architecture, refer to the notebook.

## Dependencies

- Python 3.x
- TensorFlow
- Keras
- Matplotlib
- NumPy
- Pandas

Install the required dependencies using pip:

```bash
pip install tensorflow keras matplotlib numpy pandas
```

## Contributing

Contributions are welcome! If you have any suggestions, bug fixes, or improvements, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
