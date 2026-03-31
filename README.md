Face Recognition System (SFace + YuNet)
A professional, deep-learning-based facial recognition pipeline optimized for Google Colab. This project leverages modern Neural Networks to achieve high-precision identification with minimal data.

🛠️ Tech Stack
Detection: YuNet (Fast, lightweight DNN with 5-point landmarking).

Recognition: SFace (Generates 128-dimensional facial feature embeddings).

Preprocessing: CLAHE (Contrast adjustment) & Affine Transforms (Alignment).

Matching: Cosine Similarity (Vector-based identity verification).

🚀 Key Features
Drive Integration: Automatically builds a face gallery from subfolders in Google Drive.

Smart Augmentation: Enhances small datasets using horizontal flips and brightness shifts.

Live UI: Custom JavaScript/Python bridge for a "Click-to-Capture" user experience.

Robustness: Aligns faces to correct for head tilts and varying lighting conditions.
