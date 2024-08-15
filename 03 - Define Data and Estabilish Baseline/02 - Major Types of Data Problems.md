# Major Type of Data Problems

 - Usually the problems are related to the data type and size;
 - To better understand the problems and its solutions, lets define a framework to categorize different types of machine learning projects based on data characteristics;
 - For the categorization, lets consider a 2 by 2 matrix:
    - **Data Type:** Unstructured vs. structured data;
    - **Dataset Size:** Small (less than 10,000 examples) vs. large (more than 10,000 examples).

# Unstructured vs. Structured Data

**Unstructured Data**

 - Includes images, audio, and text;
 - Humans excel at processing this type of data;
 - **Example:** training a visual inspection model with images of smartphones.

**Structured Data**

 - Comprises database records with real-valued features;
 - More challenging for humans to process effectively;
 - **Example:** predicting housing prices from a structured dataset.

# Small vs. Large Datasets

**Small Datasets (e.g., 100 to 1,000 examples)**

 - Clean labels are critical, because a single mislabeled example can significantly affect the dataset;
 - Easier for small teams to review and correct labels manually.

**Large Datasets (e.g., over 10,000 examples)**
 
 - It is more challenging to manually review large datasets, which makes the processes for data collection and labeling crucial;
 - The focus shifts to setting up efficient data processes and clear labeling guidelines.

# Data Augmentation

 - Helpful for unstructured data problems (e.g., generating new images or audio);
 - More difficult for structured data problems due to the limited number of real-world instances (e.g., few houses, limited users).

# Labeling Considerations

 - Clean and consistent labeling is crucial for small datasets;
 - For large datasets, establishing a consistent labeling process and instructions for a large team is necessary;
 - Human labeling can be ambiguous, particularly for structured data, affecting the quality of labels.

# Generalization of Best Practices

 - Advice and strategies are often more applicable within the same quadrant of the framework;
 - Professionals with experience in a specific quadrant adapt more quickly to related problems;
 - Acknowledgment that machine learning is diverse; one-size-fits-all advice may not be effective.