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

## Installation and Usage
	# Clone the repository
 	git clone https://github.com/yourusername/NLP-Content-Moderation.git
	cd NLP-Content-Moderation

	# Install dependencies
 	pip install -r requirements.txt

  	# Run the notebook
   	jupyter notebook

## Results and Findings
1. Balanced dataset performance improvement
2. Optimized XGBoost model achieving high precision & recall

## Future Improvements
1. Experiment with deep learning models like LSTMs or Transformers
2. Implement BERT embeddings for improved contextual understanding



