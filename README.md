# azure-sentiment-analysis

# Azure AI Sentiment Analysis Demo

This project demonstrates how I used **Azure AI Language (Text Analytics)** to analyze sentiment in short text samples.  
The model classifies text as **positive**, **negative**, **neutral**, or **mixed**, with confidence scores for each.

---

## 📌 Project Overview
- **Platform:** Microsoft Azure AI Language  
- **Service:** Sentiment Analysis (Text Analytics)  
- **Goal:** Show how Azure can automatically detect sentiment in customer feedback.  
- **Outputs:** JSON files with model predictions and confidence scores.

---

## 📝 Test Sentences and Results

1. **Positive Example**  
   *Input:*  
   > "I absolutely love this product! The setup was easy and the results are amazing."  
   *Output:* [positive.json](Positive.json)

2. **Negative Example**  
   *Input:*  
   > "This service is a waste of time. It constantly fails and support never responds."  
   *Output:* [negative.json](Negative.json)

3. **Mixed Example**  
   *Input:*  
   > "The instructions were confusing at first, but once I figured them out, the process was simple and smooth."  
   *Output:* [mixed.json](Mixed.json)

---

## 📂 Repository Structure

├── positive.json # Sentiment output for positive text
├── negative.json # Sentiment output for negative text
├── mixed.json # Sentiment output for mixed text
└── README.md # Project documentation


## ✅ Example Output (Positive)

```json
{
  "inputText": "I absolutely love this product! The setup was easy and the results are amazing.",
  "sentiment": "positive",
  "confidenceScores": {
    "positive": 0.98,
    "neutral": 0.01,
    "negative": 0.01
  }
}
```
🚀 How to Reproduce

Create an Azure AI Language resource in the Azure Portal
Open Language Studio
Select your resource → choose Sentiment Analysis.
Paste text → Run → Export results as JSON.

💡 What I Learned

How to deploy and use Azure AI Language services.
That I only needed to create one resource (Azure AI Language) for this project — not multiple resources.
How to use Language Studio to test AI models without writing code.
How to interpret AI outputs like confidence scores and understand what they mean.
How to document results in JSON and organize them in a GitHub repository.

How to document results in JSON and organize them in a GitHub repository.
