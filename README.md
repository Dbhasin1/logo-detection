# Logo-Detection-using-YOLO

This repository contains the code that converts FlickrLogo-47 Dataset annotations to the format required by YOLO. It also has the YOLO configuration file used for the Logo Detection.

## Project Description

Companies and advertisers need to know their customers to assess their business and marketing strategies. While the amount of information shared on social media platforms is gargantuan, a lot of it is unstructured and untagged, and particularly so for visual data. Users can voluntarily tag their preferred brands in their posts, but wouldn't it be much better for the companies to know every time their brand is being publicly shared?

In this project, I built a general-purpose logo detection API. To avoid re-training the network for each new company using the service, logo detection and identification are split in two logically and operationally separate parts: first, we find all logos in the image with a YOLO detector (using the Keras implementation of keras-yolo3), and then we check for similarity between the proposed logos and an input uploaded by the customer (for example, the company owning the logo), by computing cosine similarity between features extracted by a pre-trained Inception network

## Object Detection in a image
![](2020-10-21%20(2).png)

![](2020-10-21%20(3).png)

This has been done on colab and the link is https://colab.research.google.com/drive/1TX2wy2h17nnroCjKB8C54njXVx_PW2xg .

