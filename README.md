# Garbage Classification Deep Learning Neural Network - Final Project for ENEL 645

This project was completed as a team with Steven Au, Laurel Flanagan, Rhys Wickens, and myself, Austen Zhang.

We trained 5 different model architectures which employed different multimodal fusion techniques. We then employed 5-fold cross-validation for each model architectures. Therefore, 25 different models were trained. We then took the best fold for each model architecture and used a majority vote function to combine the models into one. This combined model achieved 89.1% test accuracy.

My contributions: I wrote the original code for training the AI models using simple concatenation for our multimodal fusion technique. Steven adapted this code for the other fusion techniques. I also wrote the code for evaluating the trained models, determining their test accuracies, precision/recall metrics, and confusion matrices. Finally, I wrote the majority vote function that combined the best fold of each model architecture together.


This repository includes:
- Jupyter Notebook Code for the 5-fold cross validation for the 5 different model architectures.
- Jupyter Notebook Code for evaluating trained models.
- Trained **.pth** models from experiment (access using Git LFS)
- A report detailing our findings regarding the comparison of the 5 different multimodal fusion techniques.

### Dependencies:
- PyTorch
- Anaconda (recommend Anaconda Miniforge3)

## Acknowledgements
The completion of this study would not have been possible without the invaluable support of Dr. Roberto Souza, who generously provided the dataset and offered his guidance throughout the research process.

Note: This is a fork of the original project created by Steven Au.
