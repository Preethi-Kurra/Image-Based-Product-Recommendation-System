# Image-Based-Product-Recommendation-System
Machine Learning in e-commerce has grown a great deal since the time it has been introduced. Image-based searching has been in consideration for a few years and is finally making its way into the e-commerce domain. We aim to implement image-based product recommendations and enhance their application in e-commerce. Many renowned companies began  experimenting, only a few companies have managed to have their customers experience this technology. Google introduced Google Lens, and through this project, we experimented with the Fashion product images dataset from Kaggle to obtain similar results. Our objective is to build an image-based fashion recommendation system to aid the fashion e-commerce industry with better technology and have a better shopping experience for customers.
	We explored only the unsupervised machine learning aspect of the problem for this project. Our approach includes subsetting the parent data due to computation issues, reducing dimensions using PCA, and t-SNE,  and working with KMeans, GMM, and Agglomerative clustering techniques to cluster the images. We tested both cosine similarity measures and spatial distance matrix to identify the distances between the recommendations and finally recommend 5 similarly looking images. We used Precision@K to determine the best recommendation model, we obtained the best results with t-SNE, Agglomerative, and Spatial distance with a Precision@5 score of 0.75. 
	
## Methods
### Dimensionality Reduction
- PCA
- t-SNE
### Clustering
- KMeans
- GMM
- Agglomerative
### Similarity measures
- Cosine Similarity
- Spatial Distance
### Evaluation
- Precision@K
