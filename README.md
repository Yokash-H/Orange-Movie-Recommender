#Movie-Recommender
Interactive **movie recommendation system** built using **Orange Data Mining**, a visual programming tool for data analysis and machine learning.

This project is a movie recommendation system, built entirely using Orange Data Mining, a drag and drop tool that makes machine learning super accessible no coding required.
I wanted to explore how we can cluster similar movies together based on features like genre, IMDb rating, runtime, and release year. The idea was to identify groups of similar movies and recommend titles based on these clusters.
I started by loading a dataset of movies into Orange, selected relevant features, and used the K-Means Clustering widget to group them. To understand how well the clustering was working, I added a Silhouette Score widget for evaluation.
Then came the fun part, t-SNE visualization. This widget gave me a cool 2D map of the clustered movies, helping me see how well separated the groups were. Each dot on the map represented a movie, and similar movies stayed close together.

Tools Used
- Orange (No code ML platform)
- K-Means Clustering
- t-SNE for visualization
- Silhouette score for cluster evaluation

Project Files
- `movie_recommendation.ows` – Orange project file
- `movies.csv` – Dataset used (with features like genre, rating, etc.)

Features
- Clusters movies into groups based on selected features
- Visualizes clusters using t-SNE
- Evaluates clustering performance using Silhouette score
- Easy to extend with filters (e.g., genre, rating, year)

Future Scope
- Add user preferences for dynamic filtering
- Recommend movies similar to user’s past liked films
- Deploy using Orange Server or embed as web interface

How to Use
1. Download Orange: [https://orangedatamining.com](https://orangedatamining.com)
2. Load `movie_recommendation.ows`
3. Import dataset
4. Run the workflow!
