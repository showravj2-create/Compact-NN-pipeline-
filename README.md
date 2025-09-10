 (Compact end-to-end neural network demo)
Language: Python (NumPy)
Dataset: sklearn digits (handwritten 8x8 digits)
What it shows:
 - Clean, reproducible code and CLI
 - Mini-batch training, forward/backward implemented from scratch
 - Model & artifacts saved, training plots & confusion matrix
 - Classification report & metadata JSON for reproducibility

How to run:
  git clone <repo>
  cd repo
  python3 -m venv venv && source venv/bin/activate
  pip install -r requirements.txt  # (numpy scikit-learn matplotlib)
  python beautiful_nn.py --epochs 60 --lr 0.01 --hidden 128 --seed 42
