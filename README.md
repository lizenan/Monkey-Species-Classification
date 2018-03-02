# Monkey-Species-Classification
key words: inception v3, tensorflow, sklearn, transfer learning, kaggle dataset<br>
This is a retrained model based on tensorflow pretrained model-2016-08-28 for ImageNet. 2 convolution layers has been added.<br>
the parameters of inception v3 have been frozen.<br>
this model can identify different monkey species from kaggle pictures<br>
<br>
frozen layers' outputs are fixed, so this program implies a faster way to train this model.<br>

data:https://www.kaggle.com/slothkong/10-monkey-species/data<br>
pretrained checkpoint: http://download.tensorflow.org/models/inception_v3_2016_08_28.tar.gz<br>
<br>
PS: this just a prototype. accuracy can be improved with more computations.<br>
<br>
this model is inspired by Aurélien Geron@https://github.com/ageron
