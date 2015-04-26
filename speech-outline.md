1. About myself
2. Intro
3. Explain comuter vision
3.1. Images consist of pixels, placed on a grid. Make a nice zoomed in sketch.
4. Algorithms
4.1. Thresholding in the orange channel:
4.1.1. Explain that orange is a mix of red and yellow, in nature.
4.1.2. Explain that orange in RGB is a mix of: (255, 127, 0).
Link from [wikipedia](http://en.wikipedia.org/wiki/Orange_(colour)): In the RGB colour model, the system used to create colours on a television or computer screen, orange is made by combining high intensity red light with a lower intensity green light, and the blue light turned off. 
4.1.3. Select pixels where the RGB value is in the orange interval.
4.2. Contour detection and circular test
4.2.1. Detect contours.
4.2.2. Explain the area test with some simple geometrical sketches (circle, ellipse, rectangle). Derive the circular test criterium.
4.2.3. For all detected contours, run the test. Highlight only those contours who fulfill the circular criterium.
4.3. 
5. The implementation
5.1. Introduce python with its advantages and place an accent on academic applications
5.2. Introduce skimage
5.2.1. Talk about different modules: in a python notebook, type sk? and list the modules with a short explanation, maybe also screenshots


At the beginning, show a video cut: https://www.youtube.com/watch?v=llfYoFG7WrY. Motivate listeners to the problem of a robot searching for a ball.

Sources:
robot1: http://i.telegraph.co.uk/multimedia/archive/01436/Red-and-blue_1436364i.jpg
robot2: http://news.bbcimg.co.uk/media/images/53985000/jpg/_53985328_jex_1103711_de27-1.jpg
robot3: http://www.ais.uni-bonn.de/~stueckler/images/nimbro.jpg
robot4: http://www.ais.uni-bonn.de/humanoidsoccer/images/RoboCup_2009_TeenSize_Final_NimbRo_vs_CIT-Brains.jpg
robot5: http://www.ais.uni-bonn.de/Humanoid_Soccer_School/images/HSS_13_Soccer_Robots.jpg
robot6: http://control.ee.ethz.ch/~thunguye/RoboCup/IMG_0889.JPG
