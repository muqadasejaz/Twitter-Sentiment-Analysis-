# 💬 Twitter Sentiment Analysis

            ![sa](https://github.com/user-attachments/assets/508509a3-f102-4e92-bc01-5b2966855d30)
            

Twitter Sentiment Analysis is the process of using Python to understand the **emotions or opinions expressed in tweets automatically**. By analyzing the text, we can classify tweets as **positive (1) or negative (0)**. This helps **businesses and researchers** track **public mood**, **brand reputation**, or **reactions to events** in real time.

This project includes a **trained machine learning model**, a **user-friendly desktop GUI**, and utilizes **natural language processing techniques** to make sentiment predictions from tweet text input.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 📌 Overview

- Build a logistic regression model to classify sentiments in tweets.
  
- Create a graphical interface using **Tkinter** for user interaction.
  
- Predict the sentiment of custom tweet inputs (0 = Negative, 1 = Positive).
  
- Accuracy of trained model: **80%**

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## ✨ Features

- 🔍 Predict sentiment of custom tweets in real-time.
  
- 🧠 Trained model with 88% accuracy.
  
- 📊 Clean and interactive desktop GUI.
  
- 🎯 Easy to use for non-technical users.
  
- 📦 Fully open-source and customizable.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 📁 Dataset

The dataset used is the **Sentiment140** dataset, which contains:

- **1.6 million tweets**
  
- Pre-labeled as **0 = Negative** and **1 = Positive**
  
- Dataset includes tweet text and metadata

📂 Dataset link: [Sentiment140 on Kaggle](https://www.kaggle.com/datasets/kazanova/sentiment140)

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## ✅ Result

- Model Used: **SVM Classifier**
  
- Vectorizer: **TF-IDF**
  
- Accuracy Achieved: **80%**
  
- Sample Predictions:
  
  - `"I love this new phone!" → Positive (1)`
    
  - `"Worst service ever." → Negative (0)`
 
  - Sentiment Distribution:
 
    <img width="389" height="411" alt="image" src="https://github.com/user-attachments/assets/892ffbf8-876a-4ba9-8a04-6d325b8feac8" />

 
  - Confusion Matrix:
 
    <img width="536" height="393" alt="image" src="https://github.com/user-attachments/assets/a93ebf33-a53f-4793-b1f1-f4a1c48f4eee" />
    

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 🛠 Tools & Technologies

| Tool/Library |                Purpose               |
|--------------|--------------------------------------|
| Python       | Core programming language            |
| Scikit-learn | Model training (Logistic Regression) |
| NLTK         | Tokenization, preprocessing          |
| TextBlob     | Sentiment feature extraction         |
| Tkinter      | GUI development                      |
| Pandas       | Data manipulation                    |
| Matplotlib   | Visualization                        |
| Joblib       | Model saving/loading                 |
| PIL (Pillow) | Displaying GUI images                |

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 📸 GUI Preview


- Positive:
  
![GUI Screenshot](<img width="1257" height="585" alt="prediction" src="https://github.com/user-attachments/assets/0c2bb9fd-9a6a-440b-9daa-b7dd11fa3683" />)

- Negative:

  <img width="1307" height="590" alt="predictions jpg" src="https://github.com/user-attachments/assets/81c6f2ce-5d52-4629-9bc7-13a0d462557d" />


-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 📂 How to Run the Project Locally

Follow these steps to set up and run the Twitter Sentiment Analysis GUI on your local machine:

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/muqadasejaz/twitter-sentiment-analysis.git
cd twitter-sentiment-analysis

### 2️⃣ Install Required Libraries

pip install -r requirements.txt

### 3️⃣ Train the model

python scripts/twitter-sentiment-analysis.ipynb

### 4️⃣ Test any email from terminal
python scripts/twitter-sentiment-analysis.ipynb

## 5️⃣ Run GUI app
python scripts/gui.py

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 🔗 References

- [Sentiment140 Dataset](https://www.kaggle.com/datasets/kazanova/sentiment140)
  
- https://arxiv.org/pdf/1601.06971
  
- https://ieeexplore.ieee.org/document/6726818
  
- https://www.geeksforgeeks.org/python/twitter-sentiment-analysis-using-python/

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 👩‍💻 Author

**Muqadas Ejaz**

BS Computer Science (AI Specialization)

Machine Learning & Computer Vision Enthusiast

📫 Connect with me on [LinkedIn](https://www.linkedin.com/in/muqadasejaz/)  

🌐 GitHub: [github.com/muqadasejaz](https://github.com/muqadasejaz)

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 📝 License

This project is licensed under the MIT License.
