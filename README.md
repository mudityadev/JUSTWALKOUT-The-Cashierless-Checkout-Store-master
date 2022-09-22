<!-- PROJECT -->
  <h3 align="center">Lane Line Detection Project 
</h3>

  <p align="center">
   Build for autonomous cars and trucks.
    <br />
    <a href="https://rmuditya.github.io/MudityaRaghav/"><strong>Muditya Raghav Portflio »</strong></a>
    <br />
    <br />
    <a href="https://github.com/rmuditya/Lane-Line-Detection-for-Autonomous-Car-Truck-on-Images-Video/blob/master/test_videos_output/solidWhiteRight.mp4">View Demo</a>
    ·
    <a href="https://github.com/rmuditya/Lane-Line-Detection-for-Autonomous-Car-Truck-on-Images-Video/issues">Report Bug</a>
    ·
    <a href="https://github.com/rmuditya/Lane-Line-Detection-for-Autonomous-Car-Truck-on-Images-Video/issues">Request Feature</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#Overview---About-The-Project">Overview - About The Project</a></li>
    <li><a href="#Tools-and-Technique">Tools and Technique</a></li>
    <li><a href="#pipeline">Pipeline</a></li>
    <li>
      <a href="#How-to-Run">How to Run</a>
      <ul>
        <li><a href="#prerequisites">Environment Setup</a></li>
        <li><a href="#installation">Installation of Libraries</a></li>
        <li><a href="#installation">Command on Terminal</a></li>
      </ul>
    </li>
    <li><a href="#More-Screenshots">More Screenshots</a></li>
    <li><a href="#Possible-Improvements">Possible Improvements</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>




<!-- ABOUT THE PROJECT -->
## Overview - About The Project
![alt text](https://github.com/rmuditya/Lane-Line-Detection-for-Autonomous-Car-Truck-on-Images-Video/blob/master/Screenshots/laneLines_thirdPass.jpg)
<br />
Humans have eyes to understand the sounding but machines don't. Autonomous systems have Cameras to see the world and by using the Computer Vision algorithm, they can understand them, take decisions.
I designed a Lane Line detection program that helps autonomous cars and trucks to find the line in any environment or weather.


<!-- Tools -->
## Tools and Technique

* Color Selection
* Region of Interest Selection
* Grayscaling
* Gaussian smoothing
* Canny Edge Detection
* Hough Transform line detection

<!-- Pipeline -->
## Pipeline

* Import all library - NumPy, OpenCV, Matplotlib
* Image Images
* Convert RGB image to Grayscale image
* Using Canny Edge detection 
* Region of Interest - 4 Sided polygon to Mask
* Hough Transform
* Draw the lines
* Output



## How to Run

1. Ubuntu 20.04 or 18.04 (Environment)
2. Clone the repo
   ```sh
   git clone https://github.com/rmuditya/Lane-Line-Detection-for-Autonomous-Car-Truck-on-Images-Video.git
   ```
3. Install Requirements
   ```sh
   pip3 install -r requirements
   ```
4. Open Terminal and Open Juypter 
   ```sh
   juypter notebook
   ```

<!-- Improvement -->
## More Screenshots
![alt text](https://github.com/rmuditya/Lane-Line-Detection-for-Autonomous-Car-Truck-on-Images-Video/blob/master/Screenshots/1.png)
<br />

![alt text](https://github.com/rmuditya/Lane-Line-Detection-for-Autonomous-Car-Truck-on-Images-Video/blob/master/Screenshots/2.png)
<br />

![alt text](https://github.com/rmuditya/Lane-Line-Detection-for-Autonomous-Car-Truck-on-Images-Video/blob/master/Screenshots/3.png)
<br />

<!-- Improvement -->
## Possible Improvements

1. Image segmentation for accurate predication 
2. Under the curve of the road
3. If a lane line is not found, how to manage that situation.


<!-- CONTACT -->
## Contact

Muditya Raghav 
* [Muditya Raghav](https://rmuditya.github.io/MudityaRaghav/)
* [Linkedin](https://www.linkedin.com/in/muditya/)
* [Twitter](https://twitter.com/RaghavMuditya)
* [Instagram](https://www.instagram.com/mudityaraghav/)
* [Gmail - rmuditya@gmail.com](rmuditya@gmail.com)


<a href="https://www.buymeacoffee.com/mudityadev" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 30px !important;width: 217px !important;" ></a>

