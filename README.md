<h1>Real Time Multi Color Detection</h1>
<em>The objective of this project was to develop a computer vision application that can detect and
track multiple colors in real-time using a webcam or video input. The project was built using
OpenCV and Python. The system captures video frames, processes them, and applies color
detection algorithms to detect specific colors such as red, blue, green, etc. Once the colors are
detected, the system highlights the detected areas in the frame and displays them to the user,
providing real-time feedback.</em><br><br>


<em>In this project, I used the HSV color space (Hue, Saturation, Value) instead of RGB for color
detection because HSV is more robust and accurate for detecting colors under different
lighting conditions. 
  <h5>The steps I followed include:</h5>
<ol>Converting the image from the RGB color space to the HSV color space using OpenCV’s
cv2.cvtColor() function.</ol>
<ol>Defining color ranges for each color I wanted to detect (e.g., red, blue, green).</ol>
<ol>Applying color thresholding using cv2.inRange() to isolate the specific color from the image.</ol>
<ol>Using contours or other detection techniques to find the boundaries of the detected color and
highlight them.</ol>
</em>
