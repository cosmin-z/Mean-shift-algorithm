Enjoy reading!

# Mean shift algorithm - Computer vision

This Repository refers to the project of the course [Computer Vision](https://curriculum.maastrichtuniversity.nl/education/partner-program-master/data-science-decision-making/courses-curriculum) at the University of Maastricht 2023.

In this folder you'll find:

*  the report
*   meanshift_not_optimazed notebook where you can find the implementation of the points 1 and 2
*   Meanshift_optimizaed notebook where you can find the rest of the assignment
*   image_plots folder > here you can find the main images used for the report, and in each subfolder all attempts with the different r and c

## Abstract

Mean-shift Clustering is an unsupervised learning algorithm based on clusters using sliding windows and centroids. The idea is to start around a point and apply a sphere(window) and “shifting to the mean” in an iterative way around the neighbors in order to find the centroid that presents that pixel. From this we can deduce that the number of clusters is not pre-determined but is decided during the calculation and depends on the size of this sphere.


## An interesting result
This picture was taken by me (a landscape in Maastricht, a city that I love)
Before clustering => ![cow](https://github.com/cosmin-z/Mean-shift-algorithm/assets/61350549/7c1a058c-f675-4bcf-a897-f927962c3e8d)

After clustering => ![cowresized_image jpg5d_segmented_image_c4_r42](https://github.com/cosmin-z/Mean-shift-algorithm/assets/61350549/8aec28bf-90a4-4603-8f2f-a0388edf1396)

