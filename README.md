# LLM-MultiSource-QA
This repository contains the code, dataset, and findings from our research on evaluating and improving Large Language Models (LLMs) for multi-source question-answering tasks. We explore various prompting strategies, custom evaluation metrics, and advanced techniques such as few-shot learning and chain of thought to enhance model performance.


## Prerequisites

- Python 3.6 or higher
- OpenAI Python client library
- Update the script with your OpenAi API key
    OPENAI_API_KEY = 'your key'
- Dataset are saved into the "data" folder
- results from models are saved into the "results" folder

## Code Structure
The code is divided into four main parts:

1. Loading the Dataset
This part of the code is responsible for reading the JSON file containing the dataset.
2. Running the Models on Different Prompts
This part uses openAI models on different prompts to evaluate the capabilities of each model on this task where we ask the model to answer questions based on sources.
3. Metric Calculator
This section calculates various metrics (such as similarity, F1 score, ROUGE-L score, and BERT score) to evaluate the quality of the model's answers.
4. Plots
This part generates plots to visualize the results. It creates histograms and other charts to display the performance of the model based on different metrics.
