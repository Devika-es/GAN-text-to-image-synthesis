Text-to-Image Synthesis using GANs and NLP
Technologies Used: Python, TensorFlow, PyTorch, GANs (Generative Adversarial Networks), Natural Language Processing (NLP), OpenCV, NumPy, Pandas

Project Overview:
Developed a text-to-image synthesis model that converts descriptive textual data into facial images of celebrities using Generative Adversarial Networks (GANs). The project leveraged Natural Language Processing (NLP) techniques to process and interpret textual descriptions from a CSV dataset containing facial attributes. These descriptions were then mapped to generate corresponding images using a trained GAN model.

Key Features & Methodology:
Data Processing:
Used a celebrity facial attributes dataset (CelebA or similar) containing structured descriptions of facial features.
Cleaned and tokenized the text descriptions using NLP techniques (TF-IDF, word embeddings).

NLP Model for Feature Extraction:
Converted textual descriptions into vector representations using word embeddings (Word2Vec, GloVe, or BERT).
Mapped text features to corresponding facial attributes.

GAN-based Image Generation:
Implemented Conditional GANs (cGANs) or StackGAN for controlled image synthesis.
Trained the generator to synthesize realistic facial images conditioned on the extracted text embeddings.
Used a discriminator to evaluate the realism of generated images and improve training quality.

Model Evaluation & Optimization:
Tuned hyperparameters and improved image sharpness using progressive growing GAN techniques.

Results & Impact:
was not successfull generated high-resolution facial images that matched the given textual descriptions.
because of memory constraints


