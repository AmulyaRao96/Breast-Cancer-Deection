# Breast-Cancer-Detection

Breast cancer originates in the breast tissue. It occurs when breast cells mutate (change) and grow out of control, creating a mass of tissue (tumor). The most common type of breast cancer is Invasive Ductal Carcinoma (IDC). About 8 in 10 breast cancers are IDCs. There are various steps carried out to determine to diagnose breast cancer: Breast Ultrasound, Mammogram, Breast Magnetic Resonance Imaging and Biopsy. The last technique that is biopsy is quiet a painful procedure. This is a test that removes tissue or fluid from the breast to be looked at under a microscope and do more testing. There are different kinds of biopsies (for example, fine-needle aspiration, core biopsy, or open biopsy). This must be done manually and is a time-consuming process. Furthermore, the decision depends on the expertise of the pathologist and his or her equipment. Therefor deep learning could be of great help to automatically detect and locate tumor tissue cells and to speed up the process. To exploit the full potential, one could build a pipeline using massive amounts of tissue image data of various hospitals that were evaluated by different experts. This way one would be able to overcome the dependence on the pathologist which would be especially useful in regions where no experts are available.

Goals of the Project:

The goal of this project is to come up with a deep learning model by applying convolutional neural network, Recurrent neural network and artificial neural network algorithms that can identify cancerous cells from non-cancerous cells without the patients having to go through biopsy

Project Details:

•	Selection of performance metric of the algorithm : We chose AUC as performance metric to see how the models performed against each other, since it      doesn’t make a bias between on the size of test or evaluation data and takes into consideration all the threshold values .Higher the AUC better is the performance of the model.
•	We implemented three deep learning models namely- CNN, RNN, ANN
•	We also performed Hyperparameter tunning of the models using GridSearchCV by setting batch size and epochs
•	Visualized the confusion matrix and ROC curves for different models
•	Evaluated all three model’s performance 
