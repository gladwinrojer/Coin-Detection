# Coin Detection using OpenCV
This is a program to detect coins in an image using Hough Circle Transform and note that the parameters like minDist, minRadius, maxRadius can vary from image to image.
# # # Algorithm for finding the coins that fall under the same st.line (Vertical)
I have devised my own algorithm for finding the coins that fall under the same st.line (Vertical). We find all the circles(coins) whose x-coordinates of the centres have difference less than 40(say). If the difference in x-coordinates of the centres of the circles are more than 40, we say that circles are not aligned i.e, they are not along same st.line. Note that the number '40' may change from image to image.
