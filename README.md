# **My Portfolio**

# Project 1: Two-Stream Action Recognition with I3D and CNN
* **Technologies:** Python, PyTorch, OpenCV, PyTorchVideo
* **Key Achievements:**
  * Developed a two-stream action recognition model using PyTorch and a pre-trained I3D network.
  * Implemented data augmentation techniques to improve model robustness and generalization.
  * Achieved 80% accuracy on a shoplifting detection task.
  * Utilized PyTorch's DataLoader with multi-processing to accelerate data loading by more than 50%, reducing training time.
  * Developed a TrainValSampler class to efficiently split the dataset into training and validation sets, ensuring proper data shuffling and batching.
  * Visualized model predictions using saliency maps to highlight important regions in the video frames.
  * Demonstrated strong understanding of deep learning concepts and computer vision techniques.
    
# Project 2: Data Analysis of COVID-19 dynamics in Zambia
* **Project Overview:** This project involved the comprehensive cleaning, preprocessing, and merging of six diverse datasets related to COVID-19 in Zambia and forecasting the total deaths and cases. The resulting integrated dataset provides valuable insights into the pandemic's impact on the country, enabling in-depth analysis and informed decision-making.
* **Technologies:** Python, Pandas, Seaborn, Matplotlib, Folium, Scikit-learn
* **Key Achievements:**
   * **Data Integration:** Successfully integrated six datasets from various sources, including government agencies, international organizations, and research institutions.
   * **Data Cleaning:** Handled extensive missing data across multiple datasets, employing techniques like dropping irrelevant columns/rows, filling with 0, forward/backward filling, and linear regression imputation.
   * **Data Preprocessing:** Performed numerous data transformations, including:
       * Standardizing date/time formats
       * Grouping and aggregating data
       * Generating complete date ranges and reindexing
       * Feature engineering (calculating rates, proportions, and moving averages)
   * **Data Visualization:** Utilized Matplotlib and Folium libraries for visualizations, aiding in data exploration, missing value identification, and pattern recognition.
   
# Project 3: [Brain Tumor Segmentation](https://huggingface.co/hansie23)
* **Objective:** Developed a deep learning model for automatic segmentation of brain tumors from MRI images using the U-Net architecture.
* **Technologies Used:** Python, TensorFlow, Keras, NumPy, OpenCV, PIL, Matplotlib.
* **Data Preprocessing:** Preprocessed a dataset of MRI images and corresponding masks, including resizing, normalization, and augmentation to enhance model robustness.
* **Model Architecture:** Implemented a U-Net convolutional neural network comprising encoder and decoder pathways for feature extraction and segmentation.
* **Training and Evaluation:** Trained the model using Adam optimizer and binary cross-entropy loss, evaluated performance metrics including accuracy, dice coefficient, and Jaccard index.
* **Model Interpretability:** Utilized Gradient-weighted Class Activation Mapping (Grad-CAM) to visualize model decisions and interpret the importance of different features in segmentation.
* **Result Visualization:** Generated visualizations of model predictions and ground truth masks for qualitative assessment of segmentation accuracy.
* **Deployment:** Deployed the model as a web app using Streamlit. [Deployment link](https://hansie23-brain-tumor-segmentation.hf.space)
* **Outcome:** Achieved promising results in tumor segmentation, demonstrating potential for clinical application in medical image analysis and contributing to advancements in healthcare technology.

# Project 4: [Dog Breed Prediction](https://huggingface.co/hansie23)
* **Objective:** Developed a machine learning model to classify dog breeds from images using TensorFlow.
* **Technologies Used:** Python, TensorFlow, Keras, NumPy, Pandas, Matplotlib, Streamlit.
* **Data Preprocessing:**
  * Sourced from Kaggle’s Dog Breed Identification challenge.
  * Contains thousands of labeled images categorized into 120 dog breeds.
  * Applied image augmentation techniques (rotation, flipping, zooming, shifting) to enhance model generalization.
  * Utilized batch processing for efficient memory usage and training optimization.
* **Model Architecture:** Leveraged transfer learning using the MobileNet_V2 model (https://tfhub.dev/google/imagenet/mobilenet_v2_130_224/classification/5).
* **Training:** 
  * Trained the model using the augmented dataset.
  * Used categorical cross-entropy loss function and Adam optimizer.
  * Monitored performance on a validation set for hyperparameter tuning and overfitting prevention.
* **Evaluation:** Evaluated model performance on a separate test set and using a custom function to evaluate the predicted dog breed with the actual dog breed.
* **Result:** High accuracy in classifying dog breeds and effective generalization to new, unseen images due to image augmentation.
* **Deployment:** Deployed the model as a web app using Streamlit. [Deployment link](https://hansie23-dog-breed-classifier.hf.space)
* **Outcome:** Demonstrated the potential of transfer learning in image classification tasks with numerous categories. Gained experience in data preprocessing, image processing and transfer learning.
