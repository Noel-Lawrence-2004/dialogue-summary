# Dialogue Summarization using PEGASUS Fine-Tuning

This project focuses on summarizing dialogues by fine-tuning the PEGASUS model using the SamSum dataset. The goal is to generate concise and coherent summaries from dialogue inputs, leveraging the power of the state-of-the-art PEGASUS model for abstractive text summarization.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Model](#model)
- [Setup](#setup)
- [Training](#training)
- [Evaluation](#evaluation)
- [Results](#results)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Summarizing dialogues is a challenging task due to the informal and often unstructured nature of conversational data. This project aims to address this by fine-tuning PEGASUS, a transformer-based model designed for abstractive summarization, on the SamSum dataset which contains dialogues and their corresponding summaries.

## Dataset

The [SamSum dataset](https://arxiv.org/abs/1911.12237) is a collection of dialogues written by linguists who created conversations similar to those we have in daily life. Each dialogue in the dataset comes with a human-written summary.

## Model

[PEGASUS](https://arxiv.org/abs/1912.08777) (Pre-training with Extracted Gap-sentences for Abstractive Summarization Sequence-to-sequence) is a model by Google Research designed for abstractive summarization. It is pre-trained on a large corpus of news articles, and in this project, it is fine-tuned on the SamSum dataset for the specific task of dialogue summarization.

## Setup

### Prerequisites

- Python 3.7 or higher
- PyTorch
- Transformers library by Hugging Face
- Datasets library by Hugging Face
- ROUGE metric library for evaluation

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/Noel-Lawrence-2004/dialogue-summary.git
    cd dialogue-summarization-pegasus
    ```

2. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

## Training

To fine-tune the PEGASUS model on the SamSum dataset, follow the steps in the jupyter notebook :
