This folder contains the Jupyter/Google Colab notebooks used in the development and evaluation of the نبـرة (Nabra) project for Arabic speech-based anxiety-related vocal pattern analysis.

The notebooks include data preprocessing, feature extraction, model training, fine-tuning, and evaluation experiments using both deep learning and Transformer-based approaches.

Included Notebooks

1. BAVED Deep Learning Models

This notebook contains the implementation and training of multiple deep learning and machine learning models using the BAVED dataset, including:
	•	CNN
	•	LSTM
	•	BiLSTM
	•	CNN–LSTM Hybrid
	•	SVM
	•	K-Means Clustering

The notebook also includes:
	•	Audio preprocessing
	•	Data augmentation
	•	Log-Mel Spectrogram extraction
	•	Model evaluation
	•	Confusion matrix analysis

2. Wav2Vec2 and HuBERT Models

This notebook contains the implementation and fine-tuning of Transformer-based speech models, including:
	•	Wav2Vec2
	•	HuBERT

The models were trained using raw Arabic speech waveforms to improve contextual speech representation learning and emotional speech analysis performance.

Technologies and Libraries Used
	•	Python
	•	Google Colab
	•	TensorFlow / Keras
	•	PyTorch
	•	Librosa
	•	Scikit-learn
	•	Hugging Face Transformers
	•	NumPy
	•	Pandas
	•	Matplotlib

Purpose

The notebooks were developed to analyse Arabic speech signals and identify vocal intensity patterns associated with stress and anxiety-related speech characteristics using artificial intelligence and speech processing techniques.
