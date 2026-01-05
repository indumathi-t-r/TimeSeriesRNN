# Time Series Forecasting using RNN (PyTorch)

This repository contains a **time-series forecasting project using Recurrent Neural Networks (RNNs)** implemented in PyTorch. The project focuses on learning temporal patterns from sequential data and predicting future values, aligning with practical applications such as trend analysis, anomaly anticipation, and sequence modeling.

## Project Structure
The project follows a notebook-driven structure:
- A single Jupyter Notebook that includes data loading, preprocessing, model definition, training, and evaluation.
- All experiments, visualizations, and results are contained within the notebook.
- The workflow is designed to clearly demonstrate end-to-end time-series modeling using RNN-based architectures.

## What’s happening in the script
- The time-series data is loaded and normalized for stable training.
- Sequences are created using sliding windows to capture temporal dependencies.
- An RNN-based model (Simple RNN / LSTM / GRU as implemented in the notebook) is defined using PyTorch.
- The model learns temporal patterns by processing sequences step by step.
- Predictions are generated for future time steps based on learned representations.
- Model performance is evaluated using loss metrics and visual comparison between actual and predicted values.

## Script contains
- Time-series data preprocessing and normalization
- Sequence and window generation
- RNN-based model implementation in PyTorch
- Training and validation loops
- Forecasting and result visualization

## Portfolio Alignment
This project demonstrates:
- Practical understanding of **sequence modeling and temporal data**
- Hands-on experience with **RNN-based deep learning architectures**
- Ability to build **end-to-end forecasting pipelines** in PyTorch
- Application of deep learning concepts to real-world time-series problems

## Requirements
Python 3.9+

Main libraries used:
- numpy
- pandas
- matplotlib
- scikit-learn
- torch
