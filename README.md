# Content-Based News Recommendation System

## Project Description

This project builds a content-based news recommendation system that recommends news articles to users based on the similarity between article content and user interests. It uses TF-IDF to extract text features and cosine similarity to match articles with the user's preferred topics or keywords.

## Instructions and Usage

1. Place the `news.tsv` file inside the `data/` folder.

2. Install the required libraries using:
   ```bash
   pip install -r requirements.txt
   python -m spacy download en_core_web_sm
   3.	Run the notebooks in order:
	•	01_data_preprocessing.ipynb
	•	02_user_profile_construction.ipynb
	•	03_content_similarity.ipynb
	•	04_ranking_and_recommendation.ipynb
	4.	The final recommendations will be saved in:
	•	results/sample_recommendations.csv
	•	results/user_feedback_notes.txt (optional)
