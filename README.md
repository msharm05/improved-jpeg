# JPEG Image Compression in Python

The main goal of this project was to design an iterative image compression post-processing method to improve the quality of JPEG images. This post-processing technique uses the knowledge of the transform coding process in order to constraint what the post-processed image will be. Please follow JPEG_Python_NB.ipynb for the detailed step-by-step implementation of JPEG and the post-processing technique. 

### Project Summary
* Implemented JPEG image compression and decompression stages in Python from scratch using block DCT-2D and inverse DCT-2D.
* Improved the algorithm by developing an iterative post-processing denoising method which reduces artifact appearance in the image after  decompression stage.
* Compared the rate-distortion curves (PSNR, MSE, and SSIM) of JPEG, JPEG+Denoising, and JPEG2000.
