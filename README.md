# 🫁 Chest X-ray Disease Classification

This project classifies chest X-ray images into four categories using a deep learning model with transfer learning. It is designed to assist in the detection of respiratory diseases and healthy cases from medical images.

## Dataset

The dataset contains labeled chest X-ray images divided into four classes:
- COVID-19
- Normal (Healthy)
- Pneumonia
- Tuberculosis

The data is split into training, validation, and testing sets for proper model evaluation.

## How to Use

1. Clone this repository.
2. Place the dataset in the appropriate `train/`, `val/`, and `test/` folders.
3. Open the `chest_classification_code.ipynb` notebook in Google Colab or Jupyter and run the cells.

## Requirements

- Python 3.x  
- PyTorch  
- torchvision  
- scikit-learn  
- NumPy  
- Pandas  
- Matplotlib  

Install dependencies:

```bash
pip install torch torchvision scikit-learn numpy pandas matplotlib
```

## Results

| Metric    | Value    |
|-----------|----------|
| Train Accuracy  | 92.16%   |
| Train Loss | 20.89%   |
| Val Accuracy    | 91.90%   |
| val Loss  | 22.12%   |

### If you need the trained model weights (medical_classification.pth), feel free to email me at:
📧 k.prabhav2005@gmail.com
