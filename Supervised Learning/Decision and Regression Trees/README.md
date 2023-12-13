# Decision and Regression Trees
![Decision Tree Image](Decision-Tree.png)

# Decision and Regression Trees for Classifying and Predicting Vehicle Fuel Types

This project delves into the use of Decision Trees and Regression Trees for classifying and predicting vehicle fuel types based on fuel consumption and CO2 emissions metrics. The goal is to unravel the complex relationship between these variables and their influence on fuel type determination.

## Dataset Overview

The dataset encompasses various vehicle attributes, with a particular focus on:

- `Fuel Consumption` (City, Hwy, and Combined)
- `CO2 Emissions`
- `Fuel Type`

## Decision and Regression Trees: An Overview

### Decision Trees

Decision Trees are a type of supervised learning algorithm predominantly used for classification tasks. They work by repeatedly splitting the data based on certain criteria, forming a tree-like model of decisions.

#### How They Work:
1. **Node Splitting**: Starts with the entire dataset at the root and splits it based on a feature that results in the most significant information gain.
2. **Tree Construction**: Continues splitting at each node, forming branches, until a stopping criterion (like `max_depth`) is reached.
3. **Classification**: Each leaf node represents a class, determined by the majority of data points that reach that leaf.

### Regression Trees

Regression Trees are similar in structure to Decision Trees but are used for predicting continuous values (like fuel consumption).

#### Working Mechanism:
1. **Splitting Criteria**: Unlike classification, splits are made based on minimizing the variance of the target variable within each node.
2. **Predicting Outcomes**: Each leaf node in a Regression Tree represents an average value of the target variable for data points within that node.

### Implementation

Implemented in Python, the project utilizes libraries such as:
- `scikit-learn` for building and evaluating the tree models.
- `Pandas` for data manipulation.
- `Matplotlib` and `Seaborn` for visualizing data and model outputs.

### Key Insights

- **Decision Tree Analysis**: Provides a clear and intuitive understanding of the decision-making process for classifying fuel types.
- **Regression Tree Insights**: Offers valuable predictions and insights into the continuous relationships between variables like fuel consumption and CO2 emissions.

---

For a comprehensive look at the methodologies, implementations, and results, refer to the Jupyter notebook in this repository.

