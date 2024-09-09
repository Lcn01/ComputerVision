# ComputerVision
This is my code notebook and image/label files for my Computer Vision course from UT Austin's Postgraduate Certification in AI/ML: Business Applications. In this project, I built a convolutional neural network to classify plant seedlings into their respective categories based on their photographs, which could be applied to many different agricultural businesses to maximize crop yields and improve labor efficiency.

The images and labels were first loaded into a Python notebook in Google Colab, where they were then pre-processed and exploratory data analysis was performed. Then two seperate models were created, one with the base data, and one with data augmentation on the training set and using ReduceLRonPlateau in the CNN to reduce the learning rate. Upon evaluation of the accuracy of both models, the second model with data augmentation was chosen as the final model, scoring an 85% accuracy rate classifying the seedlings into 12 different categories.

After the final CNN model was selected, actionable business insights and conclusions were given, as well as stating how the model might be further improved in the future.
