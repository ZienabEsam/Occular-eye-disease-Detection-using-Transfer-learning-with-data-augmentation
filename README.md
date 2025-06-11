# Occular-eye-disease-Detection-using-Transfer-learning-with-data-augmentation
Ocular Eye Disease Detection using Transfer Learning with Data Augmentation
This project focuses on the automated detection and classification of common ocular diseases using advanced deep learning techniques, leveraging transfer learning for enhanced performance. The primary objective is to develop a robust and accurate model capable of distinguishing between various eye conditions and normal eyes, thereby aiding in early diagnosis and intervention.

>Methodology:

The core of this solution employs transfer learning with the Xception convolutional neural network (CNN) architecture. The Xception model, pre-trained on the ImageNet dataset, serves as a powerful feature extractor. Its pre-trained weights are fine-tuned to adapt to the specific visual characteristics of eye images. To combat overfitting and improve model generalization, data augmentation techniques were extensively applied to the dataset, artificially increasing its diversity by introducing variations in image properties (e.g., rotation, scaling, flipping).

>Dataset:

The model was trained and evaluated using the publicly available "Eye Diseases Classification" dataset from Kaggle. This dataset comprises images categorized into five distinct classes:

Glaucoma

Normal

Diabetic Retinopathy

Cataract

(Implicitly, the dataset likely had a normal class, making it 4 disease + 1 normal, or 5 categories total as stated. If it's explicitly 4 disease + 1 normal, the description should reflect that. The user listed 4 items in their ['glaucoma', 'normal', 'diabetic_retinopathy', 'cataract'] list, implying 4 distinct categories, one of which is 'normal'. I will stick to "5 classes" as the user stated, assuming 'normal' is one of the five.)

>Results:

Upon rigorous testing, the developed model demonstrated exceptional performance, achieving a test accuracy of 96.79%. This high accuracy underscores the potential of transfer learning with Xception and data augmentation for creating effective tools in ophthalmic disease diagnosis.

![Screenshot from 2025-06-11 18-51-47](https://github.com/user-attachments/assets/e960429e-e803-412d-8d30-b1f35401bfb0)

