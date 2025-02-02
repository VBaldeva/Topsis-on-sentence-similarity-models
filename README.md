# Topsis-on-sentence-similarity-models

## Overview

This project applies the TOPSIS (Technique for Order of Preference by Similarity to Ideal Solution) method to rank Sentence Transformer models based on their ability to measure text similarity. Various linguistic and statistical metrics are considered to evaluate model performance systematically.

## Methodology

🔍 Metrics Used for Evaluation:

Cosine Similarity – Measures vector space similarity.

Mean Squared Error (MSE) – Measures prediction accuracy.

Mean Absolute Error (MAE) – Evaluates deviation from true values.

Correlation – Checks alignment with human-annotated similarity scores.

Speed – Measures encoding efficiency.

Model Size – Computes memory footprint.

⚙️ Steps Involved:

Load Evaluation Data – Uses an inbuilt dataset from GLUE benchmark (no additional dataset file needed).

Evaluate Models – Computes similarity metrics for different models.

Apply TOPSIS – Ranks models based on an ideal similarity scoring framework.

Generate Visualizations – Displays ranking results and performance comparisons.

📌 Model Evaluation:

Uses multiple Sentence Transformer models.

Computes similarity scores for 100 sentence pairs from the GLUE STS-B dataset.

Measures performance using MSE, MAE, correlation, speed, and model size.

🏆 Ranking with TOPSIS:

Normalizes evaluation metrics.

Assigns weights to different criteria.

Computes TOPSIS Score and ranks models accordingly.

Results 📊

The complete results, including rankings and performance comparisons, are saved in:

[Results](./Results.png)
