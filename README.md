# yourReviewIsNoted

Project scrapes and analyses Google Maps customer reviews for Papa John's in Frankfurt Niederrad. It translates reviews to English, uses a local LLM to categorise complaints, and visualises insights.

## Features

- Fetch reviews in multiple languages using SerpAPI  
- Translate reviews to English via Deep Translator  
- Use local LLM (e.g., LM Studio Gemma-3) to cluster complaint themes  
- Visualise complaint distribution and common words in negative reviews (ratings ≤ 3 Stars)

## Repository Structure

```text
root/
│
├── reviewAnalysis.ipynb       # Jupyter notebook containing the analysis workflow
├── requirements.txt           # Python dependencies 
├── README.md                  # This file
├── images/                    # Folder containing visualisation images
│   ├── complaint_categories_pie.png
│   ├── negative_ratings_histogram.png
│   └── negative_reviews_wordcloud.png
```
