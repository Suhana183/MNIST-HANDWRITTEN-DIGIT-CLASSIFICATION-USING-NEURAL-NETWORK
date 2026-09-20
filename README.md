# MNIST Handwritten Digit Classification Using Neural Network

## 📌 Project Overview

This project uses **TensorFlow/Keras** to build a simple neural network that classifies handwritten digits from **0 to 9** using the **MNIST dataset**.

The model is trained on handwritten digit images and tested to measure its classification accuracy.

## 🎯 Objective

To develop a neural network that can recognize and classify handwritten digits using the MNIST dataset.

## 🛠️ Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Matplotlib
* Google Colab

## 📊 Dataset

The MNIST dataset contains:

* **60,000** training images
* **10,000** testing images
* Image size: **28 × 28 pixels**
* Classes: **0–9**

## 🧠 Model Architecture

```text
Input Image (28 × 28)
        ↓
Flatten Layer
        ↓
Dense Layer (128 Neurons, ReLU)
        ↓
Dropout (20%)
        ↓
Output Layer (10 Neurons, Softmax)
```

## ⚙️ Steps Performed

1. Loaded the MNIST dataset.
2. Explored and displayed sample images.
3. Normalized pixel values.
4. Built a neural network using TensorFlow/Keras.
5. Compiled and trained the model.
6. Evaluated the model using test accuracy.
7. Visualized training and validation accuracy and loss.
8. Tested the model on 5 handwritten images.
9. Compared actual and predicted labels.
10. Performed an experiment by changing the hidden layer from **128 to 64 neurons**.

## 🧪 Experiment

The original model uses **128 neurons** in the hidden layer.

For the experiment, the number of neurons was changed to **64** and the results were compared.

| Model              | Neurons | Accuracy |
| ------------------ | ------: | -------: |
| Original Model     |     128 |    ___ % |
| Experimental Model |      64 |    ___ % |

## 📈 Results

The neural network successfully learned to recognize handwritten digits from the MNIST dataset and achieved good classification accuracy.

**Test Accuracy:** ___ %

## ▶️ Google Colab Notebook

👉 **[Open the Python Notebook in Google Colab](https://colab.research.google.com/drive/1I-mAlJpkvyr4lgIHbSrXOj_pNl7Mh70D?usp=sharing)**

## 👩‍💻 Author

**Suhana**
B.Tech – Computer Science (AI & ML)

## 📝 Conclusion

The neural network successfully classified MNIST handwritten digits with good accuracy.

