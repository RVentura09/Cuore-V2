# Cuore-V2

The scope of the project encompasses the creation of a web-based tool to help diagnose incoming patients with heart disease based on various patient measurements in the Cleveland Clinic Foundation. The tool will serve the function of a decision support system for the cardiology department where the practitioner will manually input the required values. The tool is intended to analyze the different patient measurements and provide a recommended diagnosis of Acute coronary syndrome (ACS) to the practitioner who will consider the viability of the result. The system will be created using python programming language with the implementation of Dash and scikit-learn libraries to develop machine learning models that will learn the relationship between the different features of the Cleveland Clinic UCI Heart Disease dataset. Within the scope of the project is included the preparation, cleaning, and analysis of the dataset to be used in the training of the machine learning model. As result, the tool is intended to correctly identify patients with heart disease and provide the accuracy and different evaluation metrics of the machine learning model.

Steps for use 
A) Test run the saved model:
  1) Download files CUORE2Dash.py,trained_model_cuore.pickle and header_image
  2) Place the 3 items in the same folder
  3) Open CUORE2Dash.py either on VsCode or Spyder  and run it open the specified address usually : http://127.0.0.1:8050/
  4) Fill the required data
  5) Hit on "Predict for patient"

B) Creation of model and data transformation
  1) Download files processed.cleveland.csv , Project_Cuore 2.ipynb
  2) Save files in the same folder
  3) Run the notebook , it should create 3 files Cleveland_ModelData.csv ,Cleveland_TransformedData.csv,trained_model_cuore.pickle
  4) Cleveland_TransformedData.csv is only used to generate a PowerBi report it has no impact in the models performance.

  *Notice : in case of any error  verify that you have installed all the required libraries listed on Requirement.txt
   


This project is a group collaboration between Tara de Groot, Rony Ventura, Eric Vincent Rivas, Silvia Dubon,Frank Aiwuyor Ogiemwonyi, Dwi Aji Kurnia Putra, and Laureanne van Dijk
