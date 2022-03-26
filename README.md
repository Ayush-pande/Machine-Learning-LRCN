# Machine-Learning-LRCN
Long-Term Recurrent Convolutional Network (LRCN) is combination of a deep hierarchical visual feature extracted (such as CNN) with a model that can learn to recognise sequential data (inputs or outputs) , visual, linguistic , or otherwise. LRCN works by passing each visual input through a feature transformation with parameters , usually a CNN , to produce a fixed- length representation. The outputs are then passed into a recurrent sequence learning module.
In this project , we will be implementing our model for dynamic and static perdictions on videos. We are using CNN combined with LSTM for making predictions on acitivities performed in the video.
In dynamic prediction, we are making predictions throughout the length of the video.
In static prediction , we will make one prediction for the whole video.
