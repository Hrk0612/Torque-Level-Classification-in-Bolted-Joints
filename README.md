# Torque-Level-Classification-in-Bolted-Joints
🔩 Torque Level Classification in Bolted Joints Using Machine Learning

Duration: May 2025 – Jul 2025 | Institution: NIT Trichy

📘 Project Overview

This project focuses on developing a machine learning–based framework to classify torque levels in bolted joints using Acoustic Emission (AE) signals for Structural Health Monitoring (SHM) applications. The goal was to detect bolt loosening conditions and assess the mechanical integrity of structures under varying torque loads.

⚙️ Key Highlights

Data Processing: Processed and analyzed 3M+ high-frequency AE time-series samples (5 MHz, 7 torque levels × 5 campaigns) using Python, NumPy, Pandas, and PyWavelets.

Signal Analysis: Applied wavelet-based denoising, thresholding, and bandpass filtering to enhance signal quality and extract relevant vibration patterns.

Feature Engineering: Extracted 10+ time–frequency domain features (RMS, kurtosis, FFT spectral centroid, band energy, entropy) to transform raw AE signals (~1.2 M samples/sec) into compact, structured data windows (~100 K).

Model Development: Trained and optimized SVM, Random Forest, and XGBoost classifiers for torque level prediction, achieving up to 92% accuracy in bolt loosening detection.

Model Interpretability: Evaluated results using confusion matrices, feature importance plots, and classification reports to ensure model transparency and robustness.

📊 Tools & Technologies

Python · NumPy · Pandas · PyWavelets · Scikit-learn · Matplotlib · Seaborn

🚀 Outcomes

Demonstrated the potential of data-driven SHM for predictive maintenance in mechanical assemblies.

Achieved a 92% classification accuracy while significantly reducing raw signal dimensionality.

Established a scalable signal processing pipeline applicable to other vibration-based fault detection systems.
