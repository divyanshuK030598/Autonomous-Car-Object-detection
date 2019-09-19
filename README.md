# Autonomous-Car-Object-detection
1). Car detection is the first and foremost work for building a autonomous car/ self driving cars
2). In the this project we are using the dataset of images captured and build by drive.ai.
3). The YOLO (you look only once) algorithm is used by us for detectiong the multiple object in an image efficiently.
4). Following are the prerequired knowledge and topics for building such system:
    a). Convolutional Neural Networks
    b). Non - max suppression
    c). Anchor box
    d). YOLO
5). Python and other deep learning plateforms (tensorflow , keras) are used to code for the same.


2.1 - Model details

The input is a batch of images of shape (m, 608, 608, 3)
The output is a list of bounding boxes along with the recognized classes. Each bounding box is represented by 6 numbers (p_c, b_x, b_y, b_h, b_w, c)
