# News Text Summarizer using Machine Learning

## Project Overview

This project focuses on building a News Text Summarizer using Machine Learning techniques. The summarizer is trained on the CNN/Dailymail News dataset, which can be found [here](https://huggingface.co/datasets/cnn_dailymail). The dataset is preprocessed using various techniques to enhance the quality of the input data.

## Dataset Information

- **Dataset Used:** CNN/Dailymail News
- **Dataset Link:** [Hugging Face - CNN/Dailymail News](https://huggingface.co/datasets/cnn_dailymail)

## Data Preprocessing Techniques

The dataset undergoes several preprocessing steps to ensure optimal performance during training. The following techniques are applied:

1. **Removing Missing Rows:** Any rows with missing data are removed to ensure data integrity.
2. **Character Removing:** Unnecessary characters are removed from the text to clean the dataset.
3. **Tokenization:** The text is tokenized into individual words or subwords for further processing.
4. **Stop Word Removal:** Common stop words are removed to focus on meaningful content.
5. **Stemming:** Reducing words to their root form to simplify the vocabulary.
6. **Lemmatization:** Similar to stemming but considers the context to transform words to their base or dictionary form.

## Dataset Split

The dataset is split into three sets for training, testing, and validation purposes:

- **Training Set:** 80%
- **Testing Set:** 10%
- **Validation Set:** 10%

## Model Architecture

The model is implemented using a Seq2Seq architecture with an attention mechanism. The architecture consists of an encoder and a decoder, providing an effective approach to generate concise and coherent summaries for news articles.

Feel free to explore the codebase for more details and customization.

## License

This project is licensed under the [MIT License](LICENSE).
