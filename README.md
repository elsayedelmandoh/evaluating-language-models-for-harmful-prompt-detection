# Capstone: Evaluating Language Models for Harmful Prompt Detection

## Table of Contents
- [Project Overview](#project-overview)
- [Objectives](#objectives)
- [Setup](#setup)
- [Data Acquisition](#data-acquisition)
- [Data Analysis](#data-analysis)
- [Model Implementation](#model-implementation)
- [Performance Comparison](#performance-comparison)
- [Results](#results)
- [Visualizations](#visualizations)
- [Contributing](#contributing)
- [Author](#author)

## Project Overview
This project focuses on evaluating and comparing the effectiveness of different language models in detecting harmful prompts. Using the LLM-EvaluationHub dataset, the project implements at least two language models, performs data visualization, and assesses which model is best at identifying harmful content.

## Objectives
- **Data Analysis**: Conduct exploratory analysis and visualization of the dataset.
- **Model Implementation**: Evaluate a minimum of two language models for harmful prompt detection.
- **Performance Comparison**: Compare models based on accuracy and effectiveness in identifying harmful prompts.

## Setup
To get started, install the necessary packages using the following commands:
```bash
pip install langchain
pip install --upgrade --quiet langchain-google-genai pillow
pip install -qU langchain-anthropic
```

## Data Acquisition
The dataset used for evaluation is available on [Kaggle](https://www.kaggle.com/datasets/strikoder/llm-evaluationhub/data). The LLM-EvaluationHub dataset includes prompts annotated for ethical concerns such as offensiveness, fairness, and biases.

## Data Analysis
The data analysis involves exploring and visualizing the dataset to understand the distribution of different ethical categories and labels. Visualizations include bar charts and heatmaps that illustrate the relationship between ethical categories and correct labels.

## Model Implementation
The project utilizes language models from Google and Anthropic. The `ChatGoogleGenerativeAI` and `ChatAnthropic` libraries are used to implement and test these models. The models are evaluated based on their ability to accurately classify prompts as harmful or not.

## Performance Comparison
The performance of the language models is assessed by comparing their accuracy in detecting harmful prompts. The results are compiled into a DataFrame and analyzed to determine the best-performing model.

## Results
The results of the model evaluations, including accuracy metrics for each model, are saved to a CSV file for further analysis.

## Visualizations
Visualization of model accuracy comparisons is provided through bar charts, showing the effectiveness of each language model in detecting harmful prompts.

## Contributing
Contributions are welcome! If you have suggestions, improvements, or additional content to contribute, feel free to open issues, submit pull requests, or provide feedback.

[![GitHub watchers](https://img.shields.io/github/watchers/elsayedelmandoh/evaluating-language-models-for-harmful-prompt-detection.svg?style=social&label=Watch)](https://GitHub.com/elsayedelmandoh/evaluating-language-models-for-harmful-prompt-detection/watchers/?WT.mc_id=academic-105485-koreyst)
[![GitHub forks](https://img.shields.io/github/forks/elsayedelmandoh/evaluating-language-models-for-harmful-prompt-detection.svg?style=social&label=Fork)](https://GitHub.com/elsayedelmandoh/evaluating-language-models-for-harmful-prompt-detection/network/?WT.mc_id=academic-105485-koreyst)
[![GitHub stars](https://img.shields.io/github/stars/elsayedelmandoh/evaluating-language-models-for-harmful-prompt-detection.svg?style=social&label=Star)](https://GitHub.com/elsayedelmandoh/evaluating-language-models-for-harmful-prompt-detection/stargazers/?WT.mc_id=academic-105485-koreyst)

## Author
This repository is maintained by Elsayed Elmandoh, an AI Engineer. You can connect with Elsayed on [LinkedIn and Twitter/X](https://linktr.ee/elsayedelmandoh) for updates and discussions related to Machine Learning, Deep Learning, and NLP.

Happy coding!
