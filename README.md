Facial Emotion Recognition Using FER2013 Dataset

This project was developed to recognize facial emotions using the FER2013 dataset. It implements a comprehensive pipeline for data preprocessing, model building, and emotion classification. The key steps and components are as follows:

Libraries and Tools:
Essential libraries for data processing (e.g., pandas, numpy, torch) and visualization (e.g., matplotlib, seaborn) were imported to ensure a smooth workflow.

Device Selection:
The code dynamically detects and utilizes either GPU or CPU for computations, optimizing performance based on the available hardware.

Initial Data Exploration:
The FER2013 dataset, provided in CSV format, was loaded and its basic structure analyzed. This includes inspecting the dataset's dimensions and metadata.

Data Transformation (FER_Df Class):
A custom FER_Df class was implemented to convert the FER2013 dataset into a PyTorch-compatible format. This preprocessing step ensures that the data can be easily fed into the model for training and evaluation.

Model Architecture (FER_CNN Class):
A Convolutional Neural Network (CNN) was designed using PyTorch. The model includes fully connected layers for emotion classification, enabling it to learn complex patterns in the facial data.

Dataset Splitting:
The data was divided into training, public test, and private test sets. Each split was verified to ensure proper separation and balanced distribution.

Validation of Data Integrity:
The lengths of the datasets were checked to confirm their correctness and readiness for training.

Emotion Distribution Visualization:
A visualization of the emotion distribution in the dataset was created. This helped identify potential class imbalances and provided deeper insights into the dataset's structure.

This project demonstrates the application of machine learning and deep learning techniques for facial emotion recognition. By leveraging PyTorch and the FER2013 dataset, it provides a solid foundation for exploring advanced emotion classification tasks.
