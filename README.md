# GAN-KID-F
GAN for kpop female idols

K-pop Idol Dataset - Female (KID-F) is the first dataset of K-pop idol high quality face images. It consists of about 10,000 high quality face images (https://www.kaggle.com/datasets/vkehfdl1/kidf-kpop-idol-dataset-female, https://www.kaggle.com/datasets/rossellison/kpop-idol-faces). Two methods are used: DCGAN and ProGAN. 

For GANs, datasets with the size of 60000-200000 images are used. Our dataset stores less than 10000 images. On the one hand, this is not enough, on the other hand, we have one class - asian girls. For better learning, we use augmentation - horizontal flip, radom crop, compression and stretching, brightness and contrast modifications. We use InstanceNorm instead of BatchNorm. The task is complicated by various poses and accessories on the face, such as glasses.
