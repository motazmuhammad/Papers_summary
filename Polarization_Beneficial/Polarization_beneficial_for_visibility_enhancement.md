
This paper studies the use of polarized filters to reduce haze or for better imaging quality within a scattering medium.

The aim of the paper is to study whether or not it is beneficial to use a polarizer, and take multiple images some polarized and some unpolarized to improve the SNR or the dehazing.

How the paper proceeds:-

1. It makes an images formation model Assuming two images one with no polarizer, and another with a polarizer. This allows them to assume that the light is just the addition of the two components. Then some analysis is done to conclude the following.

a. There are many cases in which using a polarizer improves the quality of the image.
b. There are cases in which using a polarizer reduces the quality of the image.( measure in SNR).
c. The best way to keep the quality as good as possible is to have multiple repeate images with small enough integeration time.

Important equations.

1. Image equation

<img src ="https://github.com/motazmuhammad/Papers_summary/blob/master/Polarization_Beneficial/pictures/Equation_1(Measured_image).png"  width ="400px">
where D(x) is the direct transmission, and A(x) is the airlight component.

2. Polarization equation

<img src ="https://github.com/motazmuhammad/Papers_summary/blob/master/Polarization_Beneficial/pictures/Equation_5.png" width ="480px">

where p is the degree of polarization.

3. The actual acquired images are

<img src ="https://github.com/motazmuhammad/Papers_summary/blob/master/Polarization_Beneficial/pictures/Equation_7.png" width ="480px">
where alpha is the fraction of the intgeration time given to the respective acquisition image.

Afterwards, the dehazing is


<img src ="https://github.com/motazmuhammad/Papers_summary/blob/master/Polarization_Beneficial/pictures/Equation8_Simple_Dehazing.png" width ="480px">

