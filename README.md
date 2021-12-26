# ITC-Tobacoo
This repo contains code for the Smart India Hackathon 2019 project. Tobacco classification is a difficult problem, and only highly expert humans can correctly tell the grade of tobacco. This project is an effort to automate this process using an AI-based system. Our method predicts the grade of tobacco leaves using images based on color, texture, and ripeness. 

This project was built for ITC Ltd.

## Old implementation dataset

This dataset was easy as anyone can easily classify these images. No expertise needed.

<img src="old/train/Ayu/1.jpg" width="200"> <img src="old/train/Devu/1.jpg" width="200">
<img src="old/train/Ksku/1.jpg" width="200"> <img src="old/train/Manu/1.jpg" width="200">

Solution: Tensoflow based CNN to classify the images for various grades of the tobacco.


## New implementation dataset

This dataset is very difficult because each of these images belong to different tobacco grade.

<img src="new/dataset/1.jpg" width="200"> <img src="new/dataset/2.jpg" width="200">
<img src="new/dataset/6.jpeg" width="200"> <img src="new/dataset/7.jpeg" width="200">

Solution

Classical features were extracted from images <br>
1) Gabor
2) LBP
3) Haralik
4) Color RGB
5) Color HSV
6) GLCM
7) Orb
8) And many more ...

and a machine learning model was trained.

<img src="2.png"><br>
<img src="3.png">

## Final System
<img src="1.jpg">
