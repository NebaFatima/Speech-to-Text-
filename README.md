# Speech-to-Text-Transcripter
A Python-based Speech-to-Text application implemented in Google Colab. Converts audio files into written text using advanced speech recognition models.
This project focuses on improving 'speech recognition accuracy' by applying a denoising step before Automatic Speech Recognition (ASR).  
We evaluate the system on noisy speech samples and analyze improvements in "SNR (Signal-to-Noise Ratio)" and "WER (Word Error Rate)".

# Results
- **Average Noisy SNR**: ~9.4 dB  
- **Average Denoised SNR**: ~4.5 dB  
- **WER Reduction**: Denoising consistently lowers WER (up to **80% improvement** in some samples).  
- Denoised transcriptions align much closer to ground truth compared to noisy inputs.


# Conclusion
Denoising significantly improves **speech intelligibility and ASR performance**, even though raw SNR values drop after processing. This shows that perceptual enhancement matters more for recognition accuracy.

⚙ Requirements
- Python 3.8+  
- NumPy, Pandas, Librosa, PyTorch/TensorFlow 
