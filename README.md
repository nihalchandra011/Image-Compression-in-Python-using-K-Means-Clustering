# Image-Compression-in-Python-using-K-Means-Clustering
This project aims to implement image compression using the K-Means Clustering algorithm in Python.

**Description**<br>
Image compression is the process of reducing the file size of an image without compromising on its visual quality. This is achieved by reducing the number of colors used in the image. The K-Means Clustering algorithm is used to group similar colors together and replace them with a single representative color, thereby reducing the number of colors used in the image.<br>

In this project, we use the K-Means algorithm to pick the 'k' most prominent colors in an image and alter the remaining pixels to one of these clusters. This results in a compressed image with reduced file size and minimal loss in image quality. The number of colors used in the compressed image is determined by the value of 'k' chosen for the K-Means algorithm.

**Libraries**<br>
The project is implemented in Python 3.6 environment using Jupyter Notebook and the following libraries:
- Numpy v1.19.1
- Matplotlib v3.3.1
- Sci-kit learn v0.23.2

**Implementation**<br>
To run the project, open the 'Image Compression in Python using K-Means Clustering.ipynb' file using Jupyter Notebook and click on the Run button |>>|. The image used in this project for demonstration is obtained from Illumination Entertainment images.

The project starts by loading the image using the Numpy library and converting it to a 2D array of pixels. The K-Means Clustering algorithm is then applied to the pixels, grouping similar colors together and replacing them with a representative color. The compressed image is then reconstructed using the reduced set of colors and saved. The results of the compression are then analyzed by looking at different values of k and observing the corresponding scatter plot and compressed image.

**Note**<br>
The compressed image may not look exactly the same as the original image, but the visual quality should still be preserved to a large extent. The number of colors used in the compressed image will be less than the original image, making it a smaller file size. The optimal value of k can be determined by analyzing the results and finding the point where there is minimal loss in image quality and maximum reduction in file size.
