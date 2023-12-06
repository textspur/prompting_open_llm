# Overview

This repository contains two Jupyter Notebook files that demonstrate the use of the Zephyr-7b-alpha model from Hugging Face for text classification tasks.

## Files in this Repository

- **Example_FirstStep_zephyr-7b-alpha.ipynb**: A beginner-friendly guide to getting started with the Zephyr-7b-alpha model.
- **Example_tweets_sentiment_zephyr-7b-alpha.ipynb**: An advanced example showcasing more complex uses of the model, including sentiment analysis on tweets, optimized for Google Colab's A100 GPU.

### Example_FirstStep_zephyr-7b-alpha.ipynb

#### Steps Covered

- **Installation**: Instructions to install necessary libraries (`transformers` and `accelerate`) from Hugging Face.
- **Load Dependencies**: Importing `torch` and the pipeline from `transformers`.
- **Model Loading**: Initializing the text generation pipeline with the Zephyr-7b-alpha model.
- **First Prompt Setup**: Demonstrates how to set up a prompt for text generation, including defining roles (system, user, assistant) for the interaction.
- **Response Generation**: Shows how to generate a response from the model based on the provided prompt.
- **Functions for Text Classification**: Includes functions for zero-shot and one-shot text classification, demonstrating the versatility of the model.
- **Example Runs**: Provides example runs for both zero-shot and few-shot text classification using the model.

### Example_tweets_sentiment_zephyr-7b-alpha.ipynb

This notebook delves deeper into using the Zephyr-7b-alpha model for sentiment analysis of tweets. It is optimized for Google Colab's A100 GPU.
