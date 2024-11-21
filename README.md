## Twitter Sentiment Dashboard

### Overview

This project is a real-time sentiment analysis dashboard for Twitter data. It collects tweets based on user-defined keywords or hashtags, analyzes their sentiment, and displays the results on an interactive web dashboard. The application is built using Python with the Flask framework for the backend, Dash for the frontend, and libraries like Tweepy for Twitter API integration and Plotly for visualization.

### Features


- Real-time tweet collection using the Twitter API.
- Sentiment analysis (positive, negative, neutral) of tweets.
- Interactive dashboard with visualizations:
    -Sentiment distribution (pie chart, bar graph).
    -Sentiment trends over time (line graph).
    -Keyword/hashtag filtering.
- REST API to expose processed data for frontend integration.


### Technologies Used

### Backend

- Python
- Flask (REST API)
- Tweepy (Twitter API)
- Frontend
Dash (Plotly Framework for interactive visualizations)
Libraries
NLP: TextBlob, VADER, or Hugging Face Transformers
Data Handling: Pandas
Visualization: Plotly/Dash
Deployment
Docker (optional)
Heroku/AWS/GCP (optional)
