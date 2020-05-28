# Cell2Arts
This project uses CycleGAN to perform image to image translation and make a short artsy clip combining the [fluid motion of cell](https://drive.google.com/file/d/1BMKixrCCqmxqJJ6VJxF7zu1KJyetjE2w/view?usp=sharing) and aesthetic of abstract paintings. For example,


<img src="https://github.com/Hazarre/Cell2Arts/blob/master/image/cell.jpg" width="360" height="360" src="https://github.com/Hazarre/Cell2Arts/blob/master/image/arts.jpg" width="360" height="360"/>



See an example [video clip](https://drive.google.com/file/d/17Fp8pUerYc1iNXWxBsFtNVMZCc22Z5Vm/view?usp=sharing). Please view in smaller window since the videos are generated using 256x256 pixels.

See the [report](https://docs.google.com/document/d/1c-tMGg52UeaOi2xyilOuW7Vp3kLkTD1hvgQzjMHomK4/edit?usp=sharing) for project detials.

Data source: 
1. Cell Image Data(https://www.epfl.ch/labs/cvlab/data/data-em/).
2. Abstract Arts is obtained from the Internet with Google Image Download(https://github.com/hardikvasa/google-images-download). 

Code Snippets source are largely gathered from: 
1) The original [CycleGAN github page](https://github.com/junyanz/pytorch-CycleGAN-and-pix2pix/tree/master/) by Jun-Yan Zhu.
