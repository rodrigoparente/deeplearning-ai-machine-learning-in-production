# Importance of Context in Machine Learning Performance

 - A machine learning system might show low average test set error yet fail in critical scenarios, making it unsuitable for production deployment.
 - For example, high average test accuracy can show poor performance in production because:
   - The machine learning model displays bias/discrimination based on certain attributes.
    - The machine learning model classifies everything as negative because the training set was highly unbalanced.
 - Analysis of key slices of data is essential to detect and address such issues.
 - Average test set accuracy might hide significant errors in rare classes, which are crucial in certain applications.

# Real-World Machine Learning Deployment

 - Engineers tend to focus solely on test set performance, overlooking the real-world applicability of the model.
 - If you face a problem of high average test accuracy but poor performance in production:
    - Don’t get defensive if the model’s test set performance is questioned in practical applications.
    - Strive to build models that meet the actual business needs, not just perform well on the test set.
