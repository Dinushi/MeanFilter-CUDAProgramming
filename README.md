# MeanFilter-CUDAProgramming

A mean filter ( a simple method used in image processing to reduce noise in image) is implemented using CUDA programming to parallely process an image on a GPU.

The CUDA program applies a 𝑘 𝑥 𝑘 kernel filter to a given image (Gray Scale image) and produces the result. CPU (host) program reads the image file and converts to a raw image matrix. Then passes the matrix to the GPU and GPU kernel applies the mean filter to the image and return the result image back to the CPU.
