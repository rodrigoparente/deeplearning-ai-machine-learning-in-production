# Key Challenges

 - Machine learning systems consist of both the code (algorithm/model) and the data;
 - Historically, a significant emphasis has been placed on improving the code, with much AI research focusing on finding models that perform well on predefined datasets;
 - In many real-world applications, the algorithm or model may already be a solved problem, with readily available models performing well enough;
 - In such cases, it’s more efficient to focus on improving the data, which is often more customized to the specific problem at hand.

# Iterative Nature of Model Development

 - Model development is a highly iterative process that involves:
    - Starting with an initial model, hyperparameters, and data;
    - Training the model and conducting error analysis;
    - Using the analysis to make informed decisions on how to improve the model, hyperparameters, or data.
 - Iterating through this loop quickly is key to improving model performance, as machine learning is an empirical process.


# Final Steps in Model Development

 - After sufficient iterations and achieving a good model, a final step often involves conducting a richer error analysis;
 - This final audit ensures that the system is functioning as expected before pushing it to production deployment.

# Three Key Milestones in Model Development

 - **Milestone 1:** achieving good performance on the training set;
 - **Milestone 2:** achieving good performance on the cross-validation set, and then the test set;
 - **Milestone 3:** ensuring the model performs well according to business metrics or the project’s goals.
