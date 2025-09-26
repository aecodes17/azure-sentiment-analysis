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
## 🚀 How to Reproduce
- Create an **Azure AI Language resource** in the [Azure Portal](https://portal.azure.com).  
- Open **[Language Studio](https://language.cognitive.azure.com/)**.  
- Select your resource → choose **Sentiment Analysis**.  
- Paste text → Run → Export results as JSON.  

---

## 💡 What I Learned
- Deployed and used **Azure AI Language services** for the first time.  
- Learned that only **one resource (Azure AI Language)** was needed — not multiple resources.  
- Explored **Language Studio** as a no-code environment for testing AI models.  
- Interpreted **confidence scores** and how Azure AI evaluates sentiment.  
- Practiced documenting results in **JSON format** and organizing them in a GitHub repository.  
