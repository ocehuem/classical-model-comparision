# classical-model-comparision
A Comparative Study of Classical Models, Feature Spaces, and Reduced-Dimension Techniques for Suicide Detection on Social Media with Geolocation
# A Comparative Study of Classical Models, Feature Spaces, and Reduced-Dimension Techniques for Suicide Detection on Social Media

This project presents a comprehensive evaluation of **27+ model–feature combinations** for suicide ideation detection using classical machine-learning techniques. We compare TF-IDF, Bag-of-Words, Chi-Square-selected vocabularies, and SVD-based latent semantic embeddings, along with PCA/t-SNE for dimensionality reduction. Additionally, we explore **geolocation extraction**, **social-media analysis**, **DGIM/sliding-window algorithms**, and **user-user similarity metrics** for Instagram, Reddit, and X datasets.

## 🚀 Key Objectives
- Identify the most effective feature representation for classical ML models.
- Quantify the effect of dimensionality reduction on classification performance.
- Compare linear models, boosting models, neural networks, and ensembles.
- Perform geolocation of crisis-related posts using NER and similarity matching.
- Analyze user behavior and risks using stream algorithms and similarity metrics.

## 📊 Methodology
- Models: Logistic Regression, Linear Regression, NN (1-layer), KNN, Decision Tree, XGBoost, LightGBM, Perceptron, Ensemble, Sentence Transformers, VADER, TextBlob, Bloom Filter, DGIM, Sliding Window, Collaborative Filtering.
- Features: TF-IDF, BoW, CHI2-1000, SVD-300.
- Dimensionality Reduction: PCA (2, 50, 100), t-SNE (2D).
- Additional Tasks: Geolocation mapping, similarity analysis on Instagram, DGIM vs Sliding Window evaluation.

## 🏆 Key Findings
- **TF-IDF + Logistic Regression** is the strongest overall model with highest ROC-AUC and F1.
- **CHI2-1000** performs nearly as well as TF-IDF, proving that selective vocabulary reduction preserves signal.
- **PCA/t-SNE drastically reduce performance** — not suitable for supervised classification.
- **Boosting models** perform well but do not surpass linear models in high-dimensional sparse spaces.
- **DGIM (event-level)** closely matches Sliding Window performance for detecting risky activity spikes.
- **Geolocation** accuracy improves using blacklists + similarity measures.

## 🌍 Geolocation Visualization
Interactive map:  
🔗 `https://prakriti16.github.io/SDM_Project/`

## 📁 Repository Structure
