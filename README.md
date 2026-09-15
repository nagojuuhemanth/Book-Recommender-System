# Book-Recommender-System
---
# Book Recommender System

A content-based book recommendation system that uses natural language processing and Sentence-BERT (SBERT) embeddings to recommend books based on the semantic similarity of their summaries.

The system allows users to enter a book, description, or preference and retrieves books with similar semantic content.

## Features

- Content-based book recommendations.
- Semantic similarity using Sentence-BERT.
- Book summary embedding generation.
- Cosine similarity-based matching.
- Search books using natural language queries.
- React-based frontend.
- Node.js and Express.js backend.
- REST API endpoints.
- Dynamic recommendation results.

## Tech Stack

### Frontend

- React.js
- JavaScript
- HTML
- CSS

### Backend

- Node.js
- Express.js
- REST APIs

### NLP / Machine Learning

- Python
- Sentence-BERT
- Sentence Transformers
- Text Embeddings
- Cosine Similarity

### Data

- Book titles
- Authors
- Book summaries
- Genres
- Metadata

## System Architecture

```text
              Book Dataset
                   |
                   v
            Text Preprocessing
                   |
                   v
          Sentence-BERT Model
                   |
                   v
          Book Embeddings
                   |
                   v
          Similarity Search
                   ^
                   |
             User Query
                   |
                   v
          Query Embedding
                   |
                   v
        Top-K Recommendations
                   |
                   v
           React Frontend
