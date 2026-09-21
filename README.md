# Deep Learning Practicals

A collection of **Deep Learning practical implementations** covering fundamental concepts, neural network architectures, model optimization techniques, and real-world applications using Python, TensorFlow/Keras, Scikit-learn, NumPy, Pandas, and Matplotlib.

This repository contains **12 practical implementations** developed as part of the Deep Learning coursework.

---

## 📌 Overview

The repository provides hands-on implementations of different machine learning and deep learning techniques, progressing from basic regression and error evaluation to advanced architectures such as:

* Feedforward Neural Networks
* Regularization
* Hyperparameter Optimization
* Convolutional Neural Networks
* Transfer Learning
* Recurrent Neural Networks
* LSTM-based Sequence Models
* Autoencoders
* Generative Adversarial Networks

The practicals use datasets and applications from domains such as **housing, healthcare, computer vision, finance, natural language processing, and generative AI**.

---

## 📚 Practicals

| No.    | Practical                                                                                                              | Key Concepts                                         |
| ------ | ---------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------- |
| **1**  | [Linear Regression & Error Metrics](./Practical1-linear_regression_error_metrics.ipynb)                                | Linear Regression, MAE, MSE, RMSE                    |
| **2**  | [Housing Price Prediction using DFFN](./Practical2-Housing_Price_Prediction_DFFN.ipynb)                                | Feedforward Neural Network, Regression               |
| **3**  | [Breast Cancer Classification](./Practical3-Breast-Cancer-Classification.ipynb)                                        | Neural Network Classification, Binary Classification |
| **4**  | [Regularization Techniques](./Practical4_Regularization_Techniques.ipynb)                                              | Regularization, Dropout, Overfitting Prevention      |
| **5**  | [Hyperparameter Tuning & Model Optimization](./Practical5_Hyperparameter_Tuning_&_Model_Optimization_.ipynb)           | Hyperparameter Tuning, Model Optimization            |
| **6**  | [Handwritten Digit Recognition](./Practical6_Handwritten_Digit_Recognition.ipynb)                                      | Image Classification, Neural Networks                |
| **7**  | [Dog Breed Classification using Transfer Learning](./Practical7_Dog_Breed_Classification_using_TransferLearning.ipynb) | CNN, Transfer Learning, Image Classification         |
| **8**  | [Stock Market Prediction using RNN](./Practical8_StockMarket_Prediction_using_Recurrent_Neural_Networks.ipynb)         | RNN, Time-Series Prediction                          |
| **9**  | [Slot Filling using RNN](./Practical9_Slot_Filling_using_Recurrent_Neural_Networks.ipynb)                              | NLP, Sequence Labeling, RNN                          |
| **10** | [Credit Card Fraud Detection using Deep Learning](./Practical10_Credit_Card_Fraud_Detection_using_Deep_Learning.ipynb) | Deep Neural Networks, Fraud Detection                |
| **11** | [Convolutional Autoencoder](./Practical11_Convolutional_Autoencoder.ipynb)                                             | Autoencoders, CNN, Representation Learning           |
| **12** | [Generative Adversarial Network](./Practical12_Generative_Adversarial_Network.ipynb)                                   | GAN, Generator, Discriminator, Image Generation      |

---

## 🧠 Topics Covered

### 1. Regression & Model Evaluation

The initial practical introduces regression concepts and commonly used error metrics:

* Linear Regression
* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)

These concepts provide the foundation for evaluating predictive models.

### 2. Feedforward Neural Networks

A Deep Feedforward Neural Network is implemented for housing price prediction.

Key concepts include:

* Data preprocessing
* Feature encoding
* Feature scaling
* Dense neural network layers
* Training and validation
* Regression evaluation

### 3. Classification

A neural network is used for breast cancer classification.

The practical demonstrates:

* Binary classification
* Data preprocessing
* Neural network architecture
* Model training
* Classification evaluation

### 4. Regularization

Different techniques for reducing overfitting are explored, including:

* Regularization
* Dropout
* Model generalization
* Training vs. validation performance

### 5. Hyperparameter Optimization

The repository also demonstrates how model performance can be improved through hyperparameter tuning.

Parameters such as:

* Learning rate
* Number of layers
* Number of neurons
* Batch size
* Training configuration

can be optimized to improve model performance.

### 6. Computer Vision

Image-based deep learning applications include:

* Handwritten digit recognition
* Dog breed classification
* Transfer learning
* Convolutional neural networks

