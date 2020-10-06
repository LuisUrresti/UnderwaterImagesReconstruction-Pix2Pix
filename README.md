# Underwater imagenes reconstruction 

This proyect was made with the objetive of reconstructing the images received by an underwater drone pilot using generative adversarial networks.

The input images has not a very clear visibility because of the scattering effect of the water and the water turbidity. They have very low resolucion (300 x 170), thats because the umbilical wide that conects the drone with the pilot has a very low band width. For thease reasons, I use GANs to reconstructing the input images and improve its visibility and resolution. See some results:

Input Image Example 1

![alt text](https://github.com/LuisUrresti/UnderwaterImagesReconstruction-Pix2Pix/blob/main/results/input.png)

Output Image Example 1

![alt_text](https://github.com/LuisUrresti/UnderwaterImagesReconstruction-Pix2Pix/blob/main/results/output.png)

Input Image Example 2

![alt text](https://github.com/LuisUrresti/UnderwaterImagesReconstruction-Pix2Pix/blob/main/results/input_1.png)

Output Image Example 2

![alt_text](https://github.com/LuisUrresti/UnderwaterImagesReconstruction-Pix2Pix/blob/main/results/output_1.png)

Here I show the differences between the input image, the orignal  image and the reconstructed image

Example 1

![alt text](https://github.com/LuisUrresti/UnderwaterImagesReconstruction-Pix2Pix/blob/main/results/example_0.png)


References:

[1]P. Isola, J.-Y. Zhu, T. Zhou, y A. A. Efros, «Image-to-Image Translation with Conditional Adversarial Networks», en 2017 IEEE Conference on Computer Vision and Pattern Recognition (CVPR), Honolulu, HI, jul. 2017, pp. 5967-5976, doi: 10.1109/CVPR.2017.632.
