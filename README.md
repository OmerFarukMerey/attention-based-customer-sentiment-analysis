# Attention-Based Customer Sentiment Analysis

Sentiment classification of customer service conversations using transformer-based models. The model classifies interactions into **positive**, **negative**, or **neutral** sentiment.

## Overview

This project fine-tunes an attention-based (transformer) network to analyze customer-support dialogues and predict sentiment. It includes exploratory data analysis, data preprocessing, model training, evaluation, and experiment tracking.

## Project Structure

```
├── dataset/            # Train and test datasets
├── EDA/                # Exploratory data analysis
├── preprocess/         # Data preprocessing scripts
├── train/              # Model training code
├── test/               # Evaluation on test set
├── reports/            # Results and reports
```

## Dataset

Customer service interactions where customers describe their issues and support agents respond. Split into `train.csv` (training & validation) and `test.csv` (held out strictly for evaluation). Three sentiment classes: positive, negative, neutral.

## Approach

1. **Exploratory Data Analysis** - Class distribution, feature correlations, text statistics
2. **Preprocessing** - Text cleaning, tokenization, train/validation split
3. **Modeling** - Fine-tuning a pre-trained transformer for 3-class sentiment classification
4. **Evaluation** - Performance measured with appropriate classification metrics
5. **Experiment Tracking** - All runs logged via [Weights & Biases](https://wandb.ai)

## Tools & Technologies

- Python, PyTorch, Hugging Face Transformers
- Weights & Biases (W&B) for experiment tracking
- Jupyter Notebook

## Deliverables

- **Report:** IEEE format, 2-page PDF
- **Code:** Interactive notebooks (`.ipynb`) with outputs
- **Version Control:** [GitHub Repository](https://github.com/OmerFarukMerey/attention-based-customer-sentiment-analysis)
- **Experiment Tracking:** [W&B Dashboard](https://wandb.ai/team-lingua/customer-sentiment-analysis)
