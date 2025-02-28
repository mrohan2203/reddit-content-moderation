# reddit-content-moderation
Text classification using NLP and XGBoost for content moderation.

A machine learning project that applies NLP techniques to classify text content using TF-IDF embeddings and XGBoost, handling class imbalance effectively.

## Dataset
Uses a dataset containing text samples with labels indicating whether content was moderated (REMOVED or not).
Preprocessed using feature selection, handling missing values, and balancing classes.

## Model and Techniques Used
1. TF-IDF Vectorization for text feature extraction
2. XGBoost Classifier with hyperparameter tuning
3. Class Imbalance Handling using scale_pos_weight
4. Evaluation Metrics: Precision, Recall, F1-score

## Results and Findings
	•	Balanced dataset performance improvement
	•	Optimized XGBoost model achieving high precision & recall



