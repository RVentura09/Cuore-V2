# Cuore-V2

The scope of the project encompasses the creation of a web-based tool to help diagnose incoming patients with heart disease based on various patient measurements from the Cleveland Clinic Foundation. The tool will serve as a decision support system for the cardiology department, where practitioners will manually input the required values. The tool is intended to analyze the different patient measurements and provide a recommended diagnosis of Acute Coronary Syndrome (ACS) to the practitioner, who will then consider the viability of the result. The system will be created using the Python programming language, with the implementation of Dash and scikit-learn libraries to develop machine learning models that will learn the relationships between the different features of the Cleveland Clinic UCI Heart Disease dataset. The project scope also includes the preparation, cleaning, and analysis of the dataset to be used in training the machine learning model. As a result, the tool is intended to correctly identify patients with heart disease and provide accuracy and other evaluation metrics of the machine learning model.

Steps for Use:

A) Test run the saved model:

  1) Download the files CUORE2Dash.py, trained_model_cuore.      pickle, and header_image.
  2) Place the three items in the same folder.
  3) Open CUORE2Dash.py either in VSCode or Spyder and run it.  
  4) Open the specified address, usually: http://127.0.0.1:8050/.
  5) Fill in the required data.
  6) Click on "Predict for patient."

B) Creation of the model and data transformation:

  1) Download the files processed.cleveland.csv and Project_Cuore2.ipynb.
  2) Save the files in the same folder.
  3) Run the notebook. It should create three files: Cleveland_ModelData.csv, Cleveland_TransformedData.csv, and trained_model_cuore.pickle.
____________________________________________________________________________________________________________________________________________________________________________________________________

* Cleveland_TransformedData.csv is only used to generate a Power BI report and has no impact on the model's performance.

* Notice: In case of any errors, verify that you have installed all the required libraries listed in "Requirement.txt".

* This project is based from original Cuore project which is a group collaboration between Tara de Groot, Rony Ventura, Eric Vincent Rivas, Silvia Dubon,Frank Aiwuyor Ogiemwonyi, Dwi Aji Kurnia Putra, and Laureanne van Dijk

____________________________________________________________________________________________________________________________________________________________________________________________________
Changelog

- Project_Cuore2.ipynb
  -   Added data transformation steps.
  -   Save cleaned and transformed csv files.
  -   Eliminated the feature selected dataframe due to low performance.
  -   Included confusion matrix for the final model.
  -   Minor code readability and comment updates.
 
- CUORE2DASH.py
  -   Improved readability.
  -   Limited numerical values to only positive values.
  -   Updated dropdown lists values to their proper value instead of a number.

- Cuore Report.pbix
  -   Created powerbi report.
  -   Added mobile phone layout
  -   Sync slicers in both pages
    
