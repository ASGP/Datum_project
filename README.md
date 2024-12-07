# Vehicle Analysis and Sentiment Dashboard  

This project was developed as part of the Python Workshop Competition held by the University of Sri Jayewardenepura (PyData). The project consists of three main tasks focusing on data cleaning, analysis, visualization, and sentiment analysis using state-of-the-art techniques.  

## Tasks Overview  

### Task 1: Dataset Integration and Analysis  
- Combined multiple datasets based on vehicle fuel type into a unified dataset.  
- Performed thorough data cleaning, including handling missing values and inconsistent data.  
- Conducted exploratory data analysis (EDA) to uncover trends and insights about vehicle characteristics and fuel types.  

### Task 2: Dashboard Creation  
- Built an interactive dashboard using the cleaned dataset.  
- Visualizations include:  
  - Status breakdown of vehicles (active, inactive, etc.).  
  - Counts of vehicle types and wheelchair-accessible vehicles.  
  - Geographic map visualizing vehicle distribution across cities in Illinois.  

### Task 3: Sentiment Analysis of Car Reviews  
- Utilized a dataset of car reviews for the state of Illinois (IL).  
- Deployed **Hugging Face NLP models** to analyze the sentiment of the reviews (positive, negative, neutral).  
- Models used:  
  - `distilbert-base-uncased`: For text preprocessing and embeddings.  
  - `nlptown/bert-base-multilingual-uncased-sentiment`: For sentiment classification.  
- Leveraged **GPU acceleration** for faster inference of Hugging Face models, significantly reducing processing time for large datasets.  
- Extracted key insights to understand customer feedback patterns.  

## Features  
- Data cleaning and preprocessing.  
- Interactive dashboard providing insights on vehicle statuses and types.  
- Sentiment analysis pipeline using GPU-accelerated pre-trained transformer models.  
- Visualizations of review sentiments for actionable insights.  

## Tools & Technologies  
- **Python**: Data analysis, visualization, and NLP pipeline.  
- **Pandas & NumPy**: Data cleaning and preprocessing.  
- **Plotly Dash**: Interactive dashboard development.  
- **Hugging Face Transformers**: Sentiment analysis model deployment.  
- **PyTorch**: GPU-accelerated model inference.  
- **Geopandas & Mapbox**: Geographic visualizations.  
- **Power BI**: Supplementary analysis and visualizations.  


## Results 
### Dashboard





### Sentiment Analysis Results

Positive or negative the given reviews

![image](https://github.com/user-attachments/assets/d63a19ba-b80b-4c6d-a310-5d814b504b8c)


Catergorical distribution

![image](https://github.com/user-attachments/assets/2999fb12-496d-4fa6-b5a9-322831f93d7a)


