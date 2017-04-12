# Perspective-Transform
[image1]: ./examples/example.jpg "example"
[image2]: ./examples/Region.jpg "region"
[image3]: ./examples/compare.jpg "transformed"
[image4]: ./examples/using.jpg "using"


Here, I have tried to make the perspective transformation of photos more visual. Generally, the points in the original image and the coresponding points on the transformed image need to be selected by visual inspection and estimation. I have used openCV, matplotlib.pyplot and numpy techniques to achieve the same.

Following flow chart shows how to use the function defined in [Perspective_Transform.ipynb](Perspective_Transform.ipynb)

![alt text<>][image4]

Following is the image that was used to demonstrate the function usage. ![alt text][image1]

After using the function to get points on the original image and the desired transformed immage, we get an image like the following which shows the point-regions selected. White is the desired transformed point-region and the black lined point-region is the original one.

![alt text][image2]

After the transformation, the image seemed like that if the camera was in front of the sign. The thickness of body of the working man on the sign and the orientation of the pole on which the sign is mounted suggest the above assumption is true with reasonable approximations.

![alt text][image3]
