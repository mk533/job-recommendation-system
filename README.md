# Job Recommendation System

This project aims to develop a job recommendation system that suggests the most suitable jobs to users based on their skills and career motivations. The system leverages machine learning and NLP techniques to match user profiles with job listings.

## Introduction
The job recommendation system is designed to help job seekers find relevant job opportunities by analyzing their skills and career motivations. It uses content-based filtering and pre-trained embeddings to match user profiles with job descriptions from various job boards.

## Features
- User profile and job listing management
- Content-based filtering using SpaCy pre-trained embeddings
- Cosine similarity for job recommendation
- Suggesting the jobs accordingly.


## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/mk533/job-recommendation-system.git
    cd job-recommendation-system
    ```

2. Create and activate a virtual environment (optional but recommended):
    ```bash
    python -m venv venv
    source venv/bin/activate   # On Windows, use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```bash
    python -m spacy download en_core_web_md
    ```


