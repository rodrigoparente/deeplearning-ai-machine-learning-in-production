# Obtain Data

 - Machine learning is an iterative process involving model selection, hyperparameter tuning, data set preparation, training, and error analysis;
 - Prioritize getting into the iteration loop quickly rather than spending excessive time collecting data upfront;
 - The exception is when working on a problem you've encountered before and know the minimum data size required;
 - In that case, it may be worth investing more time upfront to collect sufficient data.

# Data Source Inventory

 - Take an inventory of possible data sources, considering the cost, time, and quality:
     - **Owned data:** no additional cost, instantly available;
     - **Crowdsourced data:** requires setup and integration, may take weeks to execute;
     - **Unlabeled data:** can be labeled, but at a higher cost than crowdsourcing;
     - **Commercial data purchase:** may involve quick processes like purchase orders;
 - Evaluate each option based on financial cost, time cost, data quality, and regulatory constraints.

# Labeling Strategies

 - There are three main ways to label data:
    - **In-house**: machine learning engineers may label data initially to build intuition, though this is expensive and not scalable;
    - **Outsourcing**: specialized companies may provide efficient labeling, especially for complex tasks;
    - **Crowdsourcing**: useful for tasks that don't require specialized knowledge, such as transcribing speech for speech recognition.

# Dataset Expansion

 - Begin with smaller increases (e.g., from 1,000 to 3,000 examples) to gauge the impact on model performance;
 - Use incremental increases (e.g., 10% or 2x) for more predictable outcomes and to avoid over-investing in unnecessary data collection.

# Transition to Data Pipelines

 - Once data collection is underway, focus on building efficient data pipelines to manage and process data as it becomes available;
 - Pipelines help automate and streamline the processing steps, essential for handling continuous data influx.