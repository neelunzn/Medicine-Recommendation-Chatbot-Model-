# Medicine Recommendation System

A comprehensive machine learning and deep learning system for medical symptom analysis and medicine recommendation, featuring a hybrid CNN+Bidirectional LSTM model and fine-tuned 
ClinicalBERT. 

# Overview

This project implements an intelligent medicine recommendation system that analyzes patient symptoms and provides accurate disease predictions along with corresponding treatment recommendations. The system combines traditional machine learning models with advanced deep learning architectures for optimal performance.

# Features

 - Multi-Model Approach: Utilizes both traditional ML models (Random Forest, XGBoost) and deep learning models (CNN + BiLSTM, BERT)
 - Comprehensive Medical Knowledge Base: Integrates information from multiple medical datasets including symptoms, medications, diets, and precautions
 - Data Augmentation: Implements sophisticated data augmentation techniques to improve model generalization
 - Confidence-based Predictions: Provides predictions with confidence scores and fallback recommendations for low-confidence cases
 - Interactive Q&A System: Generates natural language questions and answers for medical consultations

# Dataset

The system uses multiple medical datasets:
 - Symptom severity data
 - Disease training data with symptom mappings
 - Disease descriptions and medications
 - Diet recommendations and precautions
 - Workout suggestions for various conditions

# Model Architecture

## Hybrid CNN + Bidirectional LSTM
 - Combines convolutional layers for feature extraction with bidirectional LSTM for sequence modeling
 - Captures both local patterns and long-term dependencies in symptom data

## Fine-tuned ClinicalBERT
 - Transformer architecture for understanding complex medical text
 - Fine-tuned on medical Q&A pairs for accurate symptom interpretation

## Traditional ML Models
 - Random Forest, XGBoost, LightGBM, and other classifiers
 - 10-fold cross-validation for robust performance evaluation

Here is the Kaggle notebook of it- 
  https://www.kaggle.com/code/sagorahmedmunna/chatbotv26
