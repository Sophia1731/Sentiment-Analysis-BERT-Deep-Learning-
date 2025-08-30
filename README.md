# Sentiment Analysis Using BERT with Deep Learning


Sentiment Analysis Using BERT Project Overview:

This project fine-tunes a pre-trained BERT model for a sentiment analysis task, classifying text into the following categories: 
angry, disgust, happy, not-relevant, sad, and surprise. 
It follows a standard deep learning pipeline using PyTorch and the transformers library.

The notebook follows a clear, step-by-step process to perform the sentiment analysis:

    Data Analysis: Initial data exploration and cleaning. We find that there is a clear imbaance in the data set.

    Data Split: Dividing data into training and validation sets using a stratified approach to ensure that each class had some representation in each resulting set.

    Tokenization: Encoding text for the BERT model.

    Model Setup: Configuring the BERT model and adding a classification head.

    Data Loaders: Preparing data for efficient batch processing

    Training Prep: Setting up the optimizer and learning rate scheduler.

    Metrics: Defining performance metrics like F1-score.

    Training: The main loop for fine-tuning the model.

    Evaluation: Loading the final model and measuring its performance.

Files:

    Project.ipynb
    
    *finetuned_bert_epoch_1_gpu_trained.model: The saved BERT model file

*BERT Model File
Due to its large size, the pre-trained BERT model file used in this analysis is not included in this repository.

You can download the .model file directly from my Hugging Face account at the following link:

(https://huggingface.co/Sophia1731/bert-sentiment-analysis/tree/main)

After downloading, please place the file in the designated project directory as specified in the analysis script.


