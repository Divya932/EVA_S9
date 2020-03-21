# EVA_S9
### GradCAM Implementation

We can see from the outputs of gradCam applied on incorrect predictions that those 
images were predicted without seeing the entire object. Hence it proves the importance of using certain 
augmentation techniques like cutout so that other areas of the object are also given relevant importance
while predicting the labels. 


![GitHub Logo](/gradCAM_cat.png)
The original label here was cat.
The model however predicted it as a frog based on incomplete visualisations as shown by the heat mappings.

This code has been done with reference to Shantanu Acharya's Session 8 Code
