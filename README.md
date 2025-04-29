# cs7785-lab1-solved
**TO GET THIS SOLUTION VISIT:** [CS7785 Lab1 Solved](https://www.ankitcodinghub.com/product/cs7785-cs-me-ece-ae-bme7785-solved-5/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;115360&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS7785 Lab1 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
Overview

The objective of this lab is to get you familiar with the robot and to get started writing code. Speci cally, this lab consists of two parts:

Part 1a (individual): run provided Turtlebot3 code to get experience interfacing with the robot.

Part 1b (group): answer the ROS related questions.

Part 2 (group): create your own image processing script that enables the robot to identify a desired object in its camera image.

The code generated in Part 2 can be reused in Lab 2 to have your robot move to track whichever object you have chosen.

Note Part 1 will take far less time than Part 2, so budget your time wisely.

Submission instruction and grading details are included at the end of the document.

Part 1a: Interfacing with the Turtlebot3

All instructions for the Turtlebot3 are available online at

http://emanual.robotis.com/docs/en/platform/turtlebot3/overview/

Complete the following steps:

1

1. Follow the steps in Section 3.1 (PC Setup). Particularly, the installation of dependent ROS 2 Packages (Sub-Section 1.1.3) and installation of Turtlebot3 Packages (Subsection 1.1.4).

2. Note: Section 1.1.5 has you place the line export ROS_DOMAIN_ID=30 #TURTLEBOT3 in the bashrc. This number should be edited depending on what robot you are using (the robot domain IDs are listed on the OLED on boot).

4. Make sure you can access the Raspberry Pi on the robot. You will need to SSH ( secure shell) into the robot using the command,

ssh burger@192.168.1.152

(The IP 192.168.1.152 should be replaced by your Raspberry Pi’s IP or hostname)

The password is burgerfor all the robots. Once entering the password you should see the terminal environment on the Raspberry Pi of your Turtlebot3!

5. Complete the Quick Start guide on the above website (listed as item 3 on the left side menu) and verify that you are able to teleoperate the robot using the keyboard (Sections 3.5 and 3.6.1.1). Optionally, feel free to run any other examples, such as Turtlebot Follower to test out the robot functionality. Note: For ROS2 the robot and your laptop have to be on the same network for messages to communicate (e.g. run teleop on your PC rather than on the robot). Thus, switch the network you are on to Eduroam for controlling the robot.

Part 1b: ROS Related Questions

Please answer the following questions (from Lab 0) and submit them as a PDF with your code submission from part 2.

What is a ROS_DOMAIN_ID? (2pt)

What is a node? (2pt)

What is a topic? (2pt)

What is a message? (2pt)

What is a subscriber? Write the syntax to create a subscriber that subscribes to the topic amazing_int, which takes message of type UInt64, and uses the callback function magic_fun, in C++ or Python. (5pt)

What is a publisher? Write the syntax to create a publisher that publishes to the topic amazing_bool, which takes message of type Bool, in Python. (5pt)

Can a node have multiple subscribers? Can a node have multiple publishers? (2pt)

2

Part 2: Object Following

Objective: Use the capabilites (e.g. HoughCircles, Contours) within OpenCV to locate an object using real-time images streaming on your computer.

In this part of the lab, you will use OpenCV to locate an object from your laptop’s webcam. This is a valuable step towards Lab 2, in which you will track the object from your robots camera frame and add driving capabilities to your code. Feel free to use any additional python libraries you want, at the very least cv2 (OpenCV) and numpy, please include a requirements.txt le with your submission if you use any libraries outside of these.

Create a new python script called nd_object.py. This script should receive images from the webcam on your laptop and track the location of a speci c object in the frame. Note: This cannot be done using a premade tag tracker package like ArUco. Once you have made the script it is often useful to make it an executable. To do this you must rst make sure you have the type of environment being used in the rst line of your code. For python this typically is,

#!/usr/bin/env python

Then, to make the le executable, using the command line in the directory (or with the full path speci ed) where your le is stored type,

chmod +x object_follower.py

./object_follower.py

Some example code to capture and display your webcam with OpenCV in python can be found at https://docs.opencv.org/3.0-beta/doc/py_tutorials/py_gui/py_video_display/py_video_display.html

After grabbing the image, process the image to look for your object. An easy place to start is to use the HoughCircles() functionality within OpenCV if your looking for a circle:

circles = cv2.HoughCircles(cv_image, cv2.HOUGH_GRADIENT, 1, 90, param1=70, param2=60, minRadius=50, maxRadius=0)

or use ndContours() to nd blobs of the same color:

im2, contours, hierarchy = cv.findContours(thresh, cv.RETR_TREE, cv.CHAIN_APPROX_SIMPLE)

3

As described in class, these alone will likely not be enough. Be sure to pre lter your images (blurring, sharpening, improving contrast, thresholding color, etc). You are not required to use Hough circles or contours, if you prefer to try a di erent method that is completely acceptable so long as the object is tracked.

Once you have located the ball in an image, print the pixel coordinate of the object and display some sort of marker or bounding box on the image itself.

We will provide balls of several sizes and colors for your use in the lab. Feel free to use any of them, or a di erent object of your choosing. For this lab, the object can be at any distance from the webcam that you choose (not taking up the entire frame).

Grading Rubric

The lab is graded out of 100 points, with the following point distribution:

Answer ROS questions from Part 1b 20%

Find &gt;65% of your chosen shapes in images 55%

Print the pixel location of each identi ed shape 5%

Submission

Part 1b and 2:

2. Put the names of both lab partners into the header of the python script. Put your python script, any supplimentary les, and a PDF with your answers to Part 1b in a single zip le called

Lab1_LastName1_LastName2.zip and upload on Canvas under Assignments Lab 1.

3. Only one of the partners needs to upload code and answers.

4
