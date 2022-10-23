# Neurodegenerative Disease Diagnosing With Machine Learning

- This study focuses on how neurodegenerative diseases that affect cognitive abilities can be diagnosed by handwriting analysis. Neurodegenerative diseases are caused by motor neurons not performing their functions properly and cause some deformations in handwriting. This study explores how these deformations can be detected by machine learning algorithms accurately. 
- We used  a convolutional neural network model to detect handwriting deformations of Parkinson's disease patients. Handwriting deformations will be used as decision makers in the diagnostic process. The drawings in the NewHandPD data set consisting of 264 images are divided into two parts, 188 of them are considered as training data and 76 of them are considered as test data. The drawing files obtained from the participants are used as an input for the convolutional neural network model. We optimized hyper-parameters to obtain highest accuracy. 
- As a result of the hyperparameter optimization, the most suitable search space for the filter size was between 8 and 128, these values found different for parameters such as pooling layer size and epoch size. Handwritten images of Parkinson's patients classified as "patient" and "not patient" with an accuracy of 87 %. 
- This study found that a machine learning model can be used to diagnose Parkinson's disease with an accuracy of 87 %. Anomalies caused by the disease tried to be diagnosed. This study contributes to the implementation of fast, efficient, effective and less costly diagnostic procedures.

- You can reach the data set from here :  https://wwwp.fc.unesp.br/~papa/pub/datasets/Handpd/
