# SYNLA Plus Dataset
 Successor to the original [Synthetic Line Art (SYNLA) Dataset](https://github.com/bloc97/SYNLA-Dataset).

Improvements:
 - Huge 65536 images dataset
 - Color gradients for lines and background
 - Improved data augmentation
 - Linear/correct color blending
 - Better resampling and reduced artifacts
 - Contains real images as background ([DIV2K](https://data.vision.ee.ethz.ch/cvl/DIV2K/) + random anime images)

![Example][c0]
![Example][c1]
![Example][c2]
![Example][c3]
![Example][c4]
![Example][c5]
![Example][c6]
![Example][c7]
![Example][c8]

## Fair Use

<ins>The background source images used to generate this dataset are copyrighted</ins>, however their use are justfied by:  
**[Canadian Copyright Act](https://laws-lois.justice.gc.ca/eng/acts/c-42/index.html) (R.S.C., 1985, c. C-42)**, [29 - Fair dealing for the purpose of research, private study, education, parody or satire does not infringe copyright.](https://laws-lois.justice.gc.ca/eng/acts/c-42/page-8.html#h-103270) (Country of issue)

**[U.S. Code Title 17. - COPYRIGHTS](https://www.law.cornell.edu/uscode/text/17) (17 U.S. Code § 107)**, [\[...\] the fair use of a copyrighted work, \[...\] for purposes such as criticism, comment, news reporting, teaching (including multiple copies for classroom use), scholarship, or research, is not an infringement of copyright.](https://www.law.cornell.edu/uscode/text/17/107) (Country of provider)

1. The purpose of use is for nonprofit educational/research purposes;
2. Original images cannot be recovered without significant effort and redrawing from this dataset, which makes it nonrepresentative of the original work.
3. Effort is made to use the least amount of each copyrighted work as possible. The goal is to have a large variance on the images' content, thus a very small amount of many individual work was used.
4. There are no public alternatives for high quality line art datasets.
5. It is easier to distribute the original work as intact images rather than distributing them within this dataset. The impact of distribution on the original work is minimal.
6. As the dataset obfuscates large amounts of the original images, negative financial/market impact on the artist/creator is minimal.

## Description

This dataset is designed to simulate complex line art. Useful for training machine learning models which perform any of the following:
 - Super-Resolution/Deblurring
 - Denoising
 - Artifact removal (de-ringing, non-gaussian degradation, etc.)
 - Inpainting
 - User-Guided Colorization 
 - Style Transfer
 - And more...

Most line art are licensed and have copyright. This dataset offers an open alternative and is released under MIT license.

Three color datasets are available. The full dataset contains 65536 (2^16) images of size 256x256. All images were generated using images in the folder `/Generator_Images`, which is also public, allowing custom generation.
Smaller preview datasets (1024 and 4096 images) are also available. They are mutually exclusive with the full dataset can be used as validation/test datasets.

The code used to generate the images is not yet public.


[b0]: Dataset_Grayscale/1e2fb2f838034fc7a0a43b6b0c7ab321.png "Example"
[b1]: Dataset_Grayscale/5f1ed8c90aa948b995f0360986e3bb74.png "Example"
[b2]: Dataset_Grayscale/07a3fd4cd8664fb59283d0444dae5c34.png "Example"
[b3]: Dataset_Grayscale/07c91b920fee4ae29788b62b0be3ee3c.png "Example"
[b4]: Dataset_Grayscale/5260f5d41c964c02a8c6dc0ccffb98c7.png "Example"
[b5]: Dataset_Grayscale/7239d739b4b748659c0fd11c2f8c16a2.png "Example"
[b6]: Dataset_Grayscale/7974b1a2e1ea4716b38a4fe67ebceefc.png "Example"
[b7]: Dataset_Grayscale/34975c49c334461d88f528ca66b5d347.png "Example"
[b8]: Dataset_Grayscale/40514e8fe57b46c9893f389f0c8cbc3c.png "Example"




[c0]: Dataset_Color/Dataset_1024/0e61d8557ac5496c90611c52a9b8e9c0.png "Example"
[c1]: Dataset_Color/Dataset_1024/1cd819fc1ca1424a896426928adc74bb.png "Example"
[c2]: Dataset_Color/Dataset_1024/1f3983379dcd4b5f93595186f7392e26.png "Example"
[c3]: Dataset_Color/Dataset_1024/2bbcb8cf42634e3196423de0ad9c5cfe.png "Example"
[c4]: Dataset_Color/Dataset_1024/2e1bc807b5e44472986e2333a3b2708f.png "Example"
[c5]: Dataset_Color/Dataset_1024/7f653e863421411e899480ad787126d3.png "Example"
[c6]: Dataset_Color/Dataset_1024/09ac6167c4f54b4ba286cd20ecd4ddb5.png "Example"
[c7]: Dataset_Color/Dataset_1024/9e89413807c04186b8b1337ad2d37852.png "Example"
[c8]: Dataset_Color/Dataset_1024/21b69edaf3614e7eabfb24e43917e5d4.png "Example"





