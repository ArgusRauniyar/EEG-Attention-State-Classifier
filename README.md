# EEG-Attention-State-Classifier

**DESCRIPTION**
- This machine learning project distinguishes between relaxed and concentrated mental states using EEG data from multiple subjects through the usage of "internal Attention Study" dataset available from OpenNeuro. The pipeline includes classification with cross-validation to demonstrate ways in which EEG can be used for cognitive state monitoring. 

**Dataset**
- Arnaud Delorme and Dean Radin (2021). Internal attention study. OpenNeuro. [Dataset] doi: 10.18112/openneuro.ds002691.v1.1.0
URL: https://openneuro.org/datasets/ds002691/versions/1.1.0/file-display/participants.json

**Method**
- Install dependencies: set up Python environment with required packages (e.g., mne, scikit-learn, numpy).
- Load and label datasets: import EEG data and assign class labels.
- Preprocessing:
    -Filter EEG signals.
    -Extract bandpowers (e.g., delta, theta, alpha, beta).
- Event extraction: identify experimental events from dataset annotations.
- Epoching: segment EEG data into epochs aligned with events.
- Feature extraction: compute statistical and frequency-based features from epochs.
- Model pipelines: build machine learning pipelines (Random Forest, SVM, Logistic Regression).
- Ensemble learning: combine models using soft voting.
- Cross-validation: evaluate ensemble perform**ance using stratified k-fold cross-validation.
  


Note:
This is a part of a work in progress, further arrangements of data and classifying algorithms could be applied to yeild a higher accuracy
