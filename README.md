# Heart-Sound-Classification
This submission provides the code explained by the (upcoming) eBook on the complete machine learning workflow. Based on the heart sound recordings of the PhysioNet 2016 challenge, a model is developed that classifies heart sounds into normal vs abnormal, and deployed in a prototype (heart) screening application. The workflow demonstrates:
1) using datastore for efficiently reading large number of data files from several folders
2) using tools from signal processing, wavelets and statistics for feature extraction
3) using ClassificationLearner app to interactively train, compare and optimize classifiers without writing any code
4) programmatically training an ensemble classifier with misclassification costs
5) applying an automated feature selection to select a smaller subset of relevant features
6) performing C code generation for deployment to an embedded system
7) applying Wavelet scattering to automatically extract features that outperform manually engineered ones
