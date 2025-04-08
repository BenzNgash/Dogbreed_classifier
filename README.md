🐶 End-to-End Multi-Class Dog Breed Classification
This project builds a complete end-to-end deep learning pipeline to classify dog breeds from images using TensorFlow 2.0 and TensorFlow Hub. The model leverages transfer learning to recognize 120 different dog breeds with high accuracy.

📌 Problem Statement
“When I'm sitting at a cafe and I take a photo of a dog, I want to know what breed of dog it is.”

Given an image of a dog, the goal is to accurately predict its breed out of 120 possible categories.

📊 Dataset
Source: Kaggle - Dog Breed Identification

The dataset consists of over 10,000 labeled images in the training set and 10,000+ unlabeled images in the test set.

Each image corresponds to one of 120 dog breeds.

🧠 Approach
Deep Learning / Transfer Learning using TensorFlow and pretrained models from TensorFlow Hub.

End-to-end pipeline: Data loading → Preprocessing → Model building → Training → Evaluation → Prediction.

Built with scalability and experimentation in mind.

🧪 Evaluation
Submission requires a CSV file with probability scores for each of the 120 breeds per test image.

Evaluation metric: Multi-class log loss as per Kaggle Evaluation Page.

🚀 Features
✅ End-to-end model training and inference workflow

✅ Utilizes transfer learning for efficient training

✅ Supports inference on unlabeled test images

✅ Outputs ready-to-submit prediction file for Kaggle

🛠️ Tools & Libraries
Python

TensorFlow 2.x

TensorFlow Hub

Pandas, NumPy, Matplotlib

Google Colab (or local GPU)
