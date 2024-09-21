# Fine-Tuning and Evaluation of Meta Llama 2 7B Model

This repository contains two Jupyter notebooks that guide you through the process of fine-tuning and evaluating the **Meta Llama 2 7B large language model** using **Amazon SageMaker** and other relevant tools. The notebooks are designed for those interested in enhancing the text generation capabilities of large language models (LLMs) for specific domains by leveraging **transfer learning**.

## Project Overview

- **Model_FineTuning.ipynb**: This notebook walks through the steps to fine-tune the pre-trained Llama 2 7B model on a domain-specific dataset. It includes the process of:
  - Installing and setting up necessary libraries like SageMaker and Datasets.
  - Selecting and configuring the appropriate dataset for fine-tuning.
  - Fine-tuning the Llama 2 7B model to adapt to your chosen domain's specific data.
  - Deploying the fine-tuned model for inference and text generation.

- **Model_Evaluation_UdacityGenAIAWS.ipynb**: This notebook covers the deployment and evaluation of the fine-tuned model. It demonstrates:
  - Setting up the environment for model deployment.
  - Evaluating the text generation and domain knowledge capabilities of the Llama 2 7B model.
  - Comparing the model's performance based on text inputs and expected outputs.

## Key Features
- **Transfer Learning**: Fine-tune a pre-trained large language model on domain-specific datasets to improve performance in specialized areas.
- **Text Generation**: Evaluate the model's ability to predict and generate sequences of text based on given inputs.
- **Amazon SageMaker**: Leverage SageMaker's powerful infrastructure to fine-tune and deploy models.

## Prerequisites
- **Amazon SageMaker**: Both notebooks make use of SageMaker's functionality to deploy and fine-tune models.
- **Datasets**: Ensure you have a domain-specific dataset in CSV, JSON, or TXT format with a column named `text` (or the first column if `text` is not available).
- **Libraries**: Install the necessary libraries such as `sagemaker` and `datasets`. The required installation commands are included in the notebooks.

## Setup Instructions
1. Clone this repository.
   ```bash
   git clone https://github.com/your-repo/fine-tuning-llama2.git
   cd fine-tuning-llama2
2. Ensure you have the required AWS services set up and configured, including SageMaker.
3. Open the Model_FineTuning.ipynb notebook and follow the instructions to fine-tune the model.
4. After fine-tuning, switch to the Model_Evaluation_UdacityGenAIAWS.ipynb notebook for deploying and evaluating the fine-tuned model.

## Usage
1. Fine-tune the Llama 2 7B model using your dataset.
2. Deploy the model for real-time inference using SageMaker.
3. Evaluate the model's text generation capabilities using the provided evaluation notebook.