# Machine-Learning

ML A-Z course (Udemy) - Python

## Feature Scaling

- Do not apply feature scaling to dummy variables resulting from OneHotEncoding
- Do not apply feature scaling to dependent variable when values are in binary form (1, 0), because values are already in right range
- When Dependent variables values are high with respect to other features, apply feature scaling to dependent variable and all the features to bring into same range
- When the dataset is to split into test set & train set, the feature scaling is applied to train set only
- Convert X or y data from array into 2D format array as StandardScaler from sklearn.preprocessing method fit_transform input requires data in 2D format

Note:: Inverse Feature scaling or transformation to view predicted results
