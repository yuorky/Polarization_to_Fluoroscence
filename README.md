# Polarization_to_Fluoroscence
Predicting Thioflavin fluoroscence signal of presumed amyloid deposits by polarimetric statistics

This project is designed for seperating fluoroscence and non fluoroscence retinal deposits (presumed amyloid deposits). The main goal is to predict the existance of fluoroscence signal using statistics from polarimetry microscope, allowing amyloid deposits to be detected without the use of a dye.

14 polarization metrics values are considered as input features, 3 machine learning classifiers: LDA, SVM and Random forest have been tested.

We used 3 methods to deal with data imblance:
1. Adding Fluo_Negative_Cross_Negative data by selecting retinal area near deposits
2. ADASYN algorithm
3. BoardlineSMOTE


Author: Yunyi Qiu
Co-author: Tao Jin
Data provided by: Dr.Melanie Campbell's Lab
