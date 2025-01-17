<div align="center">  
<h1 align="center">  
 <img src="Img/Fundus_-_diabetic_retinopathy.png" alt="App Icon" width="200">  
<br>Retinopathy-Detection-using-Transfer-Learning</h1>  
<h3>Developed with the packages and tools below 🛠️</h3>  
<h3>VGG16, Resnet, Efficientnet, Densenet121, Ensemble Learning, Self Attention ⚙️</h3>  
<p align="center">  
<img src="https://img.shields.io/badge/TensorFlow-blue?style=flat&logo=tensorflow&logoSize=auto&labelColor=gray" alt="TensorFlow" />  
<img src="https://img.shields.io/badge/Keras-blue?style=flat&logo=keras&logoSize=auto&labelColor=gray", alt="Keras"/>  
<img src="https://img.shields.io/badge/Numpy-blue?style=flat&logo=numpy&logoSize=auto&labelColor=gray", alt="Numpy"/>  
<img src="https://img.shields.io/badge/Pandas-blue?style=flat&logo=pandas&logoSize=auto&labelColor=gray", alt="Pandas"/>  
<img src="https://img.shields.io/badge/Scikitlearn-blue?style=flat&logo=scikitlearn&logoSize=auto&labelColor=gray", alt="Sklearn"/>  
<img src="https://img.shields.io/badge/Scipy-blue?style=flat&logo=scipy&logoSize=auto&labelColor=gray", alt="Scipy"/>  
</p>  
<img src="https://img.shields.io/github/license/Abu-Taher-web/Retinopathy-Detection-using-Transfer-Learning?style=for-the-badge&color=5D6D7E" alt="GitHub license" />  
<img src="https://img.shields.io/github/last-commit/Abu-Taher-web/Retinopathy-Detection-using-Transfer-Learning?style=for-the-badge&color=5D6D7E" alt="git-last-commit" />  
<img src="https://img.shields.io/github/commit-activity/m/Abu-Taher-web/Retinopathy-Detection-using-Transfer-Learning?style=for-the-badge&color=5D6D7E" alt="GitHub commit activity" />  
<img src="https://img.shields.io/github/languages/top/Abu-Taher-web/Retinopathy-Detection-using-Transfer-Learning?style=for-the-badge&color=5D6D7E" alt="GitHub top language" />
<p>
 <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Abu-Taher-web&repo=Retinopathy-Detection-using-Transfer-Learning&layout=compact" alt="Top Languages" /> 
</p>
 
</div>  


# 📁 How to Use This Repository  

This repository contains all the code and data required for the project, organized by tasks as outlined in the project instructions. Below is a guide for using the contents of the repository effectively.  

## 📂 Repository Structure  

The repository is organized into folders corresponding to different tasks:  
- `📄 TASK-A`: Contains notebooks and scripts for fine-tuning pretrained models on the DeepDRiD dataset.  
- `📄 TASK-B`: Includes a notebook for conducting training using additional datasets. Modify augmentation and sampling methods to generate the required data.  
- `📄 TASK-C`: Implements attention mechanisms like self-attention, channel attention, and spatial attention.  
- `📄 TASK-D`: Features separate notebooks for bagging, boosting, and weighted average ensemble methods. Data preprocessing techniques and ensemble learning approaches are provided here.  
- `📄 TASK-E`: Provides tools for creating visualizations and implementing Explainable AI techniques such as GradCAM.  

## 📝 Task-Specific Instructions  

### 🧪 TASK-A: Fine-tuning pre-trained models using the DeepDRiD dataset  
1. Navigate to the `TASK-A` folder.  
2. Open the provided notebook.  
3. To get the required output:  
   - Set the dataset directory properly based on your dataset location.  
   - Use the DeepDRiD dataset for model fine-tuning.  
4. Execute the notebook to train the model with your selected configurations (preferred Kaggle GPU 100).  
5. Evaluate the results by comparing metrics like **Cohen's Kappa scores**.  
6. Grad-CAM visualization has also been added to the notebook.  

### 🛠️ TASK-B: Two-Stage Training with Additional Datasets  
1. Navigate to the `TASK-B` folder.  
2. Open the provided notebook.  
3. To generate the required data:  
   - Change the augmentation method by modifying the respective section in the notebook.  
   - Update the sampling method based on your requirements.  
   - Use the provided datasets (e.g., Kaggle DR Resized or APTOS 2019 Blindness Detection).  
4. Run the notebook to train the model using your chosen configurations.  

### 🎛️ TASK-C: Attention Mechanisms in the VGG16, ResNet38, DenseNet201, and EfficientNet Models  
1. Navigate to the `TASK-A` folder.  
2. Open the provided notebook. This notebook contains both task A and task C combined.  
3. To get the required output:  
   - Set the dataset directory properly based on your dataset location.  
   - Use the DeepDRiD dataset for model fine-tuning.  
4. Execute the notebook to train the model with your selected configurations (preferred Kaggle GPU 100).  
5. Evaluate the results by comparing metrics like **Cohen's Kappa scores**.  

### 🔀 TASK-D: Ensemble Learning and Image Preprocessing  
1. Navigate to the `TASK-D` folder.  
2. Separate notebooks are provided for different ensemble techniques:  
   - **Bagging**: Evaluate this method using default augmentation and compare results with unsampled and sampled data.  
   - **Boosting**: Train models using boosting techniques as described in the corresponding notebook.  
   - **Weighted Average**: Combine model predictions using weighted average and evaluate performance.  
3. Experiment with different preprocessing methods (e.g., Ben Graham transformation, CLAHE, circle cropping) to assess their impact on model performance.  
4. Analyze results by comparing evaluation metrics such as **Cohen Kappa scores**.  

## 📝 Notes  
- Ensure that the required datasets are downloaded and placed in the appropriate directories as specified in each notebook.  
- All trained models are saved in the respective task folders for easy reference.  
- Modify hyperparameters, augmentations, and training strategies as needed to improve results.  
- Use visualizations and GradCAM results from `TASK-E` to interpret model predictions and improve understanding of model behavior.  

---  

