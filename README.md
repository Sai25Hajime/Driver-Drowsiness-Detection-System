# Driver-Drowsiness-Detection
Driver drowsiness detection is a project built using Dlib and OpenCV with Python as a backend language.

---

<h3>Logic of project</h3>
The project includes direct working with the 68 facial landmark detector and also the face detector of the Dlib library.
The 68 facial landmark detector is a robustly trained efficient detector which detects the points on the human face using which 
we determine whether the eyes are open or they are closed.</br></br>
<p align="center">
  <img src="images/landmarks.jpg" height="350">
</p>
<b>The 68-landmark detector data (.dat) file can be found <a href="http://dlib.net/files/shape_predictor_68_face_landmarks.dat.bz2"> By clicking here</a></B>

---

<h3>The working of the project</h3>
<ul><li>As you can see the<b> above screenshot</b> where the landmarks aredetected using the detector.
<li>Now we are taking the ratio which is described as <i>'Sum of distances of vertical landmarks divided by twice the distance between horizontal landmarks'</i>.
<li>Now this ratio is totally dependent on your system which you may configure accordingly for the thresholds of sleeping, drowsy, active.</ul>
<p align="center">
  <img src="images/active.jpg" height="350">
  <br></br>
  <img src="images/sleepy.jpg" height="350">
  <br></br>
  <img src="images/drowsy.jpg" height="350">
</p>

---

# How to Download the Project?
1) Click on the Code option.
2) Then Select 'Download Zip'.
3) Extract the folder.
4) Run it in Visual Studio Code.

---

## 👩‍💻 Contributors/Collaborators  
- [Saileen Fernandes (@Sai25Hajime)](https://github.com/Sai25Hajime)
- [Jelestina Nadar (@Jelestina)](https://github.com/Jelestina)
- [Alister Almeida (@miali4657)](https://github.com/miali4657)


