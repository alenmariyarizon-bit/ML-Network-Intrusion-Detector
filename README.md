# ML Network Intrusion Detector

## Project Overview
This project uses machine learning to classify network traffic as normal or potentially malicious. It uses a Random Forest Classifier trained on the UNSW-NB15 dataset.

## Objectives
- Explore network traffic data.
- Prepare categorical and numerical features for machine learning.
- Train a Random Forest classification model.
- Evaluate the model using accuracy, precision, recall, F1-score, and a confusion matrix.

## Technologies Used
- Python
- Pandas and NumPy
- Scikit-learn
- Matplotlib and Seaborn
- Jupyter Notebook

## Dataset
UNSW-NB15 network intrusion dataset. The project uses the training CSV file containing 175,341 records and 45 columns.

Dataset source: [Hugging Face — UNSW-NB15](https://huggingface.co/datasets/Mouwiya/UNSW-NB15)

## Model
Random Forest Classifier with 100 trees, using an 80/20 stratified train-test split.

## Evaluation
The model achieved **95.61% accuracy** on the held-out test split. See `results/evaluation_results.json` and the notebook for the full evaluation metrics.

## Limitations
This is an educational experiment using a public dataset. Performance on this test split does not guarantee performance on live network traffic or previously unseen attack types. The model is not a production-ready security system.

## How to Run
1. Install Python 3.13.
2. Create and activate a virtual environment.
3. Install dependencies with `pip install -r requirements.txt`.
4. Open `ML_Network_Intrusion_Detector.ipynb` in VS Code.
5. Run the notebook cells in order.

## Author
Add your name here.
