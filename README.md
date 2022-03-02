# AirNet
AIRNET: Air Quality Level Predictor
The objective of this project is to monitor the environment pollution using image processing
technology. We will train the model by given data and test the model with a real time image.
Image processing obtains the polluted parts of the image using edge detection and depth
estimation technique. With the increasing availability of smartphones, images can be really
useful in information representation and description. For these techniques to work efficiently
we have to avoid using it for night time images, or images with no sky in it. 
It detects and quantifies PM (particulate matter) pollution by extracting a combination of image features,
including transmission, depth, RGB channel, local image contrast, and image entropy. General
observation that we made, the images with high AQI are much misty and bright, and the
structural objects are blurred without clear boundaries. We further consider the time, date and
weather condition of each photo, to determine the correlation between PM level and various
factors. Based on these features, we build a model to predict PM level using photos collected.
Output is the real-time PM level with the Air Quality Level Indicator.
