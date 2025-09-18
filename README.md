# Restaurant Review Sentiment Analysis  

##  Project Overview  
Customer reviews are one of the most valuable sources of feedback for restaurants. However, reading thousands of reviews manually is inefficient and often leads to missed insights.  

This project automates **sentiment analysis** of restaurant reviews to help businesses:  
- Identify customer satisfaction trends  
- Detect recurring complaints  
- Make data-driven improvements in service and menu offerings  

Using **NLP with DistilBERT** and **interactive Plotly visualizations**, the project converts unstructured text reviews into **actionable business insights**.  

---

## Key Features  
- **Data Cleaning & Preprocessing**: Removed noise (punctuation, emojis, stopwords) and standardized text.  
- **Sentiment Classification**: Applied `distilbert-base-uncased-finetuned-sst-2-english` for positive/negative classification.  
- **Exploratory Analysis**: Word frequency, sentiment ratios, and review length distribution.  
- **Interactive Dashboards**: Built with Plotly for stakeholder-friendly insights.  

---

## Technologies Used  
- **Python** – Core programming language  
- **Pandas & NumPy** – Data wrangling and preprocessing  
- **Hugging Face Transformers** – DistilBERT sentiment classification  
- **NLTK / Regex** – Text cleaning and tokenization  
- **Plotly** – Interactive data visualization  
- **Jupyter Notebook** – Development & experimentation  

---

## Workflow  

1. **Data Acquisition**  
   - Kaggle dataset with restaurant reviews (text + ratings).  

2. **Preprocessing**  
   - Lowercasing  
   - Removing stopwords, punctuation, special characters  
   - Tokenization  

3. **Modeling**  
   - Pretrained model: `distilbert-base-uncased-finetuned-sst-2-english`  
   - Classified reviews as **positive** or **negative**  

4. **Visualization**  
   - Sentiment distribution (positive vs negative)  
   - Common negative keywords (e.g., *cold food*, *slow service*)  
   - Sentiment trends over time  

---

## Outcomes & Business Value  
- **Faster Insights**: Automated sentiment analysis saves hours of manual review reading.  
- **Actionable Insights**: Identified recurring customer pain points and strengths.  
- **Scalable Solution**: Can be applied to any restaurant, hospitality, or retail review dataset.  
