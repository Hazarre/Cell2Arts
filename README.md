# Cell2Arts
This project uses CycleGAN to perform image to image translation and make a short artsy clip combining the [fluid motion of cell](https://drive.google.com/file/d/1BMKixrCCqmxqJJ6VJxF7zu1KJyetjE2w/view?usp=sharing) and aesthetic of abstract paintings. For example,


<img src="https://github.com/Hazarre/Cell2Arts/blob/master/image/cell.jpg" width="200" height="400" />

![Image of Cell](https://github.com/Hazarre/Cell2Arts/blob/master/image/cell.jpg)
![Image of Painting](https://github.com/Hazarre/Cell2Arts/blob/master/image/arts.jpg)


![Image of Cell](https://drive.google.com/file/d/1Bp8lvru82lhfA7tNFbfmYO4dI_jyWLCT/view)
![Image of Painting](https://drive.google.com/file/d/1DWtix0irf8lDC4v_tIA_5ia2XSGfHoas/view)

See an example [video clip](https://drive.google.com/file/d/17Fp8pUerYc1iNXWxBsFtNVMZCc22Z5Vm/view?usp=sharing). Please view in smaller window since the videos are generated using 256x256 pixels.

See the [report](https://docs.google.com/document/d/1c-tMGg52UeaOi2xyilOuW7Vp3kLkTD1hvgQzjMHomK4/edit?usp=sharing) for project detials.

Data source: 
1. Cell Image Data(https://www.epfl.ch/labs/cvlab/data/data-em/).
2. Abstract Arts is obtained from the Internet with Google Image Download(https://github.com/hardikvasa/google-images-download). 

Code Snippets source are largely gathered from: 
1) The original [CycleGAN github page](https://github.com/junyanz/pytorch-CycleGAN-and-pix2pix/tree/master/) by Jun-Yan Zhu.
