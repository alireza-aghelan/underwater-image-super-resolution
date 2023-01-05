# underwater-image-super-resolution

In this work, we modify the Real-Enhanced Super-Resolution Generative Adversarial Network (Real-ESRGAN) model to enhance the resolution and quality of underwater images. In our proposed approach, the pre-trained generator and discriminator networks of the Real-ESRGAN model are fine-tuned using underwater image datasets. 

We used USR-248 and UFO-120 datasets to fine-tune the Real-ESRGAN model. Our fine-tuned model produces images with better resolution and quality compared to the original model.

Datasets can be downloaded from the link below: 

USR-248 Dataset:

https://irvlab.cs.umn.edu/resources/usr-248-dataset

UFO-120 Dataset:

https://irvlab.cs.umn.edu/resources/ufo-120-dataset

All details and fine-tuning parameters are available in the finetune_realesrgan_x4plus.yml file.

It is also possible to test the original real-esrgan model and fine-tuned model in the fine_tune_underwater.ipynb file.

The Real-ESRGAN code is borrowed from https://github.com/xinntao/Real-ESRGAN.

Below are some outputs of the real-esrgan model and the fine-tuned model:

![1](https://user-images.githubusercontent.com/47056654/200174179-1c8533e2-cf81-4715-a045-80a11ed4d1d4.jpeg)
![2](https://user-images.githubusercontent.com/47056654/200174206-1d7eb2f3-f216-43dd-9c75-8c24278ae807.jpeg)
![3](https://user-images.githubusercontent.com/47056654/200174224-e6598cc9-3b53-4064-a776-b7206bf5eba8.jpeg)
![4](https://user-images.githubusercontent.com/47056654/200174245-4ab4f300-6a35-416e-bf22-24cf24aa6431.jpeg)
![5](https://user-images.githubusercontent.com/47056654/200174289-74b240fa-619a-4316-85cf-bc493474c1f6.jpeg)

Columns 1–4 are the LR degraded images, original Real-ESRGAN outputs, fine-tuned model outputs after 8 epochs, and fine-tuned model outputs after 20 epochs.

Magnified regions of underwater images for better comparison between models:

![6](https://user-images.githubusercontent.com/47056654/200174311-1708bf01-55ef-470a-9a32-0f73cd3753db.jpeg)
![7](https://user-images.githubusercontent.com/47056654/200174325-c64e3c16-2491-4e94-b3aa-7d6ccea66b38.jpeg)
![8](https://user-images.githubusercontent.com/47056654/200174348-853233ee-23d1-49f6-98ea-f6f7e367a56f.jpeg)


