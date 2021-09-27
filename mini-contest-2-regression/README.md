# Land Surface Temperature Evaluation from Satellite Data
This repository contains the solution proposed for the second Mini-Contest of the **Data Mining** course of *University of Naples Federico II*.
You can find more about the competition [here](https://www.kaggle.com/c/unina-data-mining-2021-minicontest-n2/overview).

The aim of the contest is to determine the Land Surface Temperature (LST) from satellite data, using data coming from the National Aeronautics and Space Administration (NASA) Landsat-8 missions <sup>[1](#footnote1)</sup>.

The solution shown in the Notebook, implemented by means of *scikit-learn*, is made up of tree different stages:
- **Feature engineering**: compute the main spectral indexes shown in the literature, such as *NDVI* and *PV*.
- **Feature selection**: correlation-based and projection techniques, such as *Principal Component Analysis (PCA)*.
- **Modeling**: compare several models, such as *Decision Tree*, *K-Nearest Neighbour (KNN)*, *Linear* and *Polynomial Regression*, *Ridge Regression*, *Support Vector Machine (SVM)* and *Multi Layer Perceptron*.

The final model choosed for the submission is a KNN that achieved a Mean Absolute Error (MAE) of 1.50974.



<a name="footnote1">1</a>: data are not from the European Space Agency (ESA) Copernicus Sentinel-2 missions, as erroneously reported on Kaggle.
