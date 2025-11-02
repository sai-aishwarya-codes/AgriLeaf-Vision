# 🌾 AgriLeaf Vision – Rice Leaf Disease Detection using Machine Learning

AgriLeaf Vision leverages **cutting-edge machine learning** to revolutionize agricultural diagnostics.  
Our project focuses on **precise and early detection of rice leaf diseases** to help farmers safeguard crop yield, reduce losses, and promote sustainable farming practices.

---

## 🚀 Overview

Rice is one of the world’s most important staple crops — yet it’s vulnerable to multiple diseases that can devastate production.  
**AgriLeaf Vision** provides an **AI-driven solution** that can automatically detect and classify rice leaf diseases from images using advanced **deep learning models**.

### 🎯 Key Objectives
- Automate rice leaf disease detection with high accuracy.  
- Assist farmers and agronomists with fast, accessible crop health diagnostics.  
- Contribute to the development of **AI-powered smart agriculture** systems.

---

## 🧠 Tech Stack

| Category | Tools & Technologies |
|-----------|----------------------|
| **Languages** | Python |
| **Libraries / Frameworks** | TensorFlow / Keras, OpenCV, NumPy, Pandas, Matplotlib |
| **Model Architecture** | CNN (Convolutional Neural Network) |
| **Dataset** | Rice Leaf Disease Dataset (custom or from Kaggle) |
| **Environment** | Jupyter Notebook / Google Colab |
| **Visualization** | Matplotlib, Seaborn |

---

## 🔍 Workflow

1. **Data Collection & Preprocessing**  
   - Image resizing, normalization, and augmentation.  
2. **Model Development**  
   - Trained a **CNN-based model** to classify rice leaf diseases.  
3. **Model Evaluation**  
   - Accuracy, precision, recall, and F1-score metrics used.  
4. **Deployment (Future Scope)**  
   - Plan to deploy as a web or mobile app for farmer-friendly usage.  

---

## 📊 Results

- Achieved **high model accuracy** in detecting major rice leaf diseases such as:
  - **Bacterial Leaf Blight**
  - **Brown Spot**
  - **Leaf Smut**

> 📈 Model demonstrated excellent generalization and robustness across test samples.

---

## 🖼️ Sample Output

| Input Image | Predicted Disease |
|--------------|------------------|
| 🌿 Rice Leaf 1 | Bacterial Leaf Blight |
| 🌿 Rice Leaf 2 | Brown Spot |
| 🌿 Rice Leaf 3 | Healthy |

*(Include sample images or prediction visualizations here)*

---

## 🌱 Future Enhancements

- Real-time detection using a **mobile app or camera feed**  
- Integration with **IoT-based crop monitoring systems**  
- Expand model for **multi-crop disease detection**

---

## 🤝 Contributing

Contributions are welcome!  
If you’d like to improve this project or add new features, feel free to fork the repository and submit a pull request.

---

## 📬 Contact

👩‍💻 **Sai Aishwarya**  
📧 [saiaishwaryagithub@gmail.com](mailto:saiaishwaryagithub@gmail.com)  
🔗 [GitHub Profile](https://github.com/sai-aishwarya-codes)  
💼 [LinkedIn](https://www.linkedin.com/in/sai-aishwarya/)  

---

## ⭐ Acknowledgements

- Kaggle for dataset resources  
- TensorFlow & Keras for deep learning frameworks  
- Open-source community for inspiration and support  

---

### 🌾 “Empowering Farmers with AI — For a Greener Tomorrow.”

---


# Rice-Leaf-Disease-Detection

## INTRODUCTION
The rice leaf suffers from several bacterial, viral, or fungal diseases and these diseases reduce rice production significantly. To sustain rice demand for a vast population globally.The rice leaves related diseases often pose threats to the sustainable production of rice affecting many farmers around the world. Early diagnosis and appropriate remedy of the rice leaf infection is crucial in facilitating healthy growth of the rice plants to ensure adequate supply and food security to the rapidly increasing population.

### Rice Leaf Disease:
![image](https://user-images.githubusercontent.com/101791322/177773023-a8114cb6-c1c4-497b-b51f-de9baef4e8d5.png)

### DATA SUMMARY
This dataset contains 120 jpg images of disease infected rice leaves. The images are grouped into 3 classes based on the type of disease. There are 40 images in each class.

### Classes

* Leaf smut
* Brown spot
* Bacterial leaf blight

### WE HAVE DEVICE THE PROJECT INTO MULTIPLE STEPS:
* Importing library
* Loading data
* Preparing data
* Data Processing 
* Model building
* Training
* Evaluation
* Testing



### LODING DATA / PREPARING DATA
•	Make a subset of data into three parts train, test, and validation with the help of split folder library.

### DATA PROCESSING
•	In this step generate the batches of training and validation and pre-process the images

### PLOTTING TRAINING IMAGES:
![image](https://user-images.githubusercontent.com/101791322/177773523-fbb6bcbe-81ff-4805-a34d-b655083de8de.png)

### MODEL BUILDING

* In this step we create CNN model architecture in that three types of layers convolution layer, pooling layer, 
And fully connected layer are added.
* Plotting a graphical representation of model
*	Get the summary of model
*	Compile model
*	Then the last train the model 
*	After training validation accuracy is 91.67% and accuracy is 84.38%.
*	Save the model

### MODEL EVALUATION:
•	Here the loss is 0.53 and the accuracy of model is 0.9166 means 91.66%

### MODEL TESTING:
In this step we are create a function to test multiple images from test data. 


![image](https://user-images.githubusercontent.com/101791322/177774011-ba9942b4-ab73-40cf-a3db-8c5db75a64df.png)

 



