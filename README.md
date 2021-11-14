

reimplement Saliency Estimation using a non-parametric vision model of Naila Murray in C++

Environments:
Ubuntu1604  OpenCV3.4

Build & Run:

cd saliency_gabor

step1:  g++ -std=c++11 -o saliency_gabor saliency_gabor.cpp `pkg-config --cflags --libs opencv`

step2: ./saliency_gabor  deep21.bmp
 
original image

![image](https://github.com/NanKeRen2020/saliency_gabor/blob/main/cpp/deep21.bmp)

result image

![image](https://github.com/NanKeRen2020/saliency_gabor/blob/main/cpp/result.png)

sum of result image

![image](https://github.com/NanKeRen2020/saliency_gabor/blob/main/cpp/result_sum.png)


Enjoy!!!