These practicals demonstrate how neural networks can learn visual features from images.

### 7. Transfer Learning

The dog breed classification practical demonstrates the use of a pre-trained deep learning model and transfer learning to solve an image classification problem.

This reduces the need to train a deep neural network entirely from scratch.

### 8. Recurrent Neural Networks

RNN-based practicals explore sequential data.

Applications include:

* Stock market prediction
* Natural language processing
* Slot filling
* Sequence labeling

These demonstrate how recurrent architectures can process information where the order of data is important.

### 9. Fraud Detection

Deep learning is applied to credit card fraud detection, demonstrating the use of neural networks for identifying potentially fraudulent transactions.

### 10. Convolutional Autoencoders

The convolutional autoencoder practical explores:

* Encoder-decoder architecture
* Image compression
* Feature extraction
* Representation learning
* Image reconstruction

### 11. Generative Adversarial Networks

The final practical implements a GAN consisting of:

**Generator → creates synthetic images**

**Discriminator → distinguishes real images from generated images**

The implementation uses the MNIST handwritten digit dataset and demonstrates the complete GAN training process and generation of new synthetic digits.

---

## 🛠️ Technologies Used

* **Python**
* **Jupyter Notebook**
* **Google Colab**
* **NumPy**
* **Pandas**
* **Matplotlib**
* **Seaborn**
* **Scikit-learn**
* **TensorFlow**
* **Keras**

---

## 📂 Repository Structure

```text
Deep-Learning/
│
├── Practical1-linear_regression_error_metrics.ipynb
├── Practical2-Housing_Price_Prediction_DFFN.ipynb
├── Practical3-Breast-Cancer-Classification.ipynb
├── Practical4_Regularization_Techniques.ipynb
├── Practical5_Hyperparameter_Tuning_&_Model_Optimization_.ipynb
├── Practical6_Handwritten_Digit_Recognition.ipynb
├── Practical7_Dog_Breed_Classification_using_TransferLearning.ipynb
├── Practical8_StockMarket_Prediction_using_Recurrent_Neural_Networks.ipynb
├── Practical9_Slot_Filling_using_Recurrent_Neural_Networks.ipynb
├── Practical10_Credit_Card_Fraud_Detection_using_Deep_Learning.ipynb
├── Practical11_Convolutional_Autoencoder.ipynb
├── Practical12_Generative_Adversarial_Network.ipynb
│
└── README.md
```

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Aarya0310/Deep-Learning.git
```

### 2. Navigate to the Repository

```bash
cd Deep-Learning
```

### 3. Install Dependencies

```bash
pip install numpy pandas matplotlib seaborn scikit-learn tensorflow jupyter
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open any practical notebook and execute the cells sequentially.

---

## ☁️ Running on Google Colab

Most notebooks can also be executed using **Google Colab**, which is particularly useful for deep learning practicals that require additional computational resources.

### Steps

1. Open the required `.ipynb` file from the repository.
2. Open it in Google Colab.
3. Select the appropriate runtime.
4. Install any missing dependencies if required.
5. Run the notebook cells sequentially.

---

## 📊 Learning Outcomes

After completing these practicals, the learner gains hands-on experience with:

* Building and evaluating machine learning models
* Designing neural network architectures
* Performing data preprocessing
* Handling classification and regression problems
* Preventing overfitting using regularization
* Optimizing neural network hyperparameters
* Working with image data
* Applying CNNs to computer vision problems
* Using transfer learning
* Processing sequential and time-series data
* Applying RNNs to NLP tasks
* Building autoencoders
* Understanding generative models
* Implementing GANs for synthetic data generation

---

## 🎯 Applications

The techniques implemented in this repository have applications across multiple domains:

| Domain                         | Example                       |
| ------------------------------ | ----------------------------- |
| 🏠 Real Estate                 | Housing Price Prediction      |
| 🏥 Healthcare                  | Breast Cancer Classification  |
| 👁️ Computer Vision            | Digit & Dog Breed Recognition |
| 📈 Finance                     | Stock Market Prediction       |
| 💳 Financial Security          | Credit Card Fraud Detection   |
| 💬 Natural Language Processing | Slot Filling                  |
| 🖼️ Representation Learning    | Convolutional Autoencoder     |
| 🤖 Generative AI               | GAN-based Image Generation    |

---

## 👨‍💻 Author

**Aarya Bhende**

---

⭐ If you find this repository useful for learning Deep Learning concepts, consider starring the repository.
