# Thesis-Data---XAI-Brain-Tumor-Detection
Toward Transparent AI Solutions for Brain Tumor Diagnosis in Medical Imaging

Brain Tumor Classification using InceptionV3 

This project presents a deep learning-based solution for the classification of brain tumors using MRI scans. It uses transfer learning with InceptionV3, combined with explainable AI (XAI) techniques like Grad-CAM, and deploys the final model in a web interface using Streamlit.

Project Overview

Objective: Automatically classify brain tumors (Glioma, Meningioma, Pituitary, No Tumor) from MRI images to support medical diagnostics.

Model Used: Pretrained InceptionV3 with fine-tuned classification layers.

Final Accuracy: 98.52% on the test set

Explainability: Implemented using Grad-CAM

Deployment: Built with Streamlit and tested via Ngrok



Features
CNN Transfer Learning with InceptionV3

Fine-tuning with data augmentation and learning rate scheduling

Grid search for hyperparameter optimization

Model evaluation: classification report, confusion matrix, ROC curves

Grad-CAM visualizations for model interpretability

Deployed in Streamlit interface for real-time predictions

