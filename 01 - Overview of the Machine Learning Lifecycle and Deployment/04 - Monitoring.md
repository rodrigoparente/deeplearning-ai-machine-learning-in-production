# Monitoring Dashboards

 - Dashboards are crucial for tracking the performance and health of machine learning systems over time;
 - Different dashboards can monitor various metrics depending on the application;
 - The choice of metrics should be based on potential issues that could arise and statistics that could detect these problems.

# Examples of Metrics to Monitor

 - **Software Metrics:**
    - These include memory usage, compute resources, latency, throughput, server load, and etc;
    - They help ensure the smooth operation of the software surrounding the machine learning system.
    - Many MLOps tools provide these metrics out-of-the-box.
   
 - **Input Metrics:**
    - These include missing values, data volume, feature distribution, correlation, and etc;
    - Monitoring these metrics can help identify shifts in input data that might affect model performance.
   
 - **Output Metrics:**
    - These include confidence levels, error rate (accuracy), class distribution, prediction latency, and etc;
     - These metrics help detect changes in the system's output that might indicate performance degradation.

# Addressing Issues Detected by Monitoring

 - Once key metrics are identified, thresholds should be set to trigger alarms when certain conditions are met;
 - These thresholds can be adjusted over time to ensure they are effectively flagging potential issues;
 - If monitoring reveals a problem, the response will depend on the nature of the issue:
    - **Software Issues:** may require changes to the software implementation (e.g., handling increased server load);
    - **Performance Issues:** could involve updating or retraining the machine learning model.

# Iterative Process

 - Deployment and monitoring should be viewed as iterative processes, similar to the iterative nature of model development;
 - Initial deployment often involves setting up a broad range of metrics, which can be refined over time as the system runs and real data is collected;
 - It may take several iterations to identify the most relevant metrics, and it's common to add or remove metrics based on their usefulness.