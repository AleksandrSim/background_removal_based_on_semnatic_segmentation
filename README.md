# background_removal_based_on_semnatic_segmentation

I have developed a very simple, yet effective solution to remove a background from an image. First, we precisely detect an object, using semantic segmentation. After that, we take contours from a segmented object and apply them to the original image. Everything that goes beyond those contours will be considered as a background and, hence, will be removed.

Here are the results:

Original image - ![alt text](https://ibb.co/vw7kfZy)
Segmented - ![alt text](https://ibb.co/tmh6PfL)
Background removed - ![alt text](https://ibb.co/vQfxvH4)
