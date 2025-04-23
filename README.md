# Text-Based Sentiment System Analysis - CIS4870
## Overview
- **Objective**
  - The purpose of the text-based sentiment analysis is to classify user feedback into negative, neutral, and positive categories. The analysis seeks to provide a general overview of the newly implemented tagging system's performance and functionality.
  
- **Data Source**
  - Post-Survey: Column [Answer 13] = "Any additional comments regarding the assignment or the system?"

## Steps
- **Preprocessed data using Excel**
  - Removed Irrelevant columns along with records with no comments to ensure consistency and accuracy for analysis.
    
- **Applied sentiment analysis using VADER**
  - Responsible for handling stop words, playing a crucial role in the sentiment calculation.
  - Used the compound score from VADER to evaluate the overall sentiment (positive, negative, neutral).
  - Leveraged conditional logic to classify sentiment into categories: Positive, Negative, and Neutral.
  
- **Visualized results using Matplotlib & Seaborn**
  - Created a bar chart to visualize sentiment distribution, enhancing the understanding of sentiment proportions.
    - **X-axis**: Sentiment Type (negative, neutral, positive)
    - **Y-axis**: Count of Sentiment Type

## Results
- **Key insights**

  - **50.8%** of additional comments identified **POSITIVE**.
  - **27.9%** of additional comments identified **NEGATIVE**.
  - **21.3%** of additional comments identified **NEUTRAL**.
