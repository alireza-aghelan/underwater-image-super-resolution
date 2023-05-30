# Underwater image super-resolution

In this project, we fine-tune the pre-trained Real-Enhanced Super-Resolution Generative Adversarial Network (Real-ESRGAN) model for underwater image super-resolution. We use USR-248 dataset for fine-tuning the model. The proposed model generates more realistic and higher-quality images compared to the original Real-ESRGAN model.

The download link of the USR-248 dataset:

https://irvlab.cs.umn.edu/resources/usr-248-dataset

The Real-ESRGAN code is borrowed from https://github.com/xinntao/Real-ESRGAN.

Results for different underwater images are shown in the following figures.

![1](https://github.com/alireza-aghelan/underwater-image-super-resolution/assets/47056654/de5277c6-7119-4a85-8ac5-9a341861bf36)
![2](https://github.com/alireza-aghelan/underwater-image-super-resolution/assets/47056654/f78bc064-505e-4491-992f-b4f353069905)

Columns 1–4 are input images, original Real-ESRGAN outputs, fine-tuned Real-ESRGAN outputs, and original images.

![3](https://github.com/alireza-aghelan/underwater-image-super-resolution/assets/47056654/5663be83-9b0e-47c8-9922-1995b3d41e09)
![4](https://github.com/alireza-aghelan/underwater-image-super-resolution/assets/47056654/55f16a00-152a-41af-bb08-233cc65c425c)

Magnified regions of underwater images to further identify differences.
