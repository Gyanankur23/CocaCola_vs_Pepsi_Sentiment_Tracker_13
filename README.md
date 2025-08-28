# CocaCola_vs_Pepsi_Sentiment_Tracker_13 CaseCraft Analytics Project Sprint Project 13

## 🥤 Overview  
This project tracks public sentiment toward Coca-Cola and Pepsi using synthetic tweet data and NLP techniques. It blends sentiment analysis, brand classification, and strategic visualization to decode consumer perception.

## 🎯 Objective  
To analyze tweet-level sentiment for both brands, compare emotional tone, and build a classifier to predict brand from text.

## 🐦 Dataset & Features  
- Tweets: 1,000 synthetic entries  
- Brands: Coca-Cola, Pepsi  
- Features: timestamp, tweet text, sentiment polarity (TextBlob)  
- Derived: sentiment label (Positive, Neutral, Negative)

## 📊 Visual Explorations  
- Bar chart: Sentiment distribution by brand  
- Line chart: Daily sentiment trend  
- WordClouds: Brand-specific emotional vocabulary  
- Confusion matrix: Brand prediction from tweet text

## 🔍 Sentiment Analysis  
- TextBlob used to compute polarity  
- Coca-Cola shows slightly higher positive sentiment  
- Pepsi tweets lean more neutral/negative  
- Sentiment fluctuates daily with brand-specific spikes

## 🤖 Brand Classification Model  
- Model: Random Forest Classifier  
- Input: CountVectorizer on tweet text  
- Target: brand  
- Performance:  
  - Accuracy: ~48%  
  - Precision/Recall: ~0.46–0.50 per brand  
  - WordCloud reveals brand-specific emotional cues

## 🧠 Key Insights  
1. **Sentiment Split**: Coca-Cola leads in positive sentiment; Pepsi has more mixed feedback  
2. **Temporal Trends**: Sentiment varies over time, with brand-specific peaks  
3. **Text Signals**: Emotional vocabulary differs across brands  
4. **Model Utility**: Moderate accuracy in predicting brand from tweet text  
5. **Strategic Value**: Supports brand monitoring and perception analysis

## ✅ Final Conclusion  
Sentiment tracking reveals nuanced brand perception between Coca-Cola and Pepsi. While Coca-Cola enjoys slightly more positive sentiment, Pepsi’s feedback is more varied. This framework enables automated brand monitoring and emotional signal extraction—ideal for marketing teams and brand strategists.