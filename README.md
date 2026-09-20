# MNIST Handwritten Digit Classifier 🧠

## 📌 Project Overview

This project uses a simple **Neural Network** built with **TensorFlow and Keras** to recognize handwritten digits from **0 to 9**.

The model is trained using the **MNIST handwritten digit dataset**, which contains thousands of images of handwritten numbers. After training, the model can predict the digit shown in a new image.

## 🎯 Objective

The main objectives of this project are:

* Load and explore the MNIST dataset.
* Display sample handwritten digit images.
* Preprocess the image data.
* Build a simple neural network using TensorFlow/Keras.
* Train the model on handwritten digits.
* Evaluate the model's performance.
* Predict digits from test images.

## 🛠️ Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Matplotlib
* Jupyter Notebook / Google Colab

## 📂 Dataset

The project uses the **MNIST dataset**.

The dataset contains:

* **60,000** training images
* **10,000** test images
* Image size: **28 × 28 pixels**
* **10 classes:** digits 0–9

## 🧠 Model Architecture

The neural network consists of:

1. **Flatten Layer** – Converts the 28 × 28 image into a one-dimensional array.
2. **Dense Layer** – Learns patterns from the handwritten digits.
3. **Output Layer** – Uses Softmax activation to calculate the probability of each digit from 0 to 9.

Example architecture:

```text
Input Image (28 × 28)
        ↓
Flatten Layer
        ↓
Dense Layer (128 neurons)
        ↓
Output Layer (10 neurons)
        ↓
Predicted Digit (0–9)
```

## ⚙️ Data Preprocessing

The pixel values of the images are normalized from the range **0–255** to **0–1**.

This helps the neural network train more efficiently.

```python
x_train = x_train / 255.0
x_test = x_test / 255.0
```

## 🚀 Training

The model is compiled using:

* **Optimizer:** Adam
* **Loss Function:** Sparse Categorical Crossentropy
* **Metric:** Accuracy

The model is then trained using the training dataset.

```python
model.compile(
    optimizer='adam',
    loss='sparse_categorical_crossentropy',
    metrics=['accuracy']
)
```

## 📊 Model Evaluation

After training, the model is evaluated using the test dataset.

The test accuracy shows how well the trained model can recognize handwritten digits that it has not seen during training.

## 🔍 Predictions

Five test images were passed to the trained model.

The predicted digit is obtained by selecting the class with the highest **Softmax probability**.

Example:

```text
Actual Digit: 7
Predicted Digit: 7
```

## 📸 Sample Output

The project displays sample MNIST images and their predicted labels to demonstrate the performance of the trained neural network.

## 📁 Project Structure

```text
MNIST-Handwritten-Digit-Classifier/
│
├── MNIST_Classifier.ipynb
├── README.md
└── report.pdf
```

## 💡 What I Learned

Through this project, I learned:

* Basics of neural networks
* Loading datasets using TensorFlow/Keras
* Image preprocessing
* Model building and training
* Model evaluation
* Softmax-based classification
* Making predictions using a trained model

## 🔮 Future Improvements

The project can be improved by:

* Using Convolutional Neural Networks (CNNs)
* Increasing model accuracy
* Adding a graphical interface for handwritten digit input
* Allowing users to draw a digit and get a prediction
* Comparing different neural network architectures

## 👩‍💻 Author

**Suhana**

B.Tech – Computer Science (AI & ML)

---

⭐ If you find this project useful, consider giving it a star!

