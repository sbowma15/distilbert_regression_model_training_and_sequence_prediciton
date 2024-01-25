# distilbert_regression_model_training_and_sequence_prediciton

This Python script is designed for training a regression model using the DistilBERT model from the Hugging Face Transformers library. The model is fine-tuned on a dataset containing text excerpts and corresponding target values.

## Prerequisites

Ensure you have the required libraries installed. You can install them using the following:

```bash
pip install transformers pandas matplotlib numpy nltk seaborn sklearn gensim pyldavis wordcloud textblob spacy textstat

# Configuration

Adjust the following parameters in the script based on your requirements:

MAX_LENGTH: Maximum length of tokenized excerpts.
BATCH_SIZE: Batch size for training.
train_file: Path to the CSV file containing training data.
EPOCHS: Number of training epochs.

# Results

The script outputs training and validation Mean Squared Error (MSE) for model evaluation. Additionally, visualizations are generated to help analyze training and validation losses.
