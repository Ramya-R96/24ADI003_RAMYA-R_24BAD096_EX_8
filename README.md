Scenario 1 – Association Rule Mining using Apriori Algorithm

Dataset (Kaggle – Public)
Market Basket Dataset / Grocery Dataset Example: https://www.kaggle.com/datasets/heeraldedhia/groceries-dataset

the objective is to analyze transactional datasets such as grocery or market basket datasets and identify patterns of items frequently bought together. Public datasets can be obtained from Kaggle, such as the Groceries Dataset. The input features include Transaction ID and Items Purchased, while the output consists of frequent itemsets and association rules. The implementation begins by importing required Python libraries such as Pandas and mlxtend, followed by loading the dataset and preprocessing the transactions into one-hot encoded format. The Apriori algorithm is then applied with a minimum support threshold to generate frequent itemsets. After that, association rules are created and filtered using confidence and lift values to determine the strongest relationships between items.
The main evaluation metrics used in Scenario 1 are Support, Confidence, and Lift. Support indicates how frequently an itemset appears in the dataset, confidence measures the probability that customers buying one item also buy another, and lift shows the strength of the relationship compared to random chance. Analysis tasks include studying how changing support thresholds affects the number of frequent itemsets, comparing rules under different confidence values, and understanding the business meaning of discovered patterns. Visualizations such as bar charts of frequent itemsets, network graphs of association rules, and support versus confidence scatter plots can be used for better interpretation.

Scenario 2 – Dimensionality Reduction using PCA

Dataset (Kaggle – Public)
Market Basket Dataset / Grocery Dataset Example: https://www.kaggle.com/datasets/heeraldedhia/groceries-dataset

the objective is to transform high-dimensional numerical data into a smaller number of principal components while retaining most of the variance in the dataset. Common datasets used for this scenario include the Machine Learning Iris Dataset, Wine Dataset, or any dataset containing multiple numerical attributes. The input consists of numerical features, and the output is a reduced set of principal components. The implementation starts by loading the dataset, handling missing values if present, and standardizing the features to ensure equal scaling. PCA is then applied to compute the principal components and determine the explained variance ratio for each component.
The main evaluation metrics used in Scenario 2 are Explained Variance Ratio and Cumulative Variance. These metrics help determine how much information is preserved after dimensionality reduction. Analysis tasks include identifying the optimal number of components required, comparing original and reduced datasets, and observing how PCA improves visualization and simplifies analysis. Common visualizations include scree plots showing variance captured by each component, cumulative variance graphs, and 2D or 3D scatter plots of transformed principal components.
 # 24ADI003_RAMYA-R_24BAD096_EX_8
