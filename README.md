# Movie Recommendation Engine

This repository contains a content-based movie recommendation engine developed using Scikit-learn and the TMDB 5000 Movie Dataset from Kaggle. The recommendation engine is implemented with Streamlit for the frontend.

## Setup

### Prerequisites

- Python 3.7 or above

### Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/your-username/Movie-Recommendation-Engine.git
    ```

2. **Navigate to the project directory:**

    ```bash
    cd Movie-Recommendation
    ```

3. **Install the required dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

### Usage

1. **Download the TMDB 5000 Movie Dataset from Kaggle and place the `tmdb_5000_movies.csv` file into the `data` directory.**

2. **Train the recommendation engine:**

   [Refer this notebook](https://www.kaggle.com/code/shubhamv21/movie-recommendation)


    This script will preprocess the data, train the content-based recommendation model using Scikit-learn, and save the model files (`movie_list.pkl` and `similarity.pkl`) in the root directory.

3. **Run the Streamlit app:**

    ```bash
    streamlit run app.py
    ```

    This command will start the Streamlit app locally.

4. **Access the app in your browser at [http://localhost:8501](http://localhost:8501) and interact with the movie recommendation system.**

### Files

- `train_model.py`: Python script to train the recommendation engine using the TMDB dataset.
- `app.py`: Streamlit frontend code for the movie recommendation system.
- `data/`: Directory to store the dataset file (`tmdb_5000_movies.csv`).
- `movie_list.pkl`: Pickle file containing movie information.
- `similarity.pkl`: Pickle file containing similarity scores for movies.
