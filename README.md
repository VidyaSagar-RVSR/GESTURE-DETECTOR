Its a gesture detection model made by using concepts of transfer learning and Tensorflow object detection API.

TRANSFER LEARNING:
 Transfer learning is a machine learning method where,
 we reuse a pre-trained model as the starting point for a model on a new task.




0.Setup paths
-->seting up the working paths

1.Label  maps

-->Created to label the classes or dataset.

2.Create TF records
-->The TF record format is a simple format for storing a sequence of binary records.

ADVANTAGES:
it makes it easy to combine multiple datasets and integrates seamlessly with the 
data import and preprocessing functionality provided by the library. 
Especially for datasets that are too large to be stored fully 
in memory this is an advantage as only the data that is required at the time (e.g. a batch) is 
loaded from disk and then processed. 
Another major advantage of TFRecords is that it is possible to 
store sequence data — for instance, a time series or 
word encodings.

3.Downloading pre trained tensorflow model zoo
-->we are downloading tensorflow detection model zoo because it has pretrained models
which are used for categorise outputs.Here we are going to use ssd(single shot detector) model.There are
lot of various ,models available,depending on datasets the models are preferred.

There are lot of pre trained models available,for eg VGC16 for image classification.

4.Copy model to training folder

5.Update config parameter (for transfer learning)

-->There are lot of pre definded codes and steps,we just need to chane the parameters and
 paths depending for our model.

6.Train our model

-->once every step parameters given ,run the command on command propmt for training.

7.LOAD our model

-->after training,load our model to detect in real time (Now it has
experience or training based what we trained)

8.Detect in real time

-->Now run the model to detect in real time.
