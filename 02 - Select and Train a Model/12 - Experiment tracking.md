# Experiment tracking

 - Robust experiment tracking is essential for efficiently improving algorithms;
 - Helps keep track of numerous experiments, making it easier to make informed decisions regarding data, models, and hyperparameters.


# Key Elements to Track

 - **Algorithm and Code Version:** record the specific algorithm and version of the code used for each experiment for easy replication;
 - **Dataset Used:** keep track of which dataset was employed in each experiment;
 - **Hyperparameters:** document the hyperparameters utilized for each run;
 - **Results:** save results, including high-level metrics (e.g., accuracy, F1 score) and also the trained model.

# Tracking Tools

 - **Text Files:** suitable for small experiments, allowing simple notes for each experiment;
 - **Spreadsheets:** shared spreadsheets can effectively track various parameters for multiple experiments and scale better than text files;
 - **Formal Experiment Tracking Systems:** for larger projects, consider using specialized tools that provide comprehensive tracking capabilities, for example:
    - Weights and Biases;
    - Comet;
    - MLFlow;
    - SageMaker Studio.

# Criteria for Effective Tracking Tools

 - **Replicability:** ensure that the tool captures all necessary information to replicate results;
 - **Result Summary and Analysis:** the tool should provide quick access to experimental results, including summary metrics and detailed analysis;
 - **Resource Monitoring:** track resource usage, such as CPU, GPU, and memory consumption;
 - **Visualization and Error Analysis:** tools that aid in visualizing trained models and conducting in-depth error analysis can be beneficial.
