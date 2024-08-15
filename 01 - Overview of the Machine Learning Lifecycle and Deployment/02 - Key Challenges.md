# Key Challenges in Deploying Machine Learning Models

There are two categories of problems while deploying machine learning models, which are: statistical issues, and software engineering issues.

**Machine Learning Issues**

 - **Concept Drift**: changes in the relationship between input \(x\) and output \(y\);
 - **Data Drift**: changes in the distribution of input \(x\);
 - **Examples**:
   - Changes in speech data (e.g., new microphones in smartphoness);
   - Sudden data shifts in online payment (e.g., during COVID-19).

**Software Engineering Issues**

 - **Real-Time vs. Batch Predictions:**
   - Real-time (e.g., speech recognition);
   - Batch processing (e.g., patient record analysis).
 - **Deployment Location:**
   - Cloud vs. Edge vs. Web Browser.
 - **Resource Considerations:**
   - CPU/GPU availability and memory requirements.
 - **Latency and Throughput:**
   - Meeting specific performance metrics (e.g., queries per second).
 - **Logging:**
   - Capturing data for analysis and retraining.
 - **Security and Privacy:**
   - Tailoring to the sensitivity of the data (e.g., patient records).