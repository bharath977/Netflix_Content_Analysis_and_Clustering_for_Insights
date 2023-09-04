1. README.md
2. Dataset
3. NETFLIX MOVIES AND TV SHOWS CLUSTERING.csv
4. EDA
  ## Numeric & Categoric features

       # (a) Univariate Analysis

       # (b) Bivariate Analysis

       # (c) Multivariate Analysis
5. Data Cleaning
       # (a)  Duplicated values

       # (b)  NaN/Missing values

       # (c)  Treating Skewness

       # (d)  Treating Outlier 
6. Textual Data Preprocessing
      # (a) Clustering Attributes

      # (b) Removing Stopwords

      # (c) Lowercasing words

      # (d) Removing Punctuation

      # (e) Stemming

      # (f) Snowball Stemmer

      # (g) Word Vectorization

      # (h) TF-IDF (Term Frequency - Inverse Document Frequency)
7. Dimenssionality Reduction
      * PCA (Principle Component Analysis)
8. Model Building
   # Clustering Implemention

      # (a) K-Means Clustering

      # (b) Elbow Method

      # (c) Silhoutte Score Analysis

      # (d) Agglomerative Hierarchical Clustering

          * Dendogram
9. Content Based Recommendation System
10. Future Work
11. Conclusion
In conclusion, the exploratory data analysis (EDA) of Netflix's TV shows and movies clustering has revealed a wealth of insights that shed light on the platform's content distribution, production trends, viewer preferences, and global impact. From the data, several key takeaways emerge:

Content Diversity and Global Reach:
Netflix's library showcases a rich diversity of content, with a focus on both TV shows and movies. The platform's international TV shows and the popularity of crime and kids' TV genres underscore the global audience's appetite for varied storytelling from different cultures and genres.

Production Trends: Over the years, Netflix has experienced rapid growth in content production. The surge in TV shows and movies from 2016 to 2020 reflects the streaming industry's evolving landscape, with platforms like Netflix responding to the demand for original content.

Global Influences:
The dominance of the United States in content production highlights its historical and industrial strength, while the rise of Indian content underscores the influence of factors like growing middle-class populations, disposable incomes, and the popularity of streaming services.

Regional Success Stories:
The prominence of South Korean dramas in the TV show market demonstrates the power of the Korean Wave, while Canada's financial support for TV shows has attracted both domestic and foreign investment.

Viewer Engagement:
The popularity of Japanese voice actors, crime TV shows, kids' TV, British TV shows, and documentaries showcases viewers' diverse interests, from crime thrillers to educational content, across cultures and genres.

Quality and Collaboration:
The involvement of prolific directors and actors suggests Netflix's emphasis on quality and collaboration, both within and beyond traditional entertainment industries.

In essence, the EDA illustrates Netflix's commitment to catering to a global audience by offering diverse, engaging, and high-quality content. The platform's strategic content production, collaborations with industry leaders, and focus on viewer preferences position it as a frontrunner in the evolving world of entertainment streaming.

Conclusions drawn from ML Model
Implemented K-Means Clustering and Agglomerative Hierarchical Clustering, to cluster the Netflix Movies TV show dataset.
The optimal number of clusters we are getting from K-means is 4, whereas for Agglomerative Hierarchical Clustering the optimal number of clusters are found out to be 2.
We chose Silhouette Score as the evaluation metric over distortion score because it provides a more intuitive and interpretable result. Also Silhouette score is less sensitive to the shape of the clusters.
Built a Recommendation system that can help Netflix improve user experience and reduce subscriber churn by providing personalized recommendations to users based on their similarity scores.
