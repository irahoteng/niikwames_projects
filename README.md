# niikwames_projects
A few projects that I am especially proud of and worked on
Summary of the Indoor Air Quality C code 
Provide user feedback of surrounding indoor air quality using gas sensor
Used to detect harmful levels of VOCs in an environment 
Organic chemicals that have a high vapour pressure at room temperature
Released by products through offgassing
Extended exposure to high VOC particle concentration can be toxic to the human body
Proportional relation to gas resistivity
A main factor that contribute to indoor air quality (IAQ)
In order to successful run this code here are the components required:
Parts required:
Arduino(UNO) 
BME680 sensor
Bread Board 
Jumper wires
Pins I used:
Used SDA,SCL,GND, &5V
My device set up:
Parts used:
(ESP8266)
BME (688)
Jumper wires
Breadboard
The ESP 8266 PINOUT
BSEC used SDA,SCL, GND and 3.3V
Implementing the LED’s 
Using GPIO’s 13-14
Denoise Filter
What is image convolution?
In image processing, convolution is the process of transforming an image by applying a kernel over each pixel and its local neighbors across the entire image. The kernel is a matrix of values whose size and values determine the transformation effect of the convolution process.
What is noise?
Noise in an image is the presence of artifacts that do not come  from the original image and as result makes a picture appear grainy
The  code for denoise was created primarily with the use of a median filter and salt and pepper noise.
Salt and Pepper noise are based around the grayscale image range:0-255. 0(zero intensity)producing a black color while 255(max intensity) produces a white color
Thus giving the image, the “salt and pepper” appearance. From there a matrix could be created for salt and pepper noise. One matrix being closer to white while the other closer to black.

