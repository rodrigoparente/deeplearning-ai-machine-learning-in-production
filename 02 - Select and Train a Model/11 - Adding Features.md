# Challenges in Structured Data Problems

 - Creating new training examples of structured data can be difficult;
 - Instead of generating new examples, focus on enhancing existing training examples by adding useful features.

# Use Case: Restaurant Recommendation System

 - In a restaurant recommendation app, features are created for each user and each restaurant;
 - The learning algorithm (e.g., a neural network) predicts suitable restaurant recommendations for users;
 - Error analysis revealed that vegetarians were often recommended restaurants with only meat options;
 - Instead of synthesizing new user or restaurant examples, adding relevant features can be more effective;
 - Proposed features:
     - **User Feature**: A measure indicating if a user is vegetarian (e.g., percentage of vegetarian orders);
     - **Restaurant Feature**: A feature indicating if the restaurant offers good vegetarian options.

# Data Iteration Process for Structured Data

 - The process of data interation involves:
    - Starting with a model and training it;
    - Conducting error analysis to identify areas for improvement;
    - Proposes new features and repeat the process.
    
# Feature Design vs. End-to-End Learning

 - With deep learning, manual feature design has become less common for unstructured data (e.g., images, audio);
 - However, for structured data, feature design remains important, especially when dataset sizes are not large enough for pure end-to-end deep learning.