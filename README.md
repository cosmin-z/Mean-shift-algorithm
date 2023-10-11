

# Mean shift algorithm - Computer vision

This Repository refers to the project of the course [Computer Vision](https://curriculum.maastrichtuniversity.nl/education/partner-program-master/data-science-decision-making/courses-curriculum) at the University of Maastricht 2023.

In this folder you'll find:

*  the report (Enjoy reading!)
*   meanshift_not_optimazed notebook where you can find the implementation of the points 1 and 2
*   Meanshift_optimizaed notebook where you can find the rest of the assignment
*   image_plots folder > here you can find the main images used for the report, and in each subfolder all attempts with the different r and c

## Abstract

Mean-shift Clustering is an unsupervised learning algorithm based on clusters using sliding windows and centroids. The idea is to start around a point and apply a sphere(window) and “shifting to the mean” in an iterative way around the neighbors in order to find the centroid that presents that pixel. From this we can deduce that the number of clusters is not pre-determined but is decided during the calculation and depends on the size of this sphere.


## An interesting result
This picture was taken by me (a landscape in Maastricht, a city that I love)

<div style="display: flex; align-items: center; justify-content: space-between;">
      <img width="300px" height:"400px" src="https://raw.githubusercontent.com/cosmin-z/Mean-shift-algorithm/main/image_plots/cow.jpeg" alt="cowresized_image jpg5d_segmented_image_c4_r42">
    <img style="margin-left:12px;" width="500px" height:"600px" src="https://raw.githubusercontent.com/cosmin-z/Mean-shift-algorithm/main/image_plots/other_images/cowresized_image.jpg5d_segmented_image_c4_r42.png" alt="cow">
  </div>
</div>
<br>
In this case is interesting that even if we increase the radius of the cluster the cow is still present and also there is still an understandable division between the road and the pavement.




