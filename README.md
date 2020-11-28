# FPGA-Based-Image-Processing-Module

This repository contains open source FPGA-based image processing modules, including:

	1. Sharpen Filter: to sharp the images - more information -> https://en.wikipedia.org/wiki/Unsharp_masking
	2. Smooth Filter with 3 by 3 kernel window (Gaussian Approximation) : to smooth the images
	3. Sobel Filter : to detect the egdes - more information -> https://en.wikipedia.org/wiki/Sobel_operator

All these modules use Sliding Window technique to increase the throughput of modules.

In each folder there is VHDL codes and respective documentation.