# underwater-image-super-resolution
 
underwater images are used in oceanic engineering and various applications such as underwater robot vision and underwater autonomous vehicles, etc. single image super-resolution (SISR) methods can improve the resolution and quality of underwater images. 

Real-Enhanced Super-Resolution Generative Adversarial Network (Real-ESRGAN) is one of the recent practical models that have been used to generate higher-resolution images from lower-resolution input images. 
in this work, we use this model to increase the resolution and quality of underwater images. In our proposed approach, the pre-trained generator and discriminator networks of the real-esrgan model are fine-tuned using underwater image datasets.

We used the USR-248 dataset and UFO-120 dataset to fine-tune the real-esrgan model.
our fine-tuned model produces images with better resolution and quality compared to the original real-esrgan model

datasets can be downloaded from the link below : 

USR-248 dataset :

https://irvlab.cs.umn.edu/resources/usr-248-dataset

UFO-120 Dataset :

https://irvlab.cs.umn.edu/resources/ufo-120-dataset

All details and fine-tuning parameters are available in the finetune_realesrgan_x4plus.yml file.

It is also possible to test the original real-esrgan model and fine-tuned model in the fine_tune_underwater.ipynb file

Below are some outputs of the real-esrgan model and the fine-tuned model :
