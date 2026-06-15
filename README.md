# Breast Cancer Detection ML Model

A binary classification machine learning project using 30 cellular features from fine-needle aspirates to distinguish between malignant and benign breast cancer tumors. The validated model achieves high accuracy on unseen data for reliable diagnostic predictions.

## Project Overview
This repository hosts an end-to-end analytical notebook that models tumor malignancy based on tissue sample metrics. The diagnostic pipeline explores clinical measurements, sets baseline feature relationships, splits properties into rigorous validation segments, and yields a real-time prediction framework for evaluating standalone medical profiles.

## Dataset Characteristics
The analysis handles standard physiological measurements derived directly from cell nuclei images collected via fine-needle aspirates (FNA).
* **Sample Scope:** 569 patient profiles.
* **Feature Scope:** 30 continuous mathematical metrics representing architectural dimensions, including tumor cell radius, texture standard deviations, perimeter, surface area, smoothness variations, structural compactness, and contour concavity severity.
* **Target Diagnostic Categories:**
  * **Malignant:** Presenting indicators of clinical cancer growth.
  * **Benign:** Representing stable, non-cancerous mass formations.

## Diagnostic Workflow
1. **Exploratory Distribution Review:** Examined complete data sizing, categorical ratios, missing indicators, and target class distributions to safeguard balance stability.
2. **Feature Allocation:** Partitioned morphological attributes from structural target fields to secure clean matrix tracking.
3. **Data Splitting & Isolation:** Segmented the data footprint into standalone training records and validation partitions to block baseline predictive leaking.
4. **Model Architecture Training:** Fitted a binary mathematical classifier against training attributes to map separating borders across data classes.
5. **Validation Testing:** Recorded objective diagnostic metrics across both known learning profiles and unseen test matrices to gauge realistic classification reliability.
6. **Predictive System Assembly:** Constructed a standalone prediction interface that receives raw single-patient cellular data structures and delivers a discrete diagnostic classification output.
