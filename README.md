# PlayWithCifar
Objective: Image Classification on Cifar 10 dataset


Requirements: Since my google credits are expired I have decided to build this project on Google Colab. The project will use keras with tensorflow as backend. We don't need to install libraries on Colab and can start straight away. 

Use below link to open the notebook and run the code:

https://colab.research.google.com/drive/1654IUaU8VR2mFcemMC_E5E_3Bp6JY2lq


Model:

Since I am using Google Colab it will be little difficult to train heavy models like WideResnet which in turn can give really good accuracy(ex- https://github.com/fastai/fastai/blob/master/examples/cifar.ipynb) and tune them in a single day(I planned to finish this in a day), so I have decided to go with not so famous but light architecture 'DavidNet'. There is an online competition about fast training called DAWNBench, and the winner was David C. Page, who built a custom 9-layer Residual ConvNet, or ResNet. In the following, we refer to this model as “DavidNet”, named after its author.



