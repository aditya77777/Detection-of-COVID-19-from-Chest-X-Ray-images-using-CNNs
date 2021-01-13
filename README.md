# Detection-of-COVID-19-from-Chest-X-Ray-images-using-CNNs
The COVID-19 (coronavirus) is an ongoing pandemic caused by severe acute respiratory syndrome coronavirus 2 (SARS-CoV-2). The virus was first identified in mid-December 2019 in the Hubei province of Wuhan, China and by now has spread throughout the planet with more than 75.5 million confirmed cases and more than 1.67 million deaths. With limited number of COVID-19 test kits available in medical facilities, it is important to develop and implement an automatic detection system as an alternative diagnosis option for COVID-19 detection that can used on a commercial scale. Chest X-ray is the first imaging technique that plays an important role in the diagnosis of COVID-19 disease. Computer vision and deep learning techniques can help in determining COVID-19 virus with Chest X-ray Images. Due to the high availability of large-scale annotated image datasets, great success has been achieved using convolutional neural network for image analysis and classification. In this research, we have proposed a deep convolutional neural network trained on five open access datasets with binary output: Normal and Covid. The performance of the model is compared with four pre-trained convolutional neural networkbased models (COVID-Net, ResNet18, ResNet and MobileNet-V2) and it has been seen that the proposed model provides better accuracy on the validation set as compared to the other four pre-trained models. This research work provides promising results which can be further improvise and implement on a commercial scale.

Keywords – COVID-19, SARS-CoV-2, Chest X-Ray, Computer Vision, Deep learning, Convolutional Neural Network

# Dataset

The dataset used to train the proposed model is a combination of two open-source datasets called COVID19 image data collection and Covid-Net. The COVID-19 image data collection was initially built by collecting medical images from websites and research publications such as Radiopaedia.org, the Italian Society of Medical and Interventional Radiology.
It also included medical images directly from the PDF using the tool pdf images. The objective of using an imaging tool was to maintain the quality of the images. The COVID-19 image data collection dataset consisted of 148 frontal view Chest X Radiology images. The Covid-Net dataset is a collection of 13,975 CXR images of around 13,870 infected patients. It is the largest open-access benchmark dataset in terms of images with COVID-19 infected patients. The dataset also comprises images from leading medical databases including COVID-19 Chest X-ray Dataset Initiative. ActualMed COVID-19 Chest X-ray Dataset Initiative, established in collaboration with ActualMed RSNA Pneumonia Detection Challenge dataset and COVID-19 radiography database The combined dataset after filtration consists of 9,438 Chest X-Ray images which are categorized into 2 labels, that is, Covid (Pneumonia) and normal.

Dataset generation is available publicly for open access at https://github.com/lindawangg/COVID-Net
