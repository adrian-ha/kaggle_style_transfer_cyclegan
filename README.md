# kaggle_style_transfer_cyclegan
 Implementation of cycle GAN style transfer algorithm - used for Kaggle "I'm  Something of a Painter Myself"

# I'm Something of a Painter Myself
Image-to-image translation has been an increasingly popular topic over the last years. One example of such a task is art style transfer. Style transfer algorithms in the context of art try to capture the general style of an artist or an image and apply it to one or many content pictures. As an example, think of your latest holiday picture and try to imagine how Monet or Van Gogh would have painted the scene. 

There are several different structures that try to do this task. One of the main differences is whether the style and content picture(s) are paired. A great paper to read to get started with style transfer is [Gatys et al. (2016)](https://openaccess.thecvf.com/content_cvpr_2016/papers/Gatys_Image_Style_Transfer_CVPR_2016_paper.pdf). In the below notebook I apply a CycleGAN for unpaired image-to-image translation. I recommend to look at the original paper by [Zhu et al.](https://arxiv.org/abs/1703.10593). We will train train a model to transform an image from domain X (photo_jpg) into an image that looks like it came from domain Y (monet_jpg). 

Even though I have played around with similar structures during some courses I am still quite new to image applications. Throughout the notebook I amended code bits of a [Udacity Cycle GAN](https://github.com/udacity/deep-learning-v2-pytorch/tree/master/cycle-gan) exercise that I did a while ago. I am looking forward to receive constructive feedback on the notebook. 
