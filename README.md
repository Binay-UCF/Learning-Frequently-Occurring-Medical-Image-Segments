# Learning-Frequently-Occurring-Medical-Image-Segments
To run the base model follow the below tutorial. 
https://detectron2.readthedocs.io/en/latest/tutorials/install.html
This tutorial details about all the required installation needed before executing the proposed model file. 
Dataset can be found from the below link.
https://monusac-2020.grand-challenge.org/Data/

Please follow the below steps required for experimental results
1. Download respective datasets along with annotation files(must be in COCO Json file format)
1.1. Perform preprocessing task if required
2. Register the dataset to detectron2  
3. train the pre-trained model with all required changes
4. evaluate the model on test set
 	- also have annotation file ready
	- to evaluate the model first register the test/val set to detectron2
5. Apply stage 2 -> operation
-------------------------------------------------------------------------------
To get the experimental results run FinalProjectCAP6545.ipynb file. The file is implemented in Jyputer notebook. 
Some sample prediction are shown below.
![image](https://github.com/user-attachments/assets/906d3c49-ba45-4d26-b2d3-f124fe97d191)

![image](https://github.com/user-attachments/assets/9c1b34f0-47a7-4679-a178-88349ed75fa8)
