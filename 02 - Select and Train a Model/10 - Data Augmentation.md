# Data Augmentation

 - Data augmentation is a valuable technique to generate more data, particularly for unstructured data types like images, audio, and text;
 - Designing an effective data augmentation setup requires careful consideration of various parameters.

**Goal**
 
 - Create realistic examples that (i) the algorithm does poorly on, but (ii) humans (or other baseline) do well on.

**Checklist**

 - Does it sound realistic?
 - Is the mapping $x \rightarrow y$ clear?
 - Is the algorithm currently doing poorly on it?

# Examples of Data Augmentation

 - In speech recognition, you can start with an audio clip and add background noise to generate synthetic audio examples;
 - In computer vision, you can enhance your data by creating a mirror image of the original picture or adjusting the brightness to make the image either brighter or darker.

Generative Adversarial Networks (GANs) can also be userd to synthesize realistic examples but may be overly complex for simple augmentation needs.
  
# Data Iteration Loop

 - Instead of a model iteration loop, consider a data iteration loop:
     - Train the model, conduct error analysis, and focus on improving data quality and quantity;
     - This approach can lead to quicker improvements in algorithm performance, especially in unstructured data problems.

# Impact on Learning Algorithm Performance

 - Generally, adding accurately labeled data does not hurt performance, especially for unstructured data problems;
 - This is true when:
    - The model is large (e.g., a neural network with high capacity and low bias);
    - The mapping from input (x) to output (y) is clear (humans can make accurate predictions based on x).
  - If the model is small, an imbalanced training set may cause the model to focus too much on one class, harming performance on others;
  - If the mapping from input to output is unclear (e.g., ambiguous examples), this can cause issues as well.