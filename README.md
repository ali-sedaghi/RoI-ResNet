# RoI-ResNet
Region of Interest (RoI) based Bottleneck Residual Network trained on FER2013 dataset.

The idea behind applying RoI comes from [Classifying a specific image region using
convolutional nets with an ROI mask as input](https://arxiv.org/abs/1812.00291) paper.

![block](https://user-images.githubusercontent.com/45814362/196834262-e2d222d0-0663-42b7-a250-d1f62c22f78b.jpg)

Our model achieved an accuracy of 70.2 percent on FER2013 test set.

This model is used on an end-to-end network for facial expression recognition task.
For more information visit our [RetinaFace Emotion Detection](https://github.com/ali-sedaghi/RetinaFace-Emotion-Detection) repository.


## Training
This model is trained on Facial Expression Recognition 2013 (FER2013) dataset for 30 epochs.
For best results you should train it for 120~150 epochs.
Fully trained model can be found [here](https://drive.google.com/file/d/1At3fv5F_47z8yidllaTveoS13itIqgkf/view?usp=sharing).

You can train this model on a desired dataset by providing RoI masks.
