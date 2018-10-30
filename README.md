# Video Doorbell, Lab 7

*A lab report by Manuel Viejo*

### In This Report

## Part A. HelloYou from the Raspberry Pi

**a. Link to a video of your HelloYou sketch running.**

https://www.youtube.com/watch?v=O0uAk8zWhLw

## Part B. Web Camera

**a. Compare `helloYou/server.js` and `IDD-Fa18-Lab7/pictureServer.js`. What elements had to be added or changed to enable the web camera? (Hint: It might be good to know that there is a UNIX command called `diff` that compares files.)**

The key difference is the event handler for taking a picture

![takePicture handler](https://github.com/mviejo33/IDD-Fa18-Lab7/blob/master/lab7_takePicture.png)

**b. Include a video of your working video doorbell**

https://www.youtube.com/watch?v=vOJJm5fjfb4

## Part C. Make it your own

**a. Find, install, and try out a node-based library and try to incorporate into your lab. Document your successes and failures (totally okay!) for your writeup. This will help others in class figure out cool new tools and capabilities.**

I used the PDFKit library to save the image as a pdf in the server, it could be used as a scanning app for documents.


**b. Upload a video of your working modified project**

https://www.youtube.com/watch?v=pPylKK-_P3k
