# Audiobook-Customer-Re-purchase-Prediction

Description: Developed a neural network model to predict whether an audiobook customer would make a repeat purchase based on behavioral and transactional data. The project aimed to identify high-conversion users for targeted marketing and customer retention.

Loaded and preprocessed raw audiobook customer data using NumPy and scikit-learn, performing data balancing, shuffling, and feature standardization to ensure model reliability.

Split data into training, validation, and testing sets, and saved processed subsets as .npz files for efficient reuse.

Built a Sequential Neural Network in TensorFlow/Keras using dense layers with dropout for regularization to prevent overfitting.

Trained the model with early stopping based on validation loss to optimize performance and generalization.

Evaluated model accuracy on a held-out test set, achieving 91% test accuracy in predicting customer re-purchases.

Provided actionable insights for marketing optimization by identifying customers most likely to buy again.

Tech Stack: Python, TensorFlow, Keras, scikit-learn, NumPy, Google Colab
