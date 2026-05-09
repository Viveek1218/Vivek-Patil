# Cosmetic Product Recommendation System using t-SNE

## Project Overview
This project analyzes cosmetic product ingredients and visualizes similarities between skincare products using NLP techniques and t-SNE dimensionality reduction.

The system helps identify products with similar ingredient compositions through interactive visualization.

---

# Objective

- Analyze cosmetic product ingredients
- Filter products suitable for dry skin
- Convert ingredient lists into numerical vectors
- Apply dimensionality reduction using t-SNE
- Visualize product similarity interactively

---

# Dataset

The project uses the `cosmetics.csv` dataset containing:

- Product Name
- Brand
- Ingredients
- Product Type
- Price
- Rank
- Skin Type Compatibility

---

# Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Bokeh

---

# Workflow

## 1. Data Loading
Load and explore the cosmetics dataset.

## 2. Data Filtering
Filter moisturizer products suitable for dry skin.

## 3. Ingredient Processing
Convert ingredient lists into lowercase tokens.

## 4. One-Hot Encoding
Transform ingredient tokens into binary vectors.

## 5. Document-Term Matrix
Create a matrix representing products and ingredients.

## 6. t-SNE Dimensionality Reduction
Reduce high-dimensional data into 2D space.

## 7. Interactive Visualization
Visualize product similarity using Bokeh scatter plots.

---

# Features

- Ingredient similarity analysis
- One-Hot Encoding
- t-SNE dimensionality reduction
- Interactive Bokeh visualization
- Hover tool displaying product details

---

# Sample Insights

- Products positioned close together share similar ingredients.
- Similar formulations appear clustered together.
- Helps users compare skincare products effectively.

---

# Future Improvements

- Add product recommendation system
- Include more skincare categories
- Deploy as a web application
- Add clustering algorithms
- Improve similarity metrics

---

# Conclusion

This project demonstrates how NLP and machine learning techniques can be applied to cosmetic product analysis. By transforming ingredient data into numerical representations and visualizing them using t-SNE, the project enables effective exploration of skincare product similarities.

---

# Author

Vivek Patil
