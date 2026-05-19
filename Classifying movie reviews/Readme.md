# Classifying Movie Reviews

This project is a detailed implementation of the **IMDB Sentiment Analysis** example from **Chapter 2** of the book:
> **Deep Learning with Python** by François Chollet

## About the Project

In this notebook, movie reviews are classified as either **positive** or **negative**.  
The implementation follows a simple feedforward neural network approach using Keras.

## Dataset

The project uses the **IMDB Dataset.csv** file, where:

- `review` contains the text of each movie review
- `sentiment` contains the labels (`positive` or `negative`)

## Main Steps

- Load and prepare the IMDB review dataset
- Convert sentiment labels to numeric values
- Split the data into training and test sets
- Tokenize the review texts
- Pad and truncate sequences
- Vectorize the sequences
- Build a Sequential neural network
- Train the model
- Evaluate training and validation performance

## Model Architecture

The notebook uses a simple neural network with:

- Dense layer with 16 units and ReLU activation
- Dense layer with 16 units and ReLU activation
- Output layer with 1 unit and sigmoid activation

## Tools & Technologies

- Python
- Keras
- TensorFlow
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Notes

This project is a practice implementation closely related to the examples and exercises in **Chapter 2** of *Deep Learning with Python*.  
It is intended for educational and learning purposes.
