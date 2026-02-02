##Car Brand Classification using Transfer Learning
#Project Overview
Architected an end-to-end computer vision pipeline to classify automotive brands from high-resolution images. By leveraging Transfer Learning and a ResNet-50 architecture, this project demonstrates the ability to handle large-scale image data and optimize deep learning models for real-world environmental noise.

#Key Features & Impact
- Engineered a robust classification model using PyTorch, achieving a 14% increase in decision accuracy (81% total) over baseline threshold methods.
- Processed a dataset of 8,000+ images from the Stanford Car Dataset, implementing custom preprocessing scripts for tag extraction and metadata normalization.
- Optimized training efficiency by utilizing ImageNet normalization and advanced image augmentation techniques (CenterCrop, ColorJitter) to enhance model generalization.
- Developed a modular codebase for data ingestion, model tuning, and evaluation, ensuring scalability for future automotive computer vision applications.

#Technical Stack
- Language: Python
- Frameworks: PyTorch, Torchvision
- Libraries: Pandas (Data manipulation), NumPy (Numerical analysis), Matplotlib (Visualization), PIL (Image processing)
- Model Architecture: ResNet-50

#Dataset Information
The model was trained and validated using the Stanford Car Dataset, which includes:
- 8,000+ Training Images across diverse car brands and models.
- 8,000+ Testing Images for rigorous performance evaluation.
- Preprocessing: Images were normalized to ImageNet standards and cropped to 224x224 pixels for optimal ResNet-50 compatibility
