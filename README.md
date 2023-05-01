# Semantic Segmentation   
**Learn about segmentation**   
Semantic segmentation in the field of images refers to the task of dividing objects within an image into meaningful units. (meaningful units: objects)   

------------------------------------

## Model   
+ [U-net](https://arxiv.org/pdf/1505.04597.pdf)   

### Structure   
<img src="https://user-images.githubusercontent.com/104747868/235435743-b261f637-d75f-495e-ba47-ae23c0ea2716.png" width="400" height="300"/>

## Loss
+ **IOU Metric**    
The intersection over union (IoU) metric is a simple metric used to evaluate the performance of a segmentation algorithm. Given two masks $y_{true}, y_{pred}$ we evaluate     
$$IoU = \frac{y_{true} \cap y_{pred}}{y_{true} \cup y_{pred}}$$

---------------------------------------
Epochs : 30   
Best Mean_IOU : 0.828
## Test
![image](https://user-images.githubusercontent.com/104747868/235434029-6f04040b-d2d9-4bf9-b212-862758ff4948.png)   

---------------------------------------

## References    
1. [http://deeplearning.net/tutorial/unet.html](http://deeplearning.net/tutorial/unet.html)
2. [https://github.com/ldenoue/keras-unet](https://github.com/ldenoue/keras-unet)
