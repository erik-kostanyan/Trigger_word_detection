## Trigger Word Detection 
 
Keyword detection is used by many famous modern technologies like Amazon Alexa and Apple Siri.
We want the device to start listening when we say a specific keyword, in our case the keyword is "activate".

We will train a model that should recognise and react whenever we say the keyword. 
We will be adding a "chime" sound whenever a keyword is recognized.

## Code

You can follow the precise steps in the 'Trigger_word_detection.ipynb' notebook, with explanations and examples for each step.

## Folders 

Here's a quick overview of the folder structure of this project.

- 'audio_examples': The "chime" soundbite & an example of a training data entry.
- 'exported_audio': The exported soundbites of a couple of examples from along the way.
- 'models': Presaved models we can load in with TensorFlow. We can add our models here if we wish.
- 'raw_data': The 3 main subfolders we use to construct our training data set.
- 'XY_dev' & 'XY_train': Folders to store and load the training and dev set to train the models.

