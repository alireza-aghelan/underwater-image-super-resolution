# underwater-image-super-resolution

Underwater images are used in oceanic engineering and various applications such as underwater robot vision, etc. Single image super-resolution (SISR) methods can improve the resolution and quality of underwater images. 
 
In this work, we use Real-Enhanced Super-Resolution Generative Adversarial Network (Real-ESRGAN) model to enhance the resolution and quality of underwater images. In our proposed approach, the pre-trained generator and discriminator networks of the real-esrgan model are fine-tuned using underwater image datasets.

The code of the Real-ESRGAN model is borrowed from https://github.com/xinntao/Real-ESRGAN

We used the USR-248 dataset and UFO-120 dataset to fine-tune the real-esrgan model.
Our fine-tuned model produces images with better resolution and quality compared to the original real-esrgan model.

Datasets can be downloaded from the link below: 

USR-248 Dataset:

https://irvlab.cs.umn.edu/resources/usr-248-dataset

UFO-120 Dataset:

https://irvlab.cs.umn.edu/resources/ufo-120-dataset

All details and fine-tuning parameters are available in the finetune_realesrgan_x4plus.yml file.

It is also possible to test the original real-esrgan model and fine-tuned model in the fine_tune_underwater.ipynb file

Below are some outputs of the real-esrgan model and the fine-tuned model:

1–4 columns are the LR degraded images, the outputs of the original real-esrgan, the outputs of the fine-tuned model after 8 epochs, and the outputs of the fine-tuned model after 20 epochs.

![1](https://user-images.githubusercontent.com/47056654/199535861-112a0006-7cbf-4d52-aeaf-6f3f9ff6be8e.jpeg)
![2](https://user-images.githubusercontent.com/47056654/199536184-264061c1-2a02-429b-9483-64c94e6f019e.jpeg)
![3](https://user-images.githubusercontent.com/47056654/199536638-e82930fd-13eb-475a-b0a9-e8a770a41676.jpeg)
![4](https://user-images.githubusercontent.com/47056654/199537622-b66d4e87-c683-4c0f-8aaf-3be48c1a93fd.jpeg)
![5](https://user-images.githubusercontent.com/47056654/199537861-7d456cdf-e222-4356-9d23-cb04728f3ec9.jpeg)

Magnified regions of underwater images for better comparison between models:

![6](https://user-images.githubusercontent.com/47056654/199537924-37a5e71c-c4ae-4a6a-a175-75b3f0778ec3.jpeg)
![7](https://user-images.githubusercontent.com/47056654/199537972-f71f3272-3c8d-467c-af97-83f977948eb5.jpeg)
![8](https://user-images.githubusercontent.com/47056654/199538018-9a837c5a-5dea-4044-9c88-316abc48a822.jpeg)
![9](https://user-images.githubusercontent.com/47056654/199538063-71bade92-ab9a-4b0e-a2b9-d6b6bb75dda6.jpeg)





