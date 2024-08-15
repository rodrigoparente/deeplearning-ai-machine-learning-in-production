# Iterative Nature of Machine Learning

 - Machine learning is an iterative process involving model creation, data handling, hyperparameter tuning, training, and error analysis;
 - The loop is repeated multiple times until a good enough model is achieved, followed by a final performance audit before deployment.

# Starting a Machine Learning Project

 - Start with a quick literature search, including online courses, blogs, and open-source projects, to understand what is possible;
 - Prioritize practical, reasonable algorithms over the latest cutting-edge ones, especially when building production systems;
 - Use open-source implementations to quickly establish a baseline, which is often more critical than having the most advanced algorithm.

# Deployment Constraints

 - Early in the project, focus on establishing a baseline rather than worrying about deployment constraints like computational resources;
 - Deployment constraints become relevant once the baseline is established and the project is deemed viable for long-term development and deployment.

# Sanity Checks for Early Stages

 - Before training on the full dataset, run quick sanity checks by overfitting the model on a very small dataset to ensure the model and code are functioning correctly;
 - For complex outputs like speech recognition or image segmentation, ensure the model can accurately process and learn from a single or a small number of training examples;
 - For large datasets, initially train the model on a small subset (e.g., 10-100 images) to identify potential issues before scaling up.

# Error Analysis and Performance Improvement

 - After training the initial model, error analysis is crucial to determine the next steps for improving the model’s performance;
 - The focus should be on understanding and addressing errors to guide further iterations of the model development process.