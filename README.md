# sentiment-analysis-nrc-goemotions
Sentiment Analysis on “HelloTalk” App Review Data with NRC Emotion Lexicon and GoEmotions Dataset

**About Project:**
This project analyzes HelloTalk app reviews to extract insights on user experiences and emotions. We applied topic modeling and emotion analysis, and XGBoost outperformed other sentiment models in accuracy, recall, and F1 score. Key findings highlight topics on language learning and community, with emotions like 'admiration' and 'annoyance' playing a significant role.

### Project Summary

- **Goal**
    - Analyzing users' experiences, opinions, and sentiments from reviews of the HelloTalk app.
- **Background**
    - Employed topic modeling LDA, and two different emotion schemas (NRC & GoEmotions). Conducted 4 different experiments to evaluate the performance of sentiment classification models.
- **Dataset**
    - HelloTalk app reviews collected from the Google Play Store
- **Results**
    - The results showed that the XGBoost algorithm, when combined with topics and emotions, achieved the highest accuracy, recall, and F1 score. In addition, the analysis revealed significant topics related to language learning and community interaction, while emotions such as 'admiration' and 'annoyance' consistently emerged as key factors in user feedback.


File Information:

📎 File 1: "hellotalk.csv" --> Original data \n
📎 File 2: "hellotalk_cleaned_data.csv" --> Cleaned version of original Data
📎 File 3: "hellotalk_cleaning+LDA.ipynb" --> Data cleaning process + performing LDA
📎 File 4: "hellotalk_NRC_GoEmotions.ipynb" --> Emotion analysis using NRC and Go Emotions

