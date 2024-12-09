# Spotify Song Recommendations

## Authors
- **Ron-Aaron Vahtra**
- **Reno Feliks Lindvere**
- **Martin Koltsov**

## Project Motivation and Goal
Music streaming platforms like Spotify aim to provide users with personalized song recommendations. This project explores the process of building a **Song Recommendation System** and a **Popularity Prediction Model** using machine learning. 

Our goal is to:
- Develop a hit classification model with at least 85% accuracy.
- Build a recommendation system based on user preferences.
- Analyze key characteristics of popular songs for actionable insights.

This project serves as a foundation for understanding the concepts behind music recommendation systems, including data preprocessing, feature engineering, model training, and evaluation.

---

## Repository Contents

Below is an overview of the repository's structure:

### Files and Notebooks:
- **`D11_report.pdf`**: Comprehensive project report.
- **`KaggleDataset.csv`**: Original dataset from Kaggle containing over 500,000 songs with features.
- **`KaggleDataset_reduced.csv`**: Cleaned and reduced dataset for quicker analysis and experimentation.
- **`data_visualization.ipynb`**: Notebook exploring the dataset using visualizations to extract trends and patterns.
- **`popularity_prediction.ipynb`**: Notebook developing a popularity prediction model on the dataset.
- **`popularity_prediction_balanced_dataset.ipynb`**: Refined prediction model with balanced dataset considerations.
- **`song_recommendation_system.ipynb`**: Main notebook implementing the song recommendation system.
- **`README.md`**

---

## Getting Started

### Dataset
The dataset used in this project is sourced from [Kaggle Spotify Dataset](https://www.kaggle.com/datasets/maharshipandya/-spotify-tracks-dataset). It includes metadata and audio features of songs released over 100 years.

### Link to repository
Current repository could be found at [here](https://github.com/ronv3/spotify-song-recommendations).

### Prerequisites
To replicate this project, you need Python installed with the following libraries:
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`

### Steps to Run the Analysis
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/ronv3/spotify-song-recommendations.git
   cd spotify-song-recommendations
