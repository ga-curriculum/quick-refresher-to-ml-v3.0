<h1>
  <span class="headline">Quick Refresher for ML</span>
  <span class="subhead">Machine Learning Overview</span>
</h1>

Learning Objective
-------------------------
By the end of this lesson, you will be able to:
- Define machine learning.
- Explain the three primary types of machine learning: supervised, unsupervised, and reinforcement learning. 
- Understand their core distinctions and common business applications.

What is Machine Learning?
-------------------------

Machine learning (ML) is a subset of artificial intelligence (AI) that enables systems to learn from data and make predictions or decisions without being explicitly programmed. Instead of relying on hard-coded rules, ML systems identify patterns in data to generate insights and automate decision-making.

✅ **Traditional programming**: Rules + Data → Output\
✅ **Machine learning**: Data + Output → Model (learned rules)

<div class="mermaid">
graph TD
    A[Data] -->|Train| B(Model)
    B -->|Predict| C[Output]
</div>

Types of Machine Learning
-------------------------

### 1\. Supervised Learning

-   The model is trained on labeled data, meaning the input data is paired with the correct output.
-   The goal is to learn a mapping from inputs to outputs, enabling the model to predict outcomes for new data.

**Common Algorithms:** Linear Regression, Decision Trees, XGBoost

**Business Applications:**

-   Predicting customer churn
-   Credit scoring
-   Demand forecasting
-   Email spam detection

**Key Distinction:** The desired outcome is known in advance and explicitly labeled in the data.

<div class="mermaid">
graph LR
    A[Input Data + Labels] -->|Train| B(Model)
    B -->|Predict| C[New Data -> Prediction]

</div>

* * * * *

### 2\. Unsupervised Learning


-   In unsupervised learning, the model is trained on unlabeled data and discovers patterns, groupings, or structures without predefined outcomes.

**Common Algorithms:** K-Means Clustering, Principal Component Analysis (PCA)

**Business Applications:**

-   Customer segmentation
-   Anomaly detection (e.g., fraud detection)
-   Market basket analysis (product recommendations based on purchase behavior)

**Key Distinction:** There is no predefined outcome; the goal is to uncover hidden patterns.

<div class="mermaid">
graph TD
    A[Input Data] -->|Find Patterns| B[Clusters/Groups]

</div>

* * * * *

### 3\. Reinforcement Learning

-   In reinforcement learning, an agent learns through trial and error by interacting with an environment and receiving feedback in the form of rewards or penalties.

**Common Algorithms:** Q-Learning, Policy-Based Methods

**Business Applications:**

-   Robotics (e.g., autonomous vehicles, warehouse automation)
-   Dynamic pricing
-   Recommendation systems that adapt based on user behavior
-   Game playing (e.g., AlphaGo)

**Key Distinction:** Learning is driven by interaction and feedback, with a focus on maximizing long-term rewards rather than immediate accuracy.

<div class="mermaid">
graph TD
    A[Agent] -->|Takes Action| B[Environment]
    B -->|Provides Feedback| A

</div>

Summary Table
-------------

| Type | Data Input | Goal | Example Application |
| --- | --- | --- | --- |
| Supervised Learning | Labeled data | Predict known outcomes | Predicting loan defaults |
| Unsupervised Learning | Unlabeled data | Identify patterns or groupings | Customer segmentation |
| Reinforcement Learning | Environment feedback | Maximize cumulative reward over time | Optimizing supply chain logistics |

Key Takeaways for Business
--------------------------

-   **Supervised Learning:** Best suited for prediction tasks when historical data with known outcomes is available.
-   **Unsupervised Learning:** Useful exploring data to uncover hidden patterns, segments, or anomalies.
-   **Reinforcement Learning:** Ideal for sequential decision-making in dynamic environments where outcomes evolve over time.
