# 🤖 Customer Complaint Analyzer - AI Agent

**IBM SkillsBuild Winter Certification Program – Applied Artificial Intelligence**

---

## 📋 Project Overview

An intelligent AI agent that automatically analyzes customer complaints to help businesses improve customer service efficiency and satisfaction.

### Key Features

✅ **Sentiment Analysis** - Detects emotional tone (Angry, Frustrated, Neutral, Mild)  
✅ **Automated Categorization** - Classifies complaints into 5 categories (Billing, Product, Service, Delivery, Technical)  
✅ **Priority Scoring** - Assigns urgency levels (High, Medium, Low) based on sentiment and keywords  
✅ **Resolution Templates** - Generates personalized response suggestions  
✅ **Interactive Dashboard** - Visual analytics with charts and insights  
✅ **Real-time Analysis** - Interactive widget for analyzing new complaints  

---

## 💼 Business Value

- **⚡ Faster Response Times** - Automated routing to appropriate departments
- **🎯 Better Prioritization** - Critical issues handled immediately
- **📊 Data-Driven Insights** - Identify patterns and improvement areas
- **💰 Cost Reduction** - Reduce manual complaint processing time
- **😊 Improved Satisfaction** - Empathetic, timely responses

---

## 🚀 How to Run

### Option 1: Google Colab (Recommended)

1. Upload `customer_complaint_analyzer.ipynb` to Google Colab
2. Run all cells sequentially (Runtime → Run all)
3. Libraries will auto-install
4. Interactive widgets will appear for testing

### Option 2: Local Jupyter Notebook

1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

2. Launch Jupyter:
   ```bash
   jupyter notebook customer_complaint_analyzer.ipynb
   ```

3. Run all cells

---

## 🛠️ Technologies Used

- **Python** - Core programming language
- **NLTK & TextBlob** - Natural language processing
- **VADER** - Sentiment analysis engine
- **Scikit-learn** - Machine learning (Logistic Regression, TF-IDF)
- **Pandas** - Data manipulation and analysis
- **Matplotlib & Seaborn** - Data visualization
- **WordCloud** - Keyword visualization
- **IPyWidgets** - Interactive UI components

---

## 📊 Sample Output

### Analysis Results for a Complaint:

```
🤖 CUSTOMER COMPLAINT ANALYSIS REPORT
================================================================================

📝 ORIGINAL COMPLAINT:
I was charged twice for the same order! This is unacceptable...

📊 ANALYSIS RESULTS:
  💰 CATEGORY: Billing (Confidence: 89.2%)
  😡 ANGRY SENTIMENT (Score: -0.847)
  🔴 HIGH PRIORITY (Score: 75/100)

💡 RECOMMENDED ACTION:
  ⚠️ URGENT: Route to senior support immediately
  ⚠️ Respond within 2-4 hours

💬 SUGGESTED RESOLUTION TEMPLATE:
  Dear Customer,
  We sincerely apologize for the billing error. This is unacceptable...
```

### Dashboard Visualizations:
- Category distribution pie chart
- Sentiment breakdown by category
- Priority level distribution
- Word cloud of common keywords

---

## 🎯 AI Concepts Demonstrated

1. **Natural Language Processing (NLP)**
   - Text preprocessing and tokenization
   - Stopword removal and lemmatization
   - Sentiment analysis using VADER

2. **Machine Learning**
   - Supervised learning (Logistic Regression)
   - Feature extraction (TF-IDF vectorization)
   - Multi-class text classification

3. **Rule-Based AI**
   - Priority scoring algorithm
   - Keyword-based urgency detection
   - Template generation system

4. **Data Science**
   - Exploratory data analysis
   - Statistical insights
   - Data visualization

---

## 📸 Screenshots

The notebook generates:
- `complaint_analysis_dashboard.png` - Comprehensive visualization dashboard
- Interactive analysis results for presentations

---

## 🎓 Learning Outcomes

Through this project, I learned:

✅ How to apply NLP techniques to real business problems  
✅ Building and training machine learning classifiers  
✅ Creating interactive AI applications with Python  
✅ Designing rule-based decision systems  
✅ Visualizing data insights for stakeholder presentations  
✅ End-to-end AI agent development workflow  

---

## 📝 Project Structure

```
customer_complaint_analyzer/
│
├── customer_complaint_analyzer.ipynb  # Main Jupyter notebook
├── requirements.txt                    # Python dependencies
├── README.md                          # This file
└── complaint_analysis_dashboard.png   # Generated visualization
```

---

## 🔮 Future Enhancements

- Integration with real customer support systems (email, chat)
- Multi-language support for international customers
- Historical trend analysis and forecasting
- Integration with CRM platforms
- Real-time alerting for critical complaints
- Deep learning models for better accuracy

---

## 👨‍💻 About

**Project Type**: AI Agent for Business Automation  
**Domain**: Customer Service & Support  
**Created For**: IBM SkillsBuild Winter Certification Program - Applied AI  
**Date**: December 2025  

---

## 📄 License

This project is created for educational purposes as part of the IBM SkillsBuild certification program.

---

## 🤝 Acknowledgments

- **IBM SkillsBuild** - For the Applied AI learning program
- **NLTK & Scikit-learn** - For powerful NLP and ML libraries
- **Google Colab** - For providing free cloud computing resources

---

**Ready to analyze complaints like a pro! 🚀**
