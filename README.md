# GAN-KID-F
GAN for kpop female faces

## Data
K-pop Idol Dataset - Female (KID-F) is the first dataset of K-pop idol high quality face images. It consists of about 10,000 high quality face images (https://www.kaggle.com/datasets/vkehfdl1/kidf-kpop-idol-dataset-female, https://www.kaggle.com/datasets/rossellison/kpop-idol-faces). Two methods are used: DCGAN and ProGAN. 

## Description

For GANs, datasets with a size of 60,000 to 200,000 images are typically used. Our dataset contains fewer than 10,000 images, which is not enough for optimal learning. On the other hand, our data set only contains one class - Asian girls. To improve learning, we apply various data augmentation techniques, including horizontal flipping, random cropping, compression, stretching, and brightness and contrast modification. We use Instance Normalization instead of Batch Normalization in DCGAN to accelerate learning. However, the task is complicated by the presence of various facial poses and accessories, such as glasses, which can affect learning and performance. The Program and Style GAN performs better than DCGAN, but it requires more time due to the larger image size.
