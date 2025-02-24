# Peptide Toxicity Prediction (Research Project)

This repository contains the code and resources for a research project focused on predicting peptide toxicity using machine learning. Our approach leverages advanced feature extraction techniques and a novel Stack Model to significantly outperform previous methods.

---

## Tech Stack

- **Programming Language:** Python
- **Libraries:** Scikit-learn, TensorFlow

---

## Key Achievements

- **High Accuracy:** Developed an ML-based peptide toxicity prediction model, achieving **98.6% accuracy**, outperforming the ToxIBTL model (**96.0% accuracy**).
- **Improved MCC:** Designed and benchmarked a Stack Model, improving the Matthews Correlation Coefficient (MCC) from **0.921** (ToxIBTL) to **0.970** for peptide datasets.
- **Enhanced Feature Representation:** Utilized feature extraction techniques including **AAC (Amino Acid Composition)**, **DPC (Dipeptide Composition)**, **ProtBERT**, and **ESM** to provide a comprehensive representation of peptide sequences.
- **Robust Data Processing:** Processed and analyzed large-scale biological datasets, with model performance evaluated using **F1-score**, **MCC**, **auROC**, **auPRC**, and **accuracy** metrics.

---

## Results
- **Accuracy:** 98.6%.
- **Model:** Stack Model outperforms the ToxIBTL deep learning model.
- **Evaluation Metrics:** Detailed performance metrics (F1-score, MCC, auROC, auPRC, and accuracy) are provided in the evaluation reports.
