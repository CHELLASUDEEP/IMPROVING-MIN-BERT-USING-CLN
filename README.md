# NLP Dataset Preparation and Modeling

This Jupyter Notebook provides code for processing NLP datasets and preparing them for classification tasks using Hugging Face's Transformers library. It includes functionality for loading datasets, analyzing class distributions, and balancing data for effective model training.

## Features

- **Dataset Loading**: Automatically fetches popular NLP datasets such as:
  - SST2 (Sentiment Analysis)
  - Quora (Duplicate Question Detection)
  - STSb (Semantic Textual Similarity)
- **Class Analysis**: Visualizes the distribution of different classes in datasets.
- **Data Balancing**: Implements a utility function to downsample datasets and balance classes for fair model training.

## Requirements

The following Python libraries are required:

- `transformers`
- `torch`
- `datasets`

You can install them using pip:

```bash
pip install transformers torch datasets
```

## Notebook Structure

1. **Setup**: Installs dependencies and imports necessary modules.
2. **Dataset Loading**: Loads datasets from the Hugging Face hub.
3. **Class Distribution Analysis**: Displays the count of examples for each class.
4. **Data Balancing**: Contains a reusable function for balancing datasets.

## Usage

1. Open the notebook in Jupyter or JupyterLab.
2. Execute the cells sequentially to load and preprocess the datasets.
3. Customize the `downsample_balanced` function if specific dataset configurations are required.
4. Use the processed datasets for further modeling tasks.

## Dataset Sources

- SST: Sentiment analysis dataset from the GLUE benchmark.
- Quora: Dataset for identifying duplicate questions.
- STS: Semantic Textual Similarity dataset from GLUE.

