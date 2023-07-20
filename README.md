# VIS-NIR Tutorial 

For dual VIS/NIR workflows, a visible image is used to identify an image mask for the plant material. The get nir function is used to get the NIR image that matches the VIS image (must be in same folder, with similar naming scheme), then functions are used to size and place the VIS image mask over the NIR image. This allows two workflows to be done at once and also allows plant material to be identified in low-quality images. We do not recommend this approach if there is a lot of plant movement between capture of NIR and VIS images.

To run a VIS/NIR workflow over a single VIS image there are two required inputs:

Image: Images can be processed regardless of what type of VIS camera was used (high-throughput platform, digital camera, cell phone camera). Image processing will work with adjustments if images are well lit and free of background that is similar in color to plant material.
Output directory: If debug mode is set to 'print' output images from each intermediate step are produced.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/danforthcenter/plantcv-tutorial-vis-nir/HEAD?labpath=index.ipynb)

## Tutorial tags/keywords

ROI, region of interest, RGB, Near-infrared,NIR analysis, single plant, Maize, threshold methods 


