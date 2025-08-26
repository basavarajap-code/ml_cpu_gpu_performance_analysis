# CPU & GPU Performance Analysis using Machine Learning

This project analyzes the evolution and performance trends of CPUs and GPUs using real-world chip datasets from Kaggle.

## Dataset
- https://www.kaggle.com/datasets/michaelbryantds/cpu-and-gpu-product-data
- Dataset contains 2,185 CPUs and 2,668 GPUs across different vendors.

## Project Highlights
- Applied PCA for dimensionality reduction and visualization.
- Built two supervised models:
  - Logistic Regression: Predicts chip vendor (Intel, AMD, NVIDIA).
  - Random Forest Classifier: Classifies product as CPU or GPU.
- Developed detailed EDA plots for process size, TDP, die size, transistor count, and frequency trends.

## Tools and Libraries
- Python, scikit-learn, pandas, matplotlib, seaborn
- Google Colab

## Code
ML_MODEL_CPU_GPU_PERF_ANALYSIS.ipynb //Run in Google Colab

## Report
Find the full project report in the repository (PDF included).

## Insights
- Evidence of Moore's Law and breakdown of Dennard scaling.
- Transistor counts have continued to grow, consistent with Moore’s Law, but frequency has plateaued — indicating the breakdown of Dennard scaling.
- TDP (power consumption) has increased significantly for GPUs, showing their shift toward high-performance parallel processing.
- Vendors follow different design philosophies: Intel tends to optimize frequency and power, while AMD and NVIDIA often push transistor counts and die sizes.
- PCA visualizations clearly showed that CPUs and GPUs are well-separated in feature space, confirming that chip characteristics naturally distinguish them.
- Both supervised models performed well, demonstrating that hardware characteristics can be used to reliably to predict both vendor and chip type.

---
