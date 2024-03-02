# MNIST Digit Recognizer with PyTorch

This Python notebook implements a digit recognition model using PyTorch to classify handwritten digits from the MNIST dataset. It utilizes a convolutional neural network (CNN) architecture and incorporates training optimizations like Adam and learning rate scheduling.

The MNIST data used here is from the Kaggle competition : Digit Recognizer which can be found here https://www.kaggle.com/competitions/digit-recognizer

## Notebook Structure

The notebook is organized into the following sections:

* **Exploratory Data Analysis:** This section includes visualizations and analysis of the MNIST dataset to gain insights into the data distribution and characteristics.
* **Preparing the Data:**  This section involves loading the dataset, applying necessary transformations (e.g., normalization, converting to tensors), and preparing it for the model.
* **Creating the Convolutional Neural Network:** Here, the convolutional neural network (CNN) architecture is defined, including its layers and their configurations. This section also includes training the CNN and testing it on the validation data.
* **Prediction on the Test set and submission :** This section involves calculating the model's performance on the test dataset using the accuracy metric and preparing the submission for Kaggle.


## Installation

**Dependencies:**

- PyTorch
- torchvision
- numpy
- pandas
- matplotlib, seaborn (Optional, for visualization)   

## Usage

1. **Clone this repository:**

   ```bash
   git clone https://github.com/YassineNefzi/Digits-Recognizer.git

2. **Navigate to the project directory:**
   ```bash
   cd Digits-Recognizer

3. **Install required dependencies (if not already installed):**
   ```bash
   pip install torch torchvision numpy pandas matplotlib seaborn # Optional

4. **Run the notebook:**
   ```bash
   jupyter notebook
