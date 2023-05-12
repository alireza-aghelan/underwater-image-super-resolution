# Underwater image super-resolution

In this project, we fine-tune the pre-trained Real-Enhanced Super-Resolution Generative Adversarial Network (Real-ESRGAN) model for underwater image super-resolution. We use USR-248 dataset for fine-tuning the model. The proposed model generates more realistic and higher-quality images compared to the original Real-ESRGAN model.

The download link of the USR-248 dataset:

https://irvlab.cs.umn.edu/resources/usr-248-dataset

The Real-ESRGAN code is borrowed from https://github.com/xinntao/Real-ESRGAN.

Results for different underwater images are shown in the following figures.

![1](https://github.com/alireza-aghelan/underwater-image-super-resolution/assets/47056654/deeb8988-f779-4aec-8aca-7ba277ddc54b)
![2](https://github.com/alireza-aghelan/underwater-image-super-resolution/assets/47056654/87d9c093-3e69-49d8-b775-2cd82a56afa4)

Columns 1–4 are input images, original Real-ESRGAN outputs, fine-tuned Real-ESRGAN outputs, and original images.

![3](https://github.com/alireza-aghelan/underwater-image-super-resolution/assets/47056654/e0064783-b33e-4d86-ae1e-9e95025bf4ba)
![4](https://github.com/alireza-aghelan/underwater-image-super-resolution/assets/47056654/d575c70c-a203-464b-ae6e-144110267bcc)

Magnified regions of underwater images to further identify differences.
