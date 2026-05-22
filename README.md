# Exploring the Relationship Between Rhythmic Audio Features and Song Lyrics

Code + notebooks for my bachelor thesis at Tilburg University (CSAI).

The thesis looks at whether some rhythm-related Spotify features (tempo, time signature, duration) have any relationship with the emotional tone or linguistic structure of song lyrics.



The best R² was still under 0.01.

---

## What this project does

The project combines Spotify audio features with Genius lyrics and then tries to predict:

- lyrical sentiment (VADER compound score)
- repetition in lyrics
- lexical diversity (MTLD)

using:

- tempo
- time signature
- duration

The models used were:

- Mean baseline
- Linear Regression
- KNN
- Random Forest

Dataset size after filtering: ~98k English songs.

---

## Folder structure

```bash
.
├── README.md
├── requirements.txt
├── notebook