# Prediticting--Pneumonia-ML-Model
## Project Team Members: Kudzanai, Emmanuela, Noshaad, Maxwell and Chisimnulia
## Introduction
Pneumonia is a disease, usually caused by an infection, that affects the lungs and it is usually diagnosed by physicians using radiological imaging to determine the infectious agent that causes the disease. 15% of child deaths were caused by Pneumonia in 2017 making it the leading cause of death in children under 5yrs old.
![image](https://user-images.githubusercontent.com/99673859/187027944-a97507ed-63f1-46a8-900d-815d75f6de8f.png)

Again you can see that the death rate from pneumonia is highest in  Africa and Asia. A clear difference between richer and poorer countries. 
![image](https://user-images.githubusercontent.com/99673859/187027977-6c94c1a7-74fb-4c79-b87a-2d68c4798358.png)

Below is an example of chest X rays, and the kind of chest X rays that our model is going to analyse. The first one is a normal chest X rays and the other three are  examples of chest x-rays with different types of Pneumonia. Differentiating X-rays with Pneumonia and X-rays without, could be difficult, as you can see by looking at image 1 and 4.
<img width="805" alt="Pneumonia x-ray" src="https://user-images.githubusercontent.com/85926823/187033122-ac193f92-c356-419c-acd5-71d63594edf8.png">

Armed with this information and knowing that pneumonia cannot easily be detected with the human eye, we set out to develop a convoluted neural network (CNN) model that  can analyse chest x-ray image and determine whether a person has pneumonia or not.

At the end of this presentation, we hope that our model will be used in the healthcare industry to improve detection of pneumonia and ultimately reduce mortality rate especially in under 5 children.

## Data Extraction, Transformation and Loading
Our data was sourced from kaggle and it was loaded onto AWS into a bucket ready for extraction. We used Google Colab to connect to our AWS bucket. We used some essential models for image processing such as CV2 and PIL, and various modules to create  get_data function that processes AWS objects into a (224, 224, 1) Numpy array that is fed into the CNN. We faced many challeges such as image adjustments, we had to change our images from bytes to jpeg, we changed them to grayscale and saved them into arrays to be reduced in size. We also had some data imbalance issues which we resolved using class weights.
 



## Machine Learning


## The APP


