# Content-Based Movie Recommendation System

Recommends similar movies using **content features** from the TMDB 5000 dataset (genres, keywords, cast, crew, overviews).

## Approach
1. Load and clean TMDB movies + credits
2. Build a combined text / feature representation per title
3. Compute similarity (e.g. cosine) between movies
4. Return top-N neighbors for a seed title

## Stack
`Python` · `pandas` · `scikit-learn` · NLP feature engineering · Jupyter

## Data
See `archive/` for TMDB CSVs and the main notebook.

## Run
```bash
jupyter notebook archive/movie-recommendation\ system.ipynb
```

## Author
[Sujith Reddy Venna](https://github.com/Venna-Sujith-Reddy) · [Portfolio](https://venna-sujith-reddy.github.io/My-portfolio/)
