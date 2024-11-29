# AI-Generated Text Detection Using BERT and TensorFlow

## Overview
This project focuses on distinguishing between human-written and AI-generated text using advanced natural language processing (NLP) techniques. With the rapid advancement of AI, identifying the origin of textual content has become increasingly challenging. The model leverages BERT embeddings and TensorFlow to classify the text accurately, contributing to the development of robust AI content detection tools.

---

## Problem Statement
With the rise of AI-generated content, distinguishing between human-written and AI-generated text is crucial for maintaining trust, accountability, and quality in various domains. This project aims to accurately identify whether a given text is human-written or AI-generated, providing a foundation for detecting synthetic content.

---

## Features
- **Preprocessing**: Text cleaning, symbol removal, and format standardization to ensure high-quality input data.
- **BERT Embeddings**: Contextualized word embeddings to capture sentence-level meaning and subtle distinctions in the text.
- **Model Training**: Developed using TensorFlow and Keras with hyperparameter tuning for optimal performance.
- **Evaluation**: Achieved a macro F1 score of 0.88 on test data, showcasing balanced performance on precision and recall.

---

## Key Highlights
- **Input**: Article text.
- **Output**: Binary classification (1 = AI-generated, 0 = Human-written).
- **Tools**: Python, TensorFlow, Keras, BERT, Pandas, Scikit-learn.


---

## Model Architecture
- **BERT Embeddings**: Extracted using a pre-trained BERT model to capture semantic and contextual nuances.
- **Fully Connected Layers**: Fine-tuned for binary classification with dropout for regularization.
- **Loss Function**: Binary cross-entropy.
- **Optimizer**: Adam with learning rate scheduling.

---

## Results
- **Macro F1 Score**: 0.88
- **Precision and Recall**: Balanced to ensure reliable classification of both classes.
- **Performance**: Successfully handled imbalanced datasets through threshold tuning and careful evaluation metrics.

---

## Lessons Learned
- The importance of preprocessing and data cleaning in improving model quality.
- How contextual embeddings like BERT significantly enhance performance for nuanced tasks.
- Strategies for hyperparameter tuning and managing class imbalances.

---

## Future Improvements
- Incorporate additional datasets for broader generalization.
- Experiment with ensemble methods or transformer-based fine-tuning.
- Deploy the model using a Flask or FastAPI interface for real-time predictions.

---

## Contribution
Feel free to fork this repository and submit pull requests. Feedback and suggestions are welcome to improve the project further.

---

---

## Acknowledgments
- Pre-trained BERT model from Hugging Face.
- TensorFlow and Keras for model development.
- Contributors and reviewers for their valuable insights.
