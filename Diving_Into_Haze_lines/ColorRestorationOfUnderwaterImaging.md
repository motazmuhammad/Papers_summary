
The aim of the paper is to better reconstruct color in underwater images .

Method. The paper aims to guess Porition attenuation values for GR,and BR. This in turn allows it to better reconstruct the images.

Limitation:

The paper depend on visually judging the images and rying different ocean parameters until the best ones are found. The best ones are defined to be the ones that visually represnt the image.

ِAlso, somehow they thought that using stereo imaging for depth estimation is good enough even underwater.

Promise of the paper:

putting into account the fact that the ttenutation coefficent is strongly different from one chanel to another, Allows them to better reconstruct the images.

Image formation mode

Ic(x)=tc(x)Jc(x)+(1-tc(x)).Ac
c is for color
I is the total value of the pixel( image value).
t transimission of a color at a certain channel
Ac the scene value of the areas with no object.
J is the object radiance.
