# COVID_detecting_CNN
The model can detect the x-ray images of the lungs of COVID-19 patients with reasonable accuracy. The validation accuracy and test accuracy after training for ten epochs are 95.63% and  96.44% respectively. The model consists of a Residual Network Architecture with 11 layers. The dataset used for the model can be found here: https://www.kaggle.com/tawsifurrahman/covid19-radiography-database?select=COVID-19+Radiography+Database

The model can detect three kinds of x-ray images: COVID-19, Viral Pneumonia and Normal. Although trained on a very small dataset the model performs quite well. It can be further improved by feeding more COVID-19 images for training. GANs can be a good option to increase the number of COVID-19 images.
