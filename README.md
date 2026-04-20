# DeepLearning-Music-Genre-Prediction

A deep learning project that classifies music into genres using audio features extracted from the GTZAN dataset.

## Overview

This project applies neural network models to predict music genres based on audio features. It uses the GTZAN Music Genre Dataset, which contains 30-second audio clips across 10 genres, along with pre-extracted features in CSV format.

## Repository Contents

- `Music_Genre_Prediction.ipynb` — Jupyter Notebook with the full deep learning pipeline (data preprocessing, model training, and evaluation)
- - `features_30_sec.csv` — Audio features extracted from 30-second clips
  - - `features_3_sec.csv` — Audio features extracted from 3-second clips
    - - `genres_original/` — Original audio files organized by genre
      - - `images_original/` — Mel spectrogram images organized by genre
        - - `Project Narrative Writeup.pdf` — Detailed project narrative and findings
         
          - ## Technologies Used
         
          - - Python
            - - Jupyter Notebook
              - - TensorFlow / Keras
                - - Librosa
                  - - Pandas, NumPy, Matplotlib
                   
                    - ## Getting Started
                   
                    - 1. Clone the repository:
                      2.    ```bash
                               git clone https://github.com/RifatIbnAlam/DeepLearning-Music-Genre-Prediction.git
                               ```
                            2. Open `Music_Genre_Prediction.ipynb` in Jupyter Notebook or JupyterLab.
                            3. 3. Run the cells sequentially to train and evaluate the model.
                              
                               4. ## Author
                              
                               5. **Rifat Ibn Alam** — [GitHub](https://github.com/RifatIbnAlam) | [LinkedIn](https://linkedin.com/in/rifat-ibn-alam)
