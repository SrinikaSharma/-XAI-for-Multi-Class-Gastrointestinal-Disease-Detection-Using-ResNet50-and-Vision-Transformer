# -XAI-for-Multi-Class-Gastrointestinal-Disease-Detection-Using-ResNet50-and-Vision-Transformer

Developed a deep learning pipeline for the detection and classification of gastrointestinal diseases using the Kvasir dataset. Used ResNet50 for hierarchical feature extraction and Vision Transformer (ViT) for attention based feature representation. 
Integrated Grad-CAM (XAI method) to visualize critical regions in medical images influencing classification decisions.
Utilized the Kvasir dataset consisting of 4,000 endoscopic images across 8 classes. Preprocessed the dataset with data augmentation techniques like random flips, rotations, color jitter.
Implemented a hybrid ResNet50 and Vision Transformer architecture
Generated class activation maps to visualize key regions influencing predictions, assisting in model validation using Grad-CAM.
Delivered a deployable model achieving 90% accuracy with explainability features that provide clinicians with visual justifications for predictions.
