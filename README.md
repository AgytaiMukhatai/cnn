Emotion Detection from Facial Expressions Using Deep Learning
#Abstract
This report investigates applying deep learning techniques for emotion detection from facial expressions. The project involved building and evaluating three different convolutional neural network (CNN) architectures: a simple CNN, a ResNet, and a VGG-like model. The models were trained on the FER-2013 dataset, a widely used benchmark dataset for facial expression recognition. The performance of each model was evaluated using metrics like accuracy, precision, recall, and F1-score. The results demonstrate the effectiveness of deep learning for emotion detection, with the ResNet model achieving the highest overall accuracy.
#1. Introduction
Emotion detection from facial expressions is a significant area of research in computer vision and artificial intelligence. It has applications in human-computer interaction, healthcare, marketing, and security. Deep learning, particularly CNNs, has emerged as a powerful tool for this task, enabling automatic feature extraction and classification.
This project focuses on developing and evaluating three CNN architectures for emotion detection using the FER-2013 dataset. The dataset contains images of human faces displaying six basic emotions: neutral, happy, sad, surprised, fearful, and angry. The goal is to compare the performance of the three models and identify the most effective approach.
#2. Dataset and Preprocessing
Dataset: The FER-2013 dataset was downloaded using the kagglehub library. It contains a 'train' and a 'test' folder, each with subfolders for the six emotion categories.

