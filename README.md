# EVA5_Session4
The purpoe of this document is to reduce the number of parmeters in trainingdate set ,maintaing an accuracy .
The kernal choosen for the first layer is 7 ,follwed by 1 ,1 .There are three layers used
The acuuracy is mangaed at increasing order fro 90% to 96%.
Relu has been used in the each layer except the 3rd for the activation.
BAtchnormalisation has been used till layer 2 but has been not used in the final layer.
Dropout has been used.

learning rate is .01 

Global average pooling has been used over Fully connected layers.FCs are not used to avoid the issue spatial data ( converting n dimesional data into 1d array,and loosing space information)
GAP has been follwed by the softmax 
