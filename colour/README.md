# ColorClassifier
Simple Color Classifier with TensorFlow (Python).

The classifier is not so accurate (80% accuracy, depending on the size of the dataset and the noise) because no filter was applied since this is just a simple example. You can add your own filter. Remember this is a classifier based on human perception, not on a mathematical calculus, that's why noise is not easy to remove. 

This project was inspired by <a href = 'https://www.youtube.com/watch?v=y59-frfKR58&list=PLRqwX-V7Uu6bmMRCIoTi72aNWHo7epX4L'>this </a> youtube playlist.

Please consider supporting the <a href = https://www.youtube.com/user/shiffman > author </a> of that playlist.


The project is based on a crowdsourced database and it uses TensorFlow to build the model and process the data. I also used Tkinter to build a (VERY) simple (quite bad) GUI, just to test the model with user-given data.

More on Tensorflow: https://www.tensorflow.org/

More on Tkinter: https://wiki.python.org/moin/TkInter

If you don't need the GUI, this is the right order to execute the scripts in order to get the data, process them and create and save the model:

1. getData.py

2. processData.py

3. train.py

