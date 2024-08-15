# Human Level Performance (HLP) in Machine Learning

 - HLP serves as a benchmark for estimating baseline performance and irreducible error in machine learning tasks;
 - In academia, surpassing HLP can validate the significance of research and assist in publishing papers;
 - HLP is also useful for guiding businesses in setting achievable accuracy targets based on real-world human performance;
 - However, HLP can help set realistic accuracy goals for machine learning systems by comparing them to human performance.

# Cautions With HLP

 - If labelers have conflicting instructions, it can skew HLP measurements, for example:
    - if 70% of labelers choose one labeling convention and 30% choose another, the chance of two labelers agreeing might be inaccurately represented as HLP, leading to an inflated perception of a model’s performance;
 - In this scenario, achieving high average test accuracy does not guarantee that a machine learning system performs better;
 - In fact, the model may be performing better because it has been able to capture the distribution of the data more effectively;
 - This can mask the model's weaknesses in other areas, potentially leading to poorer overall performance.

# Ground Truth Definition

 - When the ground truth is externally defined (e.g., from medical tests like biopsies), HLP is a useful metric for estimating errors and understanding model performance;
 - Conversely, when ground truth is defined by human labelers, HLP merely measures the agreement between human judgments, which may not accurately reflect the true performance of a model.

# Raising HLP 

 - Instead of focusing on beating HLP, improving labeling consistency can raise HLP scores;
 - While raising HLP may make it challenging for models to surpass this benchmark, it ultimately results in cleaner data, improving machine learning performance.

# Key Considerations

 - Use HLP to inform error analysis and prioritize enhancements instead of strictly comparing machine learning systems to human performance;
 - Prioritize improving label consistency to raise HLP, leading to better learning outcomes and more effective applications.