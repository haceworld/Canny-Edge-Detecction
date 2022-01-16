# Canny-Edge-Contrastive-Enhanced-Detection (CECED)

Edges are made up of crucial and relevant particular information and features. By employing an edge detector on an image, the amount of data that has to be processed can be reduced, and the information that is deemed less significant can be filtered. The CEED-Canny strategy combines the Local morphological contrast enhancement and the Canny edge detection in some research papers. The steps in CECED process are as follows:

1.) Collection of the original pixel's value, as well as the local minimum and maximum.

2.) The image's morphological contrast is increased.

3.) To reduce noise, Gaussian smoothing is applied.

5.) A non-maximum suppression method is utilized.

6.) The hysteresis thresholding technique is adopted.

This is the code for preproessing original image(s) to CECED image(s). This code will help researcher process their images into CECED images. This code process single and multiple images in a folder and save them in another folder. Kindly ensure that the right directory path is called properly. The result of the code is presented below:


![65](https://user-images.githubusercontent.com/61402731/149646870-16d2d041-d0e2-47c7-bdd3-abbf0012e726.jpg)

Original CXR image


![65_1_CECED](https://user-images.githubusercontent.com/61402731/149646872-52b86505-8161-4f84-992f-8b9701960441.jpeg)

CECED CXR image
