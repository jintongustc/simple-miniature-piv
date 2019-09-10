# simple-miniature-piv

I am a Ph.D. Candidate in PIV reasearch, I want to share the experience of build a very simple PIV with low budget allowed. 

The most simplified PIV is using a continues laser and a video camera without triggering, I will not introduce it since it is really easy to do.


### The parts of PIV, let's do some math
* usually in PIV settings, three parts are included in the whole system:
  * Camera: For capture the particle images. 
  There're 3 different connection  USB 3.0, GigE, or CamLink connection, in our case, I prefer USB 3 or GigE, the CamLink is only for people with enough budget and need high performance for high frame rate. If we select a relatively cheap 1M resolution camera, for 60 Hz frame rate(30 image pairs per seconds), both USB 3.0 and GigE could finish the work. 
  * Laser: In amazon,15W blue continues Laser for engraving use is only 50-100 dollars, please carefully read the information, choose the one can adjust focus. With a cylindrical lens, the laser beam could be expanded to a laser sheet, I ordered a 8mm cylindrical lens in my application, you can select any focal length in your application
  * A computer: In my research, I selected a ARM single-chip board with Ubuntu runing on it. But for a lab experiment, Windows computer is more easy to use, a computer with a USB 3.0 is essential. If you use your laptop without a 1000Mb Ethernet, you can use a USB 3.0 to 1000Mb Ethernet converter. 
  * Syncronizer: An very cheap and basic Arduino Uno can generate digital signals for syncronizing the camera and laser togetor

  My cost of the parts:
  * Camera: JAI GO5000M, less than 1000 dollars
  * Lens: Nikon 50 1.4, 300 dollars
  * Laser:  15Watts Laser, 100 dollars
  * Arduino Uno: 15 dollars
  * Cylindrical lens: 50 dollars
  * In total around 1500 dollars, most budget used in the camera. I didn't see any cheap alternatives for the camera, if there's any cheap camera could be applied in the PIV with trigger, please let me know, thanks. 
  

### 
  
