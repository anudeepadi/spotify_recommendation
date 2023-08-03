# Music Recommendation System

This project builds a music recommendation engine using NLP and machine learning techniques. It suggests similar songs based on lyric similarity.

## Description

- Performed text preprocessing and cleaning on lyrics data from 20,000 songs
- Implemented TF-IDF vectorizer to create lyric vectors
- Calculated cosine similarity between lyric vectors to find similarity
- Developed a recommendation engine that takes a song and returns top matching songs
- Used datasets, libraries: scikit-learn, pandas, matplotlib, seaborn  

## Getting Started

### Dependencies

- Python 3.x 
- Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

### Installation

- Clone the repo
```bash
git clone https://github.com/user/music-recommender
```
- Install dependencies
```bash
pip install -r requirements.txt
```

### Usage

- Run recommend.py with the song name as an argument
```bash
python recommend.py "Song Name" 
```
