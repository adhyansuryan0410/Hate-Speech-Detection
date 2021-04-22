# Hate-Speech-Detection
My B.Tech Project on Hate Speech Detection

# Dataset
This project uses HateBase Twitter dataset's tweets for its training. You can find the workflow in the ppt presentation.
Anyways, it uses Tfidf for feature-extraction and feeds these features to various predefined ML models to test their performance. After that, it employs chi-square test for another round of feature-extraction, details about which you can find in ppt slides and report.pdf file.
Then it creates a meta classifier using 200 tweets and putting a SVC model on top of existing view classifier.
