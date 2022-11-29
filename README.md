 <h1 span style="color:red;">State-Farm-Distracted-Driver-Detection</h1>

<p><i> Kaggle hosted the challenge few years ago which focused on identifying distracted drivers using Computer Vision <br>
    Details of challenge can be found here - https://www.kaggle.com/c/state-farm-distracted-driver-detection </i></p>
    <hr>

<h3> Problem Description </h3>
<p>State Farm launched a kaggle competition few years ago called <b>“State Farm Distracted Driver Detection”</b>, where given driver images, each taken in a car with a driver doing something in the car (texting, eating, talking on the phone, makeup, reaching behind, etc). The goal was to predict the likelihood of what the driver is doing in each picture.</p>

  <h3><i>Dataset details -</i></h3>
  <ul>
    <li><b> Image Size</b> - 480 X 640 pixels</li>
    <li><b> Training Images count</b> - 22424 images </li>
    <li><b> Test Images count</b> - 79726 images </li>
    <li><b> Image type</b> - RGB </li>
    <li><b> Image field of view</b> - Dashboard images with view of Driver and passenger </li>
    <li><b> The 10 classes to predict are:</b> <br>
        <ul>
          <li>    c0: safe driving<br>
          <li>    c1: texting - right<br>
          <li>    c2: talking on the phone - right<br>
          <li>    c3: texting - left<br>
          <li>    c4: talking on the phone - left<br>
          <li>    c5: operating the radio<br>
          <li>    c6: drinking<br>
          <li>    c7: reaching behind<br>
          <li>    c8: hair and makeup<br>
          <li>    c9: talking to passenger</ul>
    <li><b> Loss</b> - multi-class logarithmic loss</li>
  </ul>

  # Driver Distraction System

  ## How To Run the project.

  --> Download the repository and change the directory to the current directory in th terminal. In the directory open the sub directory Flask.

  --> Now open the flask subdirectory and run the api.py file from the existing directory.

  >> $python3 api.py

  --> Now, you will get a local host server link.

  --> Copy the link and open the link in the existing browser.
