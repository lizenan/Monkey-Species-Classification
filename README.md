# Monkey-Species-Classification
key words: inception v3, tensorflow, sklearn, transfer learning, kaggle dataset
This is a retrained model based on tensorflow pretrained model-2016-08-28 for ImageNet. 2 convolution layers has been added.
the parameters of inception v3 have been frozen.
this model can identify different monkey species from kaggle dataset pictures

frozen layers' outputs are fixed, so this program imply a faster way to train this model.

data:https://www.kaggle.com/slothkong/10-monkey-species/data
pretrained checkpoint: http://download.tensorflow.org/models/inception_v3_2016_08_28.tar.gz

PS: this just a prototype. accuracy can improve with more computation.

this model is inspired by Aurélien Geron@https://github.com/ageron
