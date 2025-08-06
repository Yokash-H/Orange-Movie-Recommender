# Orange-Movie-Recommender
A movie recommendation system built using Orange Data Mining Tool

Movie Recommendation System (Orange)

This is a simple, interactive **movie recommendation system** built using **Orange Data Mining**, a visual programming tool for data analysis and machine learning.

Tools Used
- Orange (No-code ML platform)
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
