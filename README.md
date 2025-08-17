# Sentiment Analysis Using BERT with Deep Learning


Sentiment Analysis Using BERT Project Overview:

This project fine-tunes a pre-trained BERT model for a sentiment analysis task, classifying text into the following categories: 
angry, disgust, happy, not-relevant, sad, and surprise. 
It follows a standard deep learning pipeline using PyTorch and the transformers library.

The notebook follows a clear, step-by-step process to perform the sentiment analysis:

    Data Analysis: Initial data exploration and cleaning.

    Data Split: Dividing data into training and validation sets.

    Tokenization: Encoding text for the BERT model.

    Model Setup: Configuring the BERT model and adding a classification head.

    Data Loaders: Preparing data for efficient batch processing

    Training Prep: Setting up the optimizer and learning rate scheduler.

    Metrics: Defining performance metrics like F1-score.

    Training: The main loop for fine-tuning the model.

    Evaluation: Loading the final model and measuring its performance.

Files:

    Project.ipynb
    
    finetuned_bert_epoch_1_gpu_trained.model: The saved BERT model file
