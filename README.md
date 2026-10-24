
# AI Text Summarizer Using Hugging Face Pipelines

## Demo link : https://textsummarization-gqxcem7iasmeujdruymsls.streamlit.app/

## Project Overview


The AI Text Summarizer is a Python-based web application that converts long text into shorter summaries using a pre-trained Natural Language Processing model from Hugging Face.

<img width="1364" height="637" alt="image" src="https://github.com/user-attachments/assets/e4ffcc0e-7173-4353-9f78-db5c3ccb7580" />


## Objective

To demonstrate text summarization using the Hugging Face Transformers pipeline.

## Technologies Used

- Python
- Hugging Face Transformers
- DistilBART CNN model
- Streamlit
- PyTorch

## Features

- Summarizes long paragraphs and articles
- Adjustable minimum and maximum summary lengths
- Displays original and summary word counts
- Calculates text reduction percentage
- Allows users to download the generated summary
- Provides error handling

<img width="1365" height="622" alt="image" src="https://github.com/user-attachments/assets/e005e715-3506-4920-a275-f6fc43d95f90" />


## Installation

Install the required libraries:

    python -m pip install -r requirements.txt

## Run the Application

    python -m streamlit run app.py

## How It Works

1. The user enters a long text.
2. The Hugging Face summarization pipeline processes the input.
3. The pre-trained DistilBART model generates a shorter summary.
4. The application displays the summary and text statistics.
5. The user can download the summary as a text file.

## Conclusion

This project demonstrates how Hugging Face Pipelines simplify the implementation of Natural Language Processing tasks. It provides an easy way to summarize long text and understand the practical use of pre-trained AI models.
