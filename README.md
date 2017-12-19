# ml-project
Objective: we try to identify different people when we get a new picture.


In this project, We learned “face_recognition” package by ourselves. With this package, we can find the faces in the picture and determine whether the face match trained picture or not.

What’s more, we achieve dynamic face-recognition using this package. The code and reults show in “filename”, and we make a video to show this function. Open “WeChatSight16.mp4” to check it.

Besides, we also establish a cnn neural network to achieve face classification just like that in lab8. We tried to modify the network by ourselves to achieve multi-classification. But the accuracy is too low. So, we only achieve binary classification. As for this part, the code and results show in”filename”

Note: we don’t run this project on GPU, so our input shape is (64,64,3). After 10 epochs, val_acc is around 90%.
      Our pictures are downloaded from lfw_funneled dataset. 
