# Malaria Detection Using Deep Learning

A deep learning project for automated malaria detection from thin blood smear microscopy images. The model classifies cell images as **Parasitized** (infected) or **Uninfected** using convolutional neural networks built with TensorFlow/Keras.

## Dataset

This project uses the [NIH Malaria Cell Images Dataset](https://www.kaggle.com/datasets/iarunava/cell-images-for-detecting-malaria), which contains 27,558 cell images with equal instances of parasitized and uninfected cells.

- **Parasitized**: Cells infected with P. falciparum malaria parasite
- **Uninfected**: Healthy red blood cells

## Project Structure

```
malaria-detection-deep-learning/
├── notebooks/          # Jupyter notebooks for experiments and analysis
├── src/                # Reusable Python modules (data loading, model, utils)
├── data/               # Dataset (not tracked by git -- download separately)
├── models/             # Saved model weights and checkpoints
├── results/            # Output figures, metrics, and evaluation results
├── requirements.txt    # Python dependencies
├── .gitignore
└── README.md
```

## Setup

### 1. Clone the repository

```bash
git clone https://github.com/Yalemu12/malaria-detection-deep-learning.git
cd malaria-detection-deep-learning
```

### 2. Create a virtual environment

```bash
python3.12 -m venv venv
source venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Download the dataset

Download the dataset from [Kaggle](https://www.kaggle.com/datasets/iarunava/cell-images-for-detecting-malaria) and extract it into the `data/` directory:

```
data/
├── Parasitized/
└── Uninfected/
```

## Tech Stack

- **Python 3.12**
- **TensorFlow 2.20** / Keras
- **NumPy** / **Pandas** -- data manipulation
- **Matplotlib** / **Seaborn** -- visualization
- **scikit-learn** -- metrics and evaluation
- **OpenCV** -- image preprocessing

## Contributions

This project is being built incrementally. Progress is tracked through commits:

| Date | Milestone |
|------|-----------|
| Feb 2026 | Project setup, environment configuration |

## License

This project is for educational and research purposes.
