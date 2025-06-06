
# 🧠 Twitter (X) Sentiment Analysis Project

This project performs sentiment analysis on recent tweets (now called posts on **X**, formerly Twitter) using the Twitter API v2, `TextBlob` for natural language sentiment classification, and optional language translation with `deep_translator`.

## 🔍 Overview

The Python script:
- Connects to Twitter using Tweepy and a Bearer Token.
- Fetches tweets based on a user-defined query.
- Cleans the tweet text to remove noise.
- Optionally translates non-English tweets to English.
- Uses TextBlob to classify tweet sentiment as **positive**, **negative**, or **neutral**.
- Outputs sentiment distribution and sample tweets per category.

## 📈 Example Output

```

Positive tweets percentage: 10.0 %
Negative tweets percentage: 5.0 %
Neutral tweets percentage: 85.0 %

Positive tweets:
RT @AfricanHub\_: In a powerful address...

Negative tweets:
RT @Imranmuhdz: The majority of fuel stations...

````

## 🧰 Tech Stack

- Python 3.10+
- [Tweepy](https://www.tweepy.org/)
- [TextBlob](https://textblob.readthedocs.io/)
- [deep_translator](https://github.com/nidhaloff/deep-translator)
- Twitter Developer API v2

## 🧪 How to Run

1. Clone the repo:

   ```bash
   git clone https://github.com/YourUsername/YourRepoName.git
   cd YourRepoName
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the script:

   ```bash
   python sentiment_analysis.py
   ```

4. Update query terms in the script to analyze other topics.

## 🔐 API Authentication

To use the Twitter API, generate a **Bearer Token** from your [Twitter Developer Portal](https://developer.twitter.com/) and paste it in the `TwitterClient` class.

## 👨‍🎓 Author

**Charles Olanrewaju**
[LinkedIn](https://www.linkedin.com/in/charles-olanrewaju-b63533356/)

---

## 📌 Notes

* Twitter is now officially called **X**.
* Tweets may be in multiple languages; translation helps improve sentiment accuracy.

````

