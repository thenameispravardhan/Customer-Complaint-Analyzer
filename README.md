# Customer Complaint Analyzer - AI Agent  
IBM SkillsBuild Winter Certification Program – Applied Artificial Intelligence

## Project Overview
An intelligent system that automatically analyzes customer complaints to improve customer service efficiency and customer satisfaction.

### Main Features
- Sentiment Analysis: Detects emotional tone (Angry, Frustrated, Neutral, Mild)  
- Automated Categorization: Classifies complaints into 5 categories (Billing, Product, Service, Delivery, Technical)  
- Priority Scoring: Assigns urgency levels (High, Medium, Low) based on sentiment and keywords  
- Resolution Templates: Generates personalized response suggestions  
- Interactive Dashboard: Visual analytics with charts and insights  
- Real-time Analysis: Interactive input for analyzing new complaints  

## Business Value
- Faster response times through automated routing to appropriate departments  
- Better prioritization of critical issues  
- Data-driven insights to identify patterns and improvement areas  
- Reduced manual processing time and operational costs  
- Improved customer satisfaction through timely and appropriate responses  

## How to Run

### Option 1: Google Colab (Recommended)
1. Upload customer_complaint_analyzer.ipynb to Google Colab  
2. Run all cells sequentially (Runtime → Run all)  
3. Libraries will be installed automatically  
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

## Technologies Used
- Python  
- NLTK & TextBlob (text processing)  
- VADER (sentiment analysis)  
- Scikit-learn (machine learning, Logistic Regression, TF-IDF)  
- Pandas (data manipulation)  
- Matplotlib & Seaborn (visualization)  
- WordCloud (keyword visualization)  
- IPyWidgets (interactive interface)  

## Sample Output

Analysis Results for a Complaint:

```
CUSTOMER COMPLAINT ANALYSIS REPORT
================================================================================
ORIGINAL COMPLAINT:
I was charged twice for the same order! This is unacceptable...

ANALYSIS RESULTS:
  CATEGORY: Billing (Confidence: 89.2%)
  SENTIMENT: Angry (Score: -0.847)
  PRIORITY: High (Score: 75/100)

RECOMMENDED ACTION:
  URGENT: Route to senior support immediately
  Respond within 2-4 hours

SUGGESTED RESPONSE TEMPLATE:
  Dear Customer,
  We sincerely apologize for the billing error. This is unacceptable...
```

Dashboard Visualizations:
- Category distribution (pie chart)  
- Sentiment breakdown by category  
- Priority level distribution  
- Word cloud of frequent terms  

## AI Concepts Demonstrated
1. Natural Language Processing  
   - Text preprocessing, tokenization  
   - Stopword removal, lemmatization  
   - Sentiment analysis (VADER)  

2. Machine Learning  
   - Supervised classification (Logistic Regression)  
   - Feature extraction (TF-IDF)  
   - Multi-class text classification  

3. Rule-Based Logic  
   - Priority scoring algorithm  
   - Keyword-based urgency detection  
   - Response template generation  

4. Data Science  
   - Exploratory data analysis  
   - Statistical summaries  
   - Data visualization  

## Project Structure
```
customer_complaint_analyzer/
├── customer_complaint_analyzer.ipynb     # Main notebook
├── requirements.txt                      # Dependencies
├── README.md                             # Documentation
└── complaint_analysis_dashboard.png      # Generated dashboard image
```

## Future Enhancements
- Integration with email and chat support systems  
- Multi-language complaint analysis  
- Historical trend analysis and forecasting  
- CRM platform integration  
- Real-time alerts for critical complaints  
- Deep learning models for improved accuracy  

## About
Project Type: AI Agent for Business Automation  
Domain: Customer Service & Support  
Created for: IBM SkillsBuild Winter Certification Program - Applied AI  
Date: December 2025  

## License
Created for educational purposes as part of the IBM SkillsBuild certification program.

## Acknowledgments
- IBM SkillsBuild – Applied AI learning program  
- NLTK, Scikit-learn, and other open-source libraries  
- Google Colab – free cloud computing environment  

This version keeps all important information while using clear, simple, and professional language.
