*************************************************
*************************************************

Mission: Save the Beavers
Terrain Identification using Artificial Intelligence
(Simple CNN or Masked R-CNN)

Git Hub Link : https://github.com/SwanandChawathe/Mission-Save-the-Beavers_Terrain-Identification-using-Artificial-Intelligence
************************************************
************************************************
Coourse: Applications of Machine Learning (2022 MOD006567 TRI2 F01CAM)
Project by : 
Swanand Pravin Chawathe (2121373)
Student,
Anglia Ruskin University,
Cambridge, United Kingdom

Rahaf Saffaf (2178425)
Student,
Anglia Ruskin University,
Cambridge, United Kingdom

************************************************
************************************************

On our Mission to save the Beavers we will be working through various techniques and CNN models to eventually find interesting results and learn and acknowledge of the Applications of Machine learning in real world, in our case a noble cause to save the Beavers.

In all we conducted three experiments thus you shall find three set of codes.

EXPERIMENT I
(Simple CNN )
	We start our experiment by Using Simple Convolution Neural Network to check on its effective in our mission to save the Beavers, that is to successfully identify the terrains and Beaver Dams and Lodges.
		file name: Save_The_Beavers_CNN_OriginalData_Resized_Extended_EXPERIMENT_I.ipynb
		Database: export-2023-03-31T14_30_22.106Z.json (Labelbox)

EXPERIMENT II
(Mask RCNN- Semantic Segmentation)

	Summary: Moving on to Mask RCNN model in Experiment II, learning from the simple CNN (EXP I) results and studying about Mask RCNN.We decided to implement semantic segmentation to study its effectiveness in our mission to save the 		beavers that is terrain identification.

	Approach: We used the method of Transfer Learning and a solution inline and ontop of the Mask-RCNN, based on research performed by Ahmed F Gad with "Mask R-CNN for Object Detection and Segmentation using TensorFlow 2.0" available 		on github repositry. Using the pre-trained weights of the Mask R-CNN model based on the COCO dataset, further finetuning the model using the beaver dataset. Using TensorFlow 2.0.0, Keras 2.2.4 (also Keras 2.3.1), and 		Python 3.7.3 	(also Python 3.6.9 and Python 3.6.13). We attempt to run the code on GPU, Colab.

	This code has two parts:
	(Semantic Segmentation using Mask R-CNN - Part 1 (Data Preparation))
		File Name: Preparing_images.ipynb

	(Semantic Segmentation using Mask R-CNN - Part 2 (Model Training))
		File Name: Terrian_Classification.ipynb

		Database:export-2023-03-25T21_23_20.508Z.json/export-2023-03-31T14_30_22.106Z (Labelbox)


EXPERIMENT III
(Mask R-CNN Instance Segmentation)
	Part A: (Single Class)
		File Name: Save_The_Beavers_Experiment_III_partA.ipynb
		Database: labels_my-project-name_2023-04-11-09-22-17.json (MakeSense) This file only contains the annotations, actual images need to be uploaded
	Part B: (Multi Class)
		File Name: SaveTheBeavers_Mask_RCNN_EXPERIMENT_III_Part_B_Final.ipynb
		Database: labels_savebeavers_2023-04-06-01-17-46.json (MakeSense) This file only contains the annotations, actual images need to be uploaded
