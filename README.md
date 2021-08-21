# Real-time-detection-of-ASL-Alphabets
The users of American Sign Language range somewhere between 250,000 to 500,000 persons. But most of the communication happens among the persons suffering from deafness and those who have learned the American Sign Language. If someone who is not proficient wants to have communication, then he or she needs someone who has learned the American Sign Language. There are experts in sign language who act as moderators between the person who is verbally speaking the disabled person who is using the sign language.

### Objective:

In this project, a deep learning model is built to alleviate the above problem a bit. Deep learning and convolutional neural networks is used to build a model that can recognize the American Sign Language alphabets with decent enough accuracy.

### Dataset:

**Link to the dataset** - https://www.kaggle.com/grassknoted/asl-alphabet

The dataset contains 87000 images with a dimension of 200×200.
There are 29 classes in total. 26 of these classes are letters from A-Z. Then there are three more classes that correspond to  SPACE, DELETE, and NOTHING. There are 3000 images from each class.

Since the dataset is very large, it will take much more time and resources to train the model. Hence only a subset is used.

### Tools used:
- Pytorch : Creates customised CNN model 
- OpenCV : For processing images and real-time capture
- CNN : Artificial neural networks used to process pixel data

### Result:

**Link to a live demonstration of the working of the project** - https://drive.google.com/file/d/1XaIQvxkScxhWYloBcUy3XTcHgES-2YFp/view

### Conclusion:

The proposed model is doing good at predicting the letters. As we increase the number of epochs the accuracy increases and the loss decreases. The train and validation accuracy at the 9th epoch is 99.23 and 99.48 respectively with loss values of 0.0009 and 0.0005.

### Future work: 
- Creating full sentences  instead of just alphabets
- Customise model for all sign languages
- Creating automatic editors
