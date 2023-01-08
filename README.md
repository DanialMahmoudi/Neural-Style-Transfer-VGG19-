# Neural-Style-Transfer-VGG19-
This project uses Neural Style Transfer algorithms to recreate content pictures with respect to different painting styles.
The following project is conducted and implemented based on Leon A. Gatys et al. (2015) A Neural Algorithm of Artistic Style https://arxiv.org/abs/1508.06576.
Truth be told, in my last repository, I took the liberty to change the architecture but VGG19 seems the best answer possible. However, the knowledge is not only meant to be shared but also to be altered spontaneously.

Moreover, additional information are provided below:

  - Image size : (400, 400, 3)
  - Pre-trained network : VGG19
  - Weights : Imagenet
  - Content layer : "block5_conv4"
  - Style layers :
  -    - ('block1_conv1', 0.2),
  -    - ('block1_conv2', 0.2),
  -    - ('block1_conv3', 0.2),
  -    - ('block1_conv4', 0.2),
  -    - ('block1_conv5', 0.2)
  
Also, in addition to the main algorithm provided in .ipynb format (notebook), there are another files which will be fully explained below.

Starry night.jpg : Style picture.

Bridge.jpg : Content picture

Result.jpg : Result picture.

Note that due to computational expensivity, I have not tried multiple example and only changed the style of a bridge into post-impressionism style of the Starry Night by Vincent Van Gogh.
I am looking forward to try this algorithm with various architectures in search of better outcomes.

Please, feel free to modify the layers or  even the architecture and use your own images for more thrilling personal experiences.


