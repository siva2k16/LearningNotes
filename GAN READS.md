https://tutorialsforar.com/face-tracking-using-arkit-and-ar-foundation-with-unity/

https://github.com/beholdergan/Beholder-GAN

https://www.kaggle.com/code/baobabman/beauty-gan

https://openaccess.thecvf.com/content/WACV2021/papers/Shafaei_AutoRetouch_Automatic_Professional_Face_Retouching_WACV_2021_paper.pdf

https://www.sciencedirect.com/science/article/pii/S0950705122000740

https://www.kaggle.com/datasets/arnaud58/flickrfaceshq-dataset-ffhq/code?datasetId=546691&sortBy=voteCount

https://www.kaggle.com/code/samadazimiabriz/stylegan

https://www.kaggle.com/code/dunky11/stylegan-2-v2

https://www.kaggle.com/code/samadazimiabriz/stylegan

https://www.kaggle.com/code/dunky11/stylegan-2-v2

https://github.com/skylab-tech/ffhqr-dataset

https://www.kaggle.com/code/theblackmamba31/pix2pix-gan-coloring-images

250 - Image to image translation using Pix2Pix GAN
https://www.youtube.com/watch?v=UcHe0xiuvpg

GAN KERAS - 
https://github.com/eriklindernoren/KerasGAN

https://www.kaggle.com/code/theblackmamba31/pix2pix-gan-coloring-images

https://nchlis.github.io/2019_11_22/page.html

https://modelzoo.co/model/pix2pix-keras

https://nchlis.github.io/2019_11_22/page.html

https://github.com/nchlis/keras_pix2pix/blob/master/pix2pix_train.py

Unity Virtual Fitting Room Full Tutorial 

https://www.youtube.com/watch?v=N-H0SHof4bc

Unity Virtual Fitting Room Full Tutorial 

https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4111818


Image-to-image translation with a pix2pix GAN and Keras

https://nchlis.github.io/2019_11_22/page.html

Key notes

Generator  G and the discriminator  D
Generator tries to generate as realistic images
Discriminator is basically a binary classifier that tries to detect fake 

Ket Steps Involved
Train  D on a batch of real images and computing the  D loss.
Train  D on a batch of fake (created using  G ) images and computing the  D loss.
Freeze weights of  D , train  G by generating a batch of images and computing the GAN loss.
Repeat steps 1-3 until convergence.

Keras implementation of a pix2pix GAN for image-to-image translation

https://github.com/nchlis/keras_pix2pix




