**Titanic Survival Prediction with Decision Trees**

This project utilizes a decision tree classifier to predict passenger survival on the Titanic based on selected features.

**Data:**

The project dataset is "titanic.csv".
Methodology:

**Data Preparation**

Missing age values are filled with the median age.
The 'Cabin' column is removed.
Categorical features ('Sex' and 'Embarked') are one-hot encoded.

**Model Development:**

Data is split into training, development, and test sets.
A decision tree classifier is trained with varying max_depth parameters.
Development set accuracy is used to select the optimal max_depth and avoid overfitting.

**Evaluation:**

The final model (with selected max_depth) is evaluated on the held-out test set.

**Key Findings:**

Optimal max_depth: [Insert the optimal max_depth value based on your results]
Final test accuracy:  0.7988826815642458

