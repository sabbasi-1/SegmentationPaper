# SegmentationPaper
This is the implementation of the paper Ayadi W, Elhamzi W, Atri M. A deep conventional neural network model for glioma tumor segmentation. Int J Imaging Syst Technol. 2023;1‐13. doi:10.1002/ima.22892
Paper proposed a novel architecture similar to a UNET
My implemenation of the architecture had some minor changes by adding upsampling and using a final Conv2D layer instead of the proposed Fully Connected Layer
The Dataset used is the same used in the Paper i.e BraTS 2018
The model converged to its peak accuracy in under 10 epochs
