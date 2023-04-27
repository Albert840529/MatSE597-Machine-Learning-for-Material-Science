# MatSE597_Final_project
semi-supervised learning for understanding composite morphology and mechanical properties

1 Data:
In the folder Images, it contains all the µ-CT images that we did for this project. Each subfolder contains 100 images and one csv file that contain the name of each image and the features of each image. The subfolder name represents the name of each composite and the represents mechanical properties. For instance, IPP_5%_4_0.44_1.403_0.245, IPP_5%_4 is the name, 0.44 is the UTS, 1.403 is the young’s modulus, and 0.245 is the elongation at break. This naming method is related to how I do data preprocessing in the code: Final_project_data_preprocess.ipynb.

2 Code:
There are two code files in the main folder. 
First one is (Final_project_data_preprocess.ipynb), which was used to load image and analyze image features into csv file for the following transfer learning code. To use this code, import your images into Images folder and put the same groups of images in the same subfolder based on the above data naming rule.
Second code is (Final_project_data_training.ipynb), this code is for you to train your data set and evaluate the performance of the model.

3 CT-images dataset:
For the access of the data set, please click on the following link:
https://drive.google.com/drive/folders/1M4rYcE8KqSGjYIP5dHxOa0G2gUy6G3wt?usp=share_link
