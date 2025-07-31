# SpamSniper 📱✉️

**SpamSniper** is an intelligent SMS Spam Classification web application that identifies whether a given message is **"spam"** or **"ham"** (not spam). It uses Machine Learning techniques to perform real-time classification, making it a handy tool for detecting unwanted messages.

---

## 🔍 Features

- ✅ **Naive Bayes Classifier**: Employs a Multinomial Naive Bayes algorithm trained on a large SMS dataset for accurate spam detection.
- 🧠 **Text Preprocessing Pipeline**: Includes steps like lowercasing, tokenization, stopword removal, and stemming to clean and standardize text.
- 🌐 **Streamlit Interface**: User-friendly web interface built with Streamlit for easy interaction and real-time predictions.
- 📊 **Visualization**: Optionally includes basic data insights and model evaluation metrics (like accuracy, confusion matrix, etc.).
- 💡 **Lightweight & Fast**: Optimized for performance and usability — classify a message in milliseconds.

---

## 📌 How It Works

1. The user inputs an SMS message.
2. The text is cleaned and transformed using NLP techniques.
3. The trained model predicts whether the message is spam or ham.
4. The result is displayed immediately with a clear label.

---

## 🌐 Try It Live

👉 [SpamSniper Streamlit App](https://spamsniper-mqpgpexuvwvy3udcmomawx.streamlit.app/)

---

## 📂 Dataset

The model is trained on the [SMS Spam Collection Dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset), which contains 5,000+ labeled SMS messages.

---

## 🛠 Tech Stack

- **Python**
- **Scikit-learn**
- **NLTK**
- **Streamlit**
- **Pandas, NumPy**

---

## 🚀 Future Enhancements

- Add support for more ML models (e.g., SVM, Logistic Regression).
- Add confidence scores or probability output.
- Include email or social media spam detection.
- Save classified messages to a database for further analysis.

---

## 📬 Contact

For suggestions or contributions, feel free to open an issue or fork the repo!

