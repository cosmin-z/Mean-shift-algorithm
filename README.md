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

<div style="display: flex; align-items: center; justify-content: space-between;">
  <div style="width: 100px; text-align: center;">
    Before clustering
    ![cow](https://github.com/cosmin-z/Mean-shift-algorithm/blob/main/assets/61350549/8c73f832-27ef-4d7a-bebd-1859b1499fa6)
  </div>
  <div style="width: 100px; text-align: center;">
    After clustering
    ![cowresized_image jpg5d_segmented_image_c4_r42](https://github.com/cosmin-z/Mean-shift-algorithm/blob/main/assets/61350549/eb761ec3-3029-43c3-8904-dbceee819b76)
  </div>
</div>





