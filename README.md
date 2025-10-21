## Setup and Requirements

**Hardware:** NVIDIA A100 GPU (80GB RAM) via Google Colab  

1. **Prepare data:**
   - Upload all datasets from the google drive
   - Update paths in training/test scripts accordingly

2. **Run training:**
   - There is a simple training section in the google colab notebook

3. **Run Test:**
   - There is a simple test section in the google colab notebook

## Dataset Overview

All datasets are in the google drive folder:
- `ecoli_train_12k.csv` – Training set (12K sequences, 0–80 mutations each)
- `ecoli_val_750.csv` – Validation set (750 sequences, 1 mutation each)
- `ecoli_test_5k.csv` – Test set (5K sequences, 1 mutation each)
- `ecoli_test_low_mutation.csv` – Test set (5K sequences, 0–2 mutations each)

## Google Colab + Model Weights

Full Google Colab notebook with datasets, trained model weights, and step-by-step execution:  
🔗 **[Google Drive Link](#)** _(https://drive.google.com/drive/folders/1IVWtHECFGHJfYsc25GlgKmJBpGX9QNUS?usp=sharing)_

## Results on the basic test set

- **Overall Accuracy:** 94.8%
- **Mutation Accuracy:** 42.5%
- Trained for 15 epochs on 12K sequences