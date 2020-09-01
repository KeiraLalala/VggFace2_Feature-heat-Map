#Visualizing feature maps of VGGFace2 model by Gradient visualization Backpropagation technique and GradCAM heatMap 

1.Repackage the model structure of VGGFace2 model from layer by layer, to block by block;

![image](https://github.com/KeiraLalala/VggFace2_Feature-heat-Map/blob/master/FeaMap_img/0001.bmp)

2.Using Gradient visualization Backpropagation methods to print out the featurmap on each blocks;

![image](https://github.com/KeiraLalala/VggFace2_Feature-heat-Map/blob/master/FeaMap_img/BSC_res50_vis_l8_f149_iter270.jpg)
![image](https://github.com/KeiraLalala/VggFace2_Feature-heat-Map/blob/master/FeaMap_img/BSC_res50_vis_l8_f161_iter270.jpg)
![image](https://github.com/KeiraLalala/VggFace2_Feature-heat-Map/blob/master/FeaMap_img/BSC_res50_vis_l8_f520_iter270.jpg)

3.Using GradCam technique to print out heatmap on each block.

![image](https://github.com/KeiraLalala/VggFace2_Feature-heat-Map/blob/master/FeaMap_img/BSC8_0001_Cam_Grayscale.png)
![image](https://github.com/KeiraLalala/VggFace2_Feature-heat-Map/blob/master/FeaMap_img/BSC8_0001_Cam_Heatmap.png)
![image](https://github.com/KeiraLalala/VggFace2_Feature-heat-Map/blob/master/FeaMap_img/BSC8_0001_Cam_On_Image.png)
