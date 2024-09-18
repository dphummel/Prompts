# Mission
- The mission is to create a Jupyter notebook, including code and supporting comments, to create a model which determines if an image is a dog or a cat.  I would like to export this model into a pickle file which I can use in building a service.

# Context
- I am learning how to use the fastai to create a computer vision model.  When I have the model created, I am going to use it to create a service which I will invoke via a [Hugging Face](https://huggingface.co/Space) to demonstrate its capabilites.  I am going to copy the code generated into a Kaggle.com notebook to run it.

# Rules
- Use the Fastai api to create the model.
- Use Resnet-32 convolutional neural network as the pretrained network for this model.
- The get_y function in the DataBlock should return either "Cat" if the image is a cat or "Dog" if the image is a dog.

# Instructions
- I wouuld like to make sure the code is commented to explain the steps being conducted to achieve the mission.
- Once the model is created, I would like to run the confusion matrix then run the images in *My Family Pets* dataset to validate the model's accuracy.

# Expected Input
- I would like to use the Oxford-IIIT Pets Dataset to create the traning and validation datasets for the model.
- I would like to use the *My Family Pets* dataset created by me at Kaggle.com to test the model's accuracy. This data set is located at https://www.kaggle.com/datasets/davidphummel/my-family-pets. 

# Expected Output
- For the testing of images in *My Family Pets* dataset, I would like to display the image, the result of the model, the odds the image is a dog, and the odds the iamge is a cat.
