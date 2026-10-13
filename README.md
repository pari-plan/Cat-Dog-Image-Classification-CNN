# 🐱 Cat vs Dog Image Classification Using CNN

A Deep Learning project that classifies images into two categories: **Cat** or **Dog**, using a Convolutional Neural Network (CNN) built with TensorFlow and Keras.

## 📌 Project Overview

The aim of this project is to develop an image classification system that can identify whether an uploaded image contains a cat or a dog. The model learns visual patterns from labeled images and uses those patterns to make predictions on new images.

The project is implemented in Python using Google Colab, making it suitable for beginners learning deep learning and computer vision.

## 🎯 Objectives

- Understand the basic concepts of deep learning and CNNs.
- Prepare and process image datasets.
- Train a CNN model for binary image classification.
- Evaluate the model using validation accuracy and loss.
- Predict whether a new image contains a cat or a dog.

## 🛠️ Technologies Used

- **Python**
- **TensorFlow**
- **Keras**
- **NumPy**
- **Matplotlib**
- **Pillow (PIL)**
- **Google Colab**

## 📂 Dataset

This project uses the Cats vs Dogs image dataset. Images are organized into two categories: Cat and Dog.

For faster training, a smaller subset of valid images is used. Images are resized to **128 × 128 pixels** and divided into training and validation sets using an 80:20 split.


## ⚙️ Project Workflow

1. Download and extract the dataset.
2. Check image files and prepare the dataset.
3. Resize and load images.
4. Split images into training and validation sets.
5. Build the CNN model.
6. Train and evaluate the model.
7. Display training accuracy and loss graphs.
8. Upload a new image and predict its class.

## 🚀 How to Run the Project

1. Open the notebook in Google Colab.
2. Run each code cell in order.
3. Wait for the dataset to download and prepare.
4. Train the CNN model.
5. Run the evaluation cell to view validation results.
6. Upload a cat or dog image to test the model.

## 📊 Results

- **Validation Accuracy:** Add the actual accuracy displayed by your notebook.
- **Validation Loss:** Add the actual loss displayed by your notebook.
- **Image Prediction:** The model predicts whether an uploaded image belongs to the Cat or Dog class.

*Note: Actual performance depends on the training data, training duration, and input image.*

## ⚠️ Limitations

- The model supports only two categories: cats and dogs.
- Training uses a limited subset of images.
- Poor lighting, unusual poses, or complex backgrounds may affect predictions.
- The model may make incorrect predictions on unfamiliar images.

## 🔮 Future Improvements

- Train using a larger dataset.
- Apply data augmentation.
- Improve accuracy by tuning model parameters.
- Use transfer learning with a pretrained CNN.
- Deploy the model through a simple web application.

## 🎓 Conclusion

This project demonstrates the application of deep learning and CNNs to image classification. It provides practical experience in image preprocessing, model training, evaluation, and prediction using TensorFlow and Keras.

## 📚 References

- [Keras Image Classification Tutorial](https://keras.io/examples/vision/image_classification_from_scratch/)
- [TensorFlow Documentation](https://www.tensorflow.org/)
- [Google Colab](https://colab.research.google.com/)

## 👩‍💻 Author

**Pari Rajput**  
BTech Computer Science Engineering  
COER University
