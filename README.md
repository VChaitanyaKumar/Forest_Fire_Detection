# Forest Fire Detection using Deep Learning

## Project Overview
This project focuses on building a Convolutional Neural Network (CNN) to detect forest fires from images using deep learning. The goal is to enable early detection to help reduce the impact of forest fires on ecosystems, wildlife, and human life.

## Objectives
- Understand and implement CNNs using TensorFlow and Keras
- Train a model to classify images as "fire" or "no fire"
- Evaluate model performance using accuracy and loss
- Predict fire presence in new, unseen images
- Apply deep learning to address a real-world environmental problem

## Tools and Technologies
- **Google Colab** – for cloud-based model development and training  
- **Python** – programming language used for all implementation  
- **TensorFlow and Keras** – deep learning libraries used to build the CNN  
- **NumPy** – for handling numerical data  
- **Matplotlib** – for visualizing training results  
- **ImageDataGenerator** – for image preprocessing and augmentation  

## Methodology
1. **Dataset Acquisition** – Wildfire image dataset obtained from Kaggle  
2. **Data Exploration** – Visualized sample images from 'fire' and 'no fire' classes  
3. **Data Preparation** – Resized images to 150x150, normalized pixel values, and prepared train/validation/test sets  
4. **Model Building** – Built a CNN with convolutional, pooling, and dense layers  
5. **Model Compilation** – Used Adam optimizer and binary cross-entropy loss function  
6. **Model Training** – Trained for 12 epochs and monitored accuracy and loss  
7. **Model Evaluation** – Tested performance and visualized results  
8. **Prediction Function** – Developed a utility to classify uploaded images  

## Results
- The trained model successfully distinguishes between fire and non-fire images  
- Achieved high accuracy and demonstrated strong performance on test data  
- Accuracy and loss graphs show consistent training behavior  

## Conclusion
This project demonstrates how deep learning can be effectively used for forest fire detection. It highlights the practical application of CNNs in environmental protection and offers hands-on experience with data processing, model design, and evaluation.

## Future Scope
- Improve the model using deeper architectures and regularization techniques  
- Expand the dataset with more diverse images for improved generalization  
- Integrate with real-time systems like drones or satellite feeds  
- Combine with other tools like GIS and weather data for enhanced prediction  
- Field testing and deployment in collaboration with emergency response agencies  

## How to Run
1. Clone this repository  
2. Open the `Forest_Fire_Detection_using_DL.ipynb` notebook in Google Colab or Jupyter Notebook  
3. Upload the dataset or connect to the dataset from Kaggle  
4. Run all the cells step-by-step  
5. Use the prediction function to classify new images  

## Screenshots
- Example images of fire and no fire  
- Model summary screenshot  
- Accuracy and loss plot from training  
- Sample prediction outputs  
