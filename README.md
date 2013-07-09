Robocop: Automatic Detection, Alert, and Response System using a Raspberry Pi and a Sony PS3 Eyetoy Camera
 
 *Beta proof-of-concept test: The original goal of of the project was to detect if UPS box is deposited at door, if so 
  then text the user image and link to livestream, and play thank you audio for mailman. The app also uploads the picture to Dropbox for 
  convinient viewing.
 
 *The algorithm uses a combination of color matching and motion detection. Effectively, we can simulate the real life scenario of 
  a colored package, and whether the package has been placed or moved. 
 
 *Hosted entirely on Raspberry Pi, fully independent and project demonstrates portability within a platform

1. Webcam detects for motion. Once motion is detected, code uses algorithm to look for extremely specific shade of
   brown that matches UPS box

2. If both requirements are met, then code sends link of livestream and an image of box(with timestamp) via text to user

3. Audio clip plays "Thank you" to Mailman to signify the other party knows it was deliverd

4. Thus user has satisfaction of knowing package was delivered as well as proof (in case of dispute) and can check live
   feed to make sure package doesn't get damaged/stolen

Attached: 1. Source Code
          2. Picture of received text, with link to image/video stream
          3. Sample Picture taken by camera (not of UPS box, unfortunately that isn't on file any more)
          
Team Members: 
Chaitanya Varanasi,
Salem Karani,
Sohail Shaikh,
Akash Motani,

*Robocop was a project for PennApps Spring 2013 Hackathon.
