# Handwritten Digit Recognition using Logistic Regression📝📝

This project implements a handwritten digit recognition system using logistic regression. The model is trained to classify images of handwritten digits (0-9) from the MNIST dataset.

## Dataset

The MNIST dataset is a classic benchmark dataset in machine learning and computer vision. It consists of:

- **Training Set**: 60,000 images of handwritten digits (0-9), each image is 28x28 pixels.
- **Test Set**: 10,000 images of handwritten digits (0-9), used for evaluating the model.

The dataset is widely used for training and testing machine learning models in the field of image recognition.

## Model Architecture

Logistic regression is used as a simple yet effective model for this task:

- **Input**: Each image is flattened into a vector of size 784 (28x28).
- **Output**: Logistic regression outputs probabilities for each digit class (0-9).

## Files

- `HandWrittenDigitRecognition.ipynb`: Jupyter notebook containing the code for data preprocessing, model training, evaluation, and prediction using logistic regression.

## Dependencies

Ensure the following libraries are installed in your Python environment:

- Python 3.x
- NumPy
- Matplotlib
- Scikit-learn

Install dependencies using:

```bash
pip install numpy matplotlib scikit-learn
```

## Usage

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Aru-2359/HandWrittenDigitRecognition.git
   cd HandWrittenDigitRecognition
   ```

2. **Open and run the Jupyter notebook:**

   - Launch Jupyter Notebook:

     ```bash
     jupyter notebook
     ```

   - Navigate to `HandWrittenDigitRecognition.ipynb` and open it.

3. **Execute the notebook:**

   - Follow the instructions in the notebook to preprocess the data, train the logistic regression model, evaluate its performance, and make predictions on new images.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- The MNIST dataset is sourced from the official repository of the National Institute of Standards and Technology (NIST).
