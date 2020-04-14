# Style-Transfer-in-Images

This repository contains code to transfer style of an image to a content image. The gradients are calculated on the raw pixels of the final image 
with the loss function as the sum of 3 components:
1. Content Loss
2. Variation Loss
3. Style Loss

Variation Loss is to ensure "smoothness" of the final image, style loss is based on the gram matrix and content loss is simply the mean square error 
between the content image and the final image.

Further instructions, layers and architecture used are mentioned in the self contained jupyter notebook
