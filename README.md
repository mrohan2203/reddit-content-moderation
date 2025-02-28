# reddit-content-moderation
Text classification using NLP and XGBoost for content moderation.

A machine learning project that applies NLP techniques to classify text content using TF-IDF embeddings and XGBoost, handling class imbalance effectively.

## Dataset
Uses a dataset containing text samples with labels indicating whether content was moderated (REMOVED or not).
Preprocessed using feature selection, handling missing values, and balancing classes.

## Model and Techniques Used
	•	TF-IDF Vectorization for text feature extraction
	•	XGBoost Classifier with hyperparameter tuning
	•	Class Imbalance Handling using scale_pos_weight
	•	Evaluation Metrics: Precision, Recall, F1-score


