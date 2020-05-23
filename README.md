# Mask Detection
Many measurements have been taken to tackle the COVID-19 pandemic. Among which wearing mask is one way to prevent spreading the virus. The aim of this work is to detect if a person is wearing a mask or not. With this objective, a machine learning model is developed which leverages transfer learning to detect mask. The training data for this model is collected from multiple sources. <br>

For collecting human faces with mask, a subset (1000 images) of the MAFA dataset (can be found in http://www.escience.cn/people/geshiming/mafa.html) is used. For collecting human faces without mask, a subset of (1000 images) the UTKFace dataset (can be found in https://susanqq.github.io/UTKFace/) is used.

• Keras is used to develop the model. <br>
• Resnet-50 is used to train the model. <br>
• Data augmentation (horizontal and vertical shift, flip) is performed as a preprocessing step. <br>
• 99% accuracy is achieved while testing with hold-out images. <br>

# Training Data
The training data of this model can be found in the following link:<br>
https://www.dropbox.com/sh/20zrofhd10f3dev/AACBL2j6I4fu9KrDLBhWI5U2a?dl=0

# How to run:
For code and performance, check the maskDetection.ipynb file.
