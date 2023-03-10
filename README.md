# Albumentations-Examples

This repository contains applications and visualizations of the [Albumentations](https://albumentations.ai/docs/) library.

### [Random Crop](https://github.com/albumentations-team/albumentations/blob/master/albumentations/augmentations/crops/transforms.py#L49)
Crop a random part of the input.
![random_crop](https://user-images.githubusercontent.com/50166164/210487145-6de4c8c8-f5b8-47ad-97a1-4697f90aeb46.png)

### [Advanced Blur](https://github.com/albumentations-team/albumentations/blob/master/albumentations/augmentations/blur/transforms.py#L306)
Blur the input image using a Generalized Normal filter with a randomly selected parameters. This transform also adds multiplicative noise to generated kernel before convolution.
![advanced_blur](https://user-images.githubusercontent.com/50166164/210487177-b3eff9b9-ff04-43e2-a382-86c3968c0d86.png)

### [Blur](https://github.com/albumentations-team/albumentations/blob/master/albumentations/augmentations/blur/transforms.py#L36)
Blur the input image using a random-sized kernel.
![blur](https://user-images.githubusercontent.com/50166164/210487200-c60d614a-772d-4f77-86c7-2857c73ddbb4.png)

### [CLAHE](https://github.com/albumentations-team/albumentations/blob/master/albumentations/augmentations/transforms.py#L1298)
Apply Contrast Limited Adaptive Histogram Equalization to the input image.
![clahe](https://user-images.githubusercontent.com/50166164/210487347-7ca42164-9e7f-4f3f-949f-983a1d545aa1.png)

### [Channel Dropout](https://github.com/albumentations-team/albumentations/blob/master/albumentations/augmentations/dropout/channel_dropout.py#L28)
Randomly Drop Channels in the input Image.
![channel_dropout](https://user-images.githubusercontent.com/50166164/210487381-e6b60197-2a34-4a01-b6d0-44b534b62df5.png)

### [Channel Shuffle](https://github.com/albumentations-team/albumentations/blob/master/albumentations/augmentations/transforms.py#L1333)
Randomly rearrange channels of the input RGB image.
![channel_shuffle](https://user-images.githubusercontent.com/50166164/210487398-e2207703-04b6-4091-8549-65e007855bb8.png)

### [Color Jitter](https://github.com/albumentations-team/albumentations/blob/master/albumentations/augmentations/transforms.py#L1829)
Randomly changes the brightness, contrast, and saturation of an image. Compared to ColorJitter from torchvision, this transform gives a little bit different results because Pillow (used in torchvision) and OpenCV (used in Albumentations) transform an image to HSV format by different formulas. Another difference - Pillow uses uint8 overflow, but we use value saturation.
![channel_jitter](https://user-images.githubusercontent.com/50166164/210487444-95c71ff8-93b6-4d98-a1a2-c0530a4cc402.png)

### [Defocus](https://github.com/albumentations-team/albumentations/blob/master/albumentations/augmentations/blur/transforms.py#L410)
Apply defocus transform.
![defocus](https://user-images.githubusercontent.com/50166164/210487514-df4c25c8-2bc3-4c72-8280-07f20f23f1ac.png)

### [Downscale](https://github.com/albumentations-team/albumentations/blob/master/albumentations/augmentations/transforms.py#L1569)
Decreases image quality by downscaling and upscaling back.
![dowscale](https://user-images.githubusercontent.com/50166164/210487556-69dfdb62-c53a-4c99-82c3-d005ed4a9183.png)

### [Emboss](https://github.com/albumentations-team/albumentations/blob/master/albumentations/augmentations/transforms.py#L1958)
Emboss the input image and overlays the result with the original image.
![emboss](https://user-images.githubusercontent.com/50166164/210487566-91bdd1c1-4cf0-4f0c-b77e-067a18d4c9a7.png)

### [Equalize](https://github.com/albumentations-team/albumentations/blob/master/albumentations/augmentations/transforms.py#L1000)
Equalize the image histogram.
![equalize](https://user-images.githubusercontent.com/50166164/210487591-79a01acd-37df-4f58-8ae9-acd05d0b7fb8.png)

# [FancyPCA](https://github.com/albumentations-team/albumentations/blob/master/albumentations/augmentations/transforms.py#L1793)
Augment RGB image using FancyPCA from Krizhevsky's paper "ImageNet Classification with Deep Convolutional Neural Networks"
![fancyPCA](https://user-images.githubusercontent.com/50166164/210487633-e1a1227a-9c7a-460f-8251-9a14669c93db.png)

### [Gauss Noise](https://github.com/albumentations-team/albumentations/blob/master/albumentations/augmentations/transforms.py#L1199)
Apply gaussian noise to the input image.
![gauss_noise](https://user-images.githubusercontent.com/50166164/210487744-733615db-2ab0-4979-8627-51fac8d51345.png)

### [Hue Saturation Value](https://github.com/albumentations-team/albumentations/blob/master/albumentations/augmentations/transforms.py#L878)
Randomly change hue, saturation and value of the input image.
![hue_saturation_value](https://user-images.githubusercontent.com/50166164/210487706-7fce6d39-73fd-42bb-aece-2389d5d266d4.png)

### [Image Compression](https://github.com/albumentations-team/albumentations/blob/master/albumentations/augmentations/transforms.py#L240)
Decreases image quality by Jpeg, WebP compression of an image.
![image_compression](https://user-images.githubusercontent.com/50166164/210487728-5f1e28d8-66b1-4ba5-8673-2da48fa0b2ad.png)

### [Invert Image](https://github.com/albumentations-team/albumentations/blob/master/albumentations/augmentations/transforms.py#L1359)
Invert the input image by subtracting pixel values from 255.
![invert_img](https://user-images.githubusercontent.com/50166164/210499297-918fd101-9ef7-4da6-ba21-53e98e8ce7ea.png)

### [ISONoise](https://github.com/albumentations-team/albumentations/blob/master/albumentations/augmentations/transforms.py#L1263)
Apply camera sensor noise.
![ISONoise](https://user-images.githubusercontent.com/50166164/210499430-aaf86d58-b1b7-4fa4-98cf-32f826c6da8f.png)

### [MultiplicativeNoise](https://github.com/albumentations-team/albumentations/blob/master/albumentations/augmentations/transforms.py#L1725)
Multiply image to random number or array of numbers.
![MultiplicativeNoise](https://user-images.githubusercontent.com/50166164/210499459-160861d0-e07e-48a6-aeee-f23c88944e75.png)

### [PixelDropout](https://github.com/albumentations-team/albumentations/blob/master/albumentations/augmentations/transforms.py#L2325)
Set pixels to 0 with some probability.
![PixelDropout](https://user-images.githubusercontent.com/50166164/210499501-dcb8bd0f-0cab-4255-8e72-4f9278d6b23c.png)

### [Posterize](https://github.com/albumentations-team/albumentations/blob/master/albumentations/augmentations/transforms.py#L958)
Reduce the number of bits for each color channel.
![Posterize](https://user-images.githubusercontent.com/50166164/210499542-c31b1d43-9230-4b05-aa35-9b37ae47d57b.png)

### [RandomBrightnessContrast](https://github.com/albumentations-team/albumentations/blob/master/albumentations/augmentations/transforms.py#L1103)
Randomly change brightness and contrast of the input image.
![RandomBrightnessContrast](https://user-images.githubusercontent.com/50166164/210499589-85eb3e7e-661e-4c87-8ff9-bf30808b9887.png)

### [RandomRain](https://github.com/albumentations-team/albumentations/blob/master/albumentations/augmentations/transforms.py#L394)
Adds rain effects.
![RandomRain](https://user-images.githubusercontent.com/50166164/210499619-bc8b4e12-5f1d-4db2-a05a-b720c63a687d.png)

### [RandomBrightness](https://github.com/albumentations-team/albumentations/blob/master/albumentations/augmentations/transforms.py#L1144)
Randomly change brightness of the input image.
![RandomBrightness](https://user-images.githubusercontent.com/50166164/210499670-46c0657f-0e43-4ce5-b8cd-f97f0e68f3c6.png)

### [RandomContrast](https://github.com/albumentations-team/albumentations/blob/master/albumentations/augmentations/transforms.py#L1170)
Randomly change contrast of the input image.
![RandomContrast](https://user-images.githubusercontent.com/50166164/210499715-4a969a13-3c7e-453e-972b-f78038a69ce1.png)

### [RandomFog](https://github.com/albumentations-team/albumentations/blob/master/albumentations/augmentations/transforms.py#L514)
Simulates fog for the image.
![RandomFog](https://user-images.githubusercontent.com/50166164/210499770-0751d87a-1b3b-42c0-bb0a-6d392787b28a.png)

### [RandomGamma](https://github.com/albumentations-team/albumentations/blob/master/albumentations/augmentations/transforms.py#L1380)
Adds random gamma value to the images.
![RandomGamma](https://user-images.githubusercontent.com/50166164/210499791-c2bf260b-689d-4b72-b4b0-4c66a6502827.png)

### [RandomShadow](https://github.com/albumentations-team/albumentations/blob/master/albumentations/augmentations/transforms.py#L751)
Simulates shadows for the image.
![RandomShadow](https://user-images.githubusercontent.com/50166164/210499881-a0216e7c-1ae2-443b-bbdb-0db23361cd39.png)

### [RandomSnow](https://github.com/albumentations-team/albumentations/blob/master/albumentations/augmentations/transforms.py#L339)
Bleach out some pixel values simulating snow.
![RandomSnow](https://user-images.githubusercontent.com/50166164/210499908-8a751096-5c4d-49a6-bafa-a96ee0128ab7.png)

### [RandomSunFlare](https://github.com/albumentations-team/albumentations/blob/master/albumentations/augmentations/transforms.py#L597)
Simulates Sun Flare for the image.
![RandomSunFlare](https://user-images.githubusercontent.com/50166164/210499944-2d1db9bc-c227-448b-b7de-715c173fcc74.png)

### [RandomToneCurve](https://github.com/albumentations-team/albumentations/blob/master/albumentations/augmentations/transforms.py#L837)
Randomly change the relationship between bright and dark areas of the image by manipulating its tone curve.
![RandomToneCurve](https://user-images.githubusercontent.com/50166164/211442054-1b8c5afd-7346-41f1-a287-7221710fc71c.png)

### [RingingOvershoot](https://github.com/albumentations-team/albumentations/blob/master/albumentations/augmentations/transforms.py#L2183)
Create ringing or overshoot artefacts by conlvolving image with 2D sinc filter.
![RingingOvershoot](https://user-images.githubusercontent.com/50166164/211442106-6e4517af-5577-4ee8-9112-6d463ca3ec49.png)

### [RGBShift](https://github.com/albumentations-team/albumentations/blob/master/albumentations/augmentations/transforms.py#L1055)
Randomly shift values for each channel of the input RGB image.
![RGBShift](https://user-images.githubusercontent.com/50166164/211442140-9317a125-02ed-4f71-b7d7-dd35c5e62c32.png)

### [Sharpen](https://github.com/albumentations-team/albumentations/blob/master/albumentations/augmentations/transforms.py#L1910)
Sharpen the input image and overlays the result with the original image.
![Sharpen](https://user-images.githubusercontent.com/50166164/211442174-76673149-cb0d-4d4f-9977-b7f34b59bee3.png)

### [Solarize](https://github.com/albumentations-team/albumentations/blob/master/albumentations/augmentations/transforms.py#L1034)
Invert all pixel values above a threshold.
![Solarize](https://user-images.githubusercontent.com/50166164/211442201-8533c763-7296-4971-bd49-1b4b190c9580.png)

### [Spatter](https://github.com/albumentations-team/albumentations/blob/master/albumentations/augmentations/transforms.py#L2552)
Apply spatter transform. It simulates corruption which can occlude a lens in the form of rain or mud.
![Spatter](https://user-images.githubusercontent.com/50166164/211442240-3f345c52-8276-4df1-8463-0f976d6045b4.png)

### [Superpixels](https://github.com/albumentations-team/albumentations/blob/master/albumentations/augmentations/transforms.py#L2151)
Transform images partially/completely to their superpixel representation. This implementation uses skimage's version of the SLIC algorithm.
![Superpixels](https://user-images.githubusercontent.com/50166164/211442277-b090b66e-0183-4ccb-84f9-7b71400a9532.png)

### [TemplateTransform](https://github.com/albumentations-team/albumentations/blob/master/albumentations/augmentations/transforms.py#L2201)
Apply blending of input image with specified templates. 
![TemplateTransform](https://user-images.githubusercontent.com/50166164/211442307-87ed1b68-8921-4108-9eae-8f57079caea6.png)

### [ToSepia](https://github.com/albumentations-team/albumentations/blob/master/albumentations/augmentations/transforms.py#L1576)
Applies sepia filter to the input RGB image.
![ToSepia](https://user-images.githubusercontent.com/50166164/211442349-631dc32a-dc5c-4965-a20f-3820d071177b.png)

### [UnsharpMask](https://github.com/albumentations-team/albumentations/blob/master/albumentations/augmentations/transforms.py#L2369)
Sharpen the input image using Unsharp Masking processing and overlays the result with the original image.
![UnsharpMask](https://user-images.githubusercontent.com/50166164/211442384-e1362337-8526-476b-9ae8-8a8d2bd14f52.png)








