# Book Recommendation Engine

## Overview

Welcome to the Book Recommendation Engine project! This project leverages K-Nearest Neighbors (KNN) and cosine similarity to recommend books similar to a given book title. It uses the Book-Crossings dataset, which includes user ratings and details about books.

## Project Structure

- **data/**: Contains the dataset files.
  - `BX-Book-Ratings.csv`: User ratings for books.
  - `BX-Books.csv`: Details about the books.
- **book_recommendation_engine.py**: Python script that contains the logic for data loading, cleaning, and book recommendation.
- **README.md**: This file.

## Features

- **Data Loading**: Loads and parses CSV files containing book ratings and details.
- **Data Cleaning**: Filters out users with fewer than 200 ratings and books with fewer than 100 ratings.
- **Recommendation Engine**: Uses K-Nearest Neighbors and cosine similarity to recommend books similar to a given title.
- **Testing**: Includes a sample function call to demonstrate how recommendations are generated.

## Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/your-username/book-recs-ml.git
   cd book-recs-ml
