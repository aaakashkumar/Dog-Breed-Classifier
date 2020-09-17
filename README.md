[//]: # "Image References"

[image1]: ./images/sample_dog_output.png "Sample Output"
[image2]: ./images/vgg16_model.png "VGG-16 Model Layers"
[image3]: ./images/vgg16_model_draw.png "VGG16 Model Figure"

# Dog Breed Classifier Capstone Project

## Project Overview

This project aims to build a pipeline that can be used within a web or mobile app to process real-world, user-supplied images.  Given an image of a dog, our algorithm identifies an estimate of the canine’s breed.  If supplied an image of a human, the code identifies the resembling dog breed. 

![Sample Output][image1]

Along with exploring state-of-the-art CNN models for classification and localization, this project aims to highlight the challenges involved in piecing together a series of models designed to perform various tasks in a data processing pipeline. Each model has its strengths and weaknesses, and engineering a real-world application often involves solving many problems without a perfect answer. 



# Dependencies

This project mainly makes use of Python, Jupyter Notebooks, OpenCV and PyTorch. Other packages used in this project have been listed in the `requirements.txt` file and may be installed following the instructions in the Project Instructions section.




## Project Instructions

To manually run through the code, you may follow the instructions given below.

### Instructions

1. Clone the repository and navigate to the downloaded folder.
	
	```	
		git clone https://github.com/aaakashkumar/Dog-Breed-Classifier.git
		cd deep-learning-v2-pytorch/project-dog-classification
	```
   
   __NOTE:__ This repository is private as of now, and cannot be accessed through git. All the files have been included in the zip.
   
2. Download the [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip).  Unzip the folder and place it in the repo, at location `path/to/dog-project/dogImages`.  The `dogImages/` folder should contain 133 folders, each corresponding to a different dog breed.

3. Download the [human dataset](http://vis-www.cs.umass.edu/lfw/lfw.tgz).  Unzip the folder and place it in the repo, at location `path/to/dog-project/lfw`.  If you are using a Windows machine, you are encouraged to use [7zip](http://www.7-zip.org/) to extract the folder. 

4. Install the necessary Python packages

   ```
   pip install -r requirements.txt
   ```

5. Open a terminal window and navigate to the project folder. Open the notebook and follow the instructions.

  ```
  jupyter notebook dog_app.ipynb
  ```



