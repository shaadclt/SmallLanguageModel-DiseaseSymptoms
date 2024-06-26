# Medical Symptom Prediction using GPT-2
This project utilizes the power of language models, specifically the GPT-2 model, to predict medical symptoms based on input text. By fine-tuning the GPT-2 model on a dataset containing disease names and associated symptoms, we train a language model to generate probable symptoms for a given disease.

## Introduction
In the medical field, identifying symptoms associated with different diseases is crucial for diagnosis and treatment planning. This project aims to automate this process by leveraging natural language processing techniques. By training a GPT-2 model on a dataset of diseases and symptoms, we enable the model to generate likely symptoms for a given disease query.

## Installation
To run this project, you'll need to install the necessary dependencies. You can do this via pip:

```bash
!pip install torch torchtext transformers sentencepiece pandas tqdm datasets
```

Additionally, ensure you have the required packages installed by running the provided code snippets in the README.

## Usage
1. Load the dataset containing diseases and symptoms.
2. Fine-tune the GPT-2 model on the dataset using the provided code.
3. Train the model and evaluate its performance.
4. Utilize the trained model to generate symptom predictions for given disease queries.
   
For detailed usage instructions, refer to the provided code and comments.

## Results
After training the model, we achieve promising results in predicting symptoms for various diseases. The validation loss and training loss metrics are recorded for each epoch during training. Additionally, we provide a sample prediction generated by the trained model for a given disease query.

## Contributing
Contributions are welcome! If you'd like to contribute to this project, feel free to submit pull requests or open issues on GitHub. Your feedback and contributions help improve the project for everyone.
