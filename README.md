# Leaf-Disease-Detection
Overview:
Leaf diseases in plants can significantly impact agricultural productivity and crop yield. Early detection and intervention are crucial for preventing the spread of these diseases. This project employs two powerful deep learning approaches: Convolutional Neural Networks (CNN) and Vision Transformers (ViT) to automate the detection and classification of leaf diseases in plants. By implementing these models, we have achieved remarkable accuracies of 95.5% with CNN and 96.2% with ViT, identifying various leaf diseases across 38 different classes.

Dataset:
Our models were trained on a comprehensive dataset comprising 54,000 high-resolution images of plant leaves, split into training, validation, and test sets. This dataset covers a wide range of plant species and includes various common leaf diseases, providing a diverse and challenging environment for training both the CNN and ViT models. The dataset is available at https://github.com/spMohanty/PlantVillage-Dataset

Methodology:

CNN Model: We implemented a Convolutional Neural Network architecture, a well-established deep learning approach optimized for image recognition tasks. The CNN model was trained on the dataset with the help of data augmentation techniques to increase its robustness and generalization ability. The model demonstrated a remarkable accuracy of 95.5% in identifying leaf diseases.

ViT Model: Using the vit-keras library, we implemented a Vision Transformer (ViT) architecture, a cutting-edge deep learning model originally designed for natural language processing tasks but adapted for computer vision. The ViT model was pretrained and fine-tuned on our dataset, achieving an impressive accuracy rate of 96.2% in leaf disease classification.

Key Features:

High Accuracy: Our CNN model achieved an accuracy rate of 95.5%, while our Vision Transformer (ViT) model reached 96.2% accuracy in identifying leaf diseases. These models provide robust and accurate disease detection, benefiting farmers and agricultural experts.
Real-time Processing: Both models are capable of processing images in real-time, enabling quick and timely disease detection.
Multi-Class Classification: The models can classify leaves into 38 different disease categories, providing precise insights into the specific ailment affecting the plant.
User-Friendly Interface: We have developed a user-friendly web interface that allows users to upload images for disease detection, making it accessible to a wide range of users.
Benefits:

Early Disease Detection: Early detection of leaf diseases can prevent their spread and minimize crop damage, leading to increased agricultural productivity.
Reduced Manual Inspection: Our automated system reduces the need for manual inspection, saving time and effort for farmers.
Data-Driven Insights: The models can provide valuable insights into the prevalence of different diseases, helping experts make informed decisions.
Future Enhancements:
We plan to further enhance this project by:

Expanding the dataset to include more plant species and disease types.
Fine-tuning both models to achieve even higher accuracy.
Implementing real-time disease severity assessment.
Developing a mobile application for on-the-field disease detection.
Conclusion:
Our "Leaf Disease Detection using CNN and Vision Transformers" project represents a significant achievement in the field of agriculture. By implementing two powerful deep learning models, CNN and Vision Transformer (ViT), and achieving impressive accuracy rates, we have demonstrated the potential of deep learning in revolutionizing leaf disease detection. We are committed to improving and expanding this project to contribute to the sustainable growth of agriculture and reduce the impact of leaf diseases on crop yields. We invite collaboration, contributions, and feedback from the community to further advance this project and its applications.
