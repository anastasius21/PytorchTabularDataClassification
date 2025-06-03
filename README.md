# Tabular Data Classification using PyTorch

This project builds a deep learning classifier using PyTorch to classify rice types based on physical attributes from a structured CSV dataset.

## Project Highlights

- Cleaned and normalized a rice classification dataset
- Custom PyTorch Dataset class for scalable data loading
- Deep learning model trained with train/validation/test splits
- Performance tracked using accuracy and loss metrics
- Final evaluation on unseen test data

## Dataset

The dataset contains several numerical features for different rice grains, with the target being the type/class of rice.

- Columns: Numerical attributes of rice grains
- Target: Class column indicating rice type

## Model Architecture

- Fully connected feedforward neural network
- Binary classification with BCEWithLogitsLoss


## Results

- Real-time accuracy and loss tracking over 10 epochs
- Final test accuracy printed at the end of training

## Libraries Used

- PyTorch
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
