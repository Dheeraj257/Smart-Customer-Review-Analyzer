# Smart-Customer-Review-Analyzer
An AI-powered sentiment analyzer that uses NLP and DistilBERT to classify and visualize Amazon product reviews.
Smart Customer Review Analyzer (NLP + AI)

This project is a sentiment analysis tool built to analyze customer reviews using a blend of classical Natural Language Processing (NLP) and modern AI models. It uses Amazon product reviews to classify sentiments and extract meaningful patterns from text data.

---

Features

- Classifies reviews as positive or negative using both rule-based logic and transformer-based models.
- Performs sentiment comparison, length analysis, and generic review detection.
- Visualizes sentiment patterns and behavior using powerful Python libraries.
- Uses pre-trained DistilBERT from Hugging Face for enhanced classification accuracy.

---

Technologies Used

- Pandas, Seaborn, Matplotlib
- Hugging Face Transformers (DistilBERT)
- NLP (tokenization, sentiment scoring, text preprocessing)

---

Dataset

This project uses the [Amazon Reviews Dataset](https://www.kaggle.com/datasets/bittlingmayer/amazonreviews) from Kaggle.  
Due to its large size, the dataset is **not included** in this repository.

To use this project, download the `train.ft.txt` file from Kaggle and place it in a folder named `amazon_reviews/` inside your project directory.

