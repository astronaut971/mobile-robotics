1. Structure

1.1 pow_analyzer folder contains Mapping, Tracking and Navigational parameters code. The data for these launch files 
is in the data folder under pow_analyzer folder.  For running the Mapping, Tracking and Navigational parameters code there are two Readme.txt files in pow_analyzer folder

1.2 pow_gui folder is GUI sample code. The GUI was developed with the future assessing staff in mind to
 be able to conveniently use the system in an intuitive, repetitive and consistent manner
 with little need for familiarisation with the underlying robotics hardware or software.
 This was done with the intention to allow for more tests to be conducted efficiently in
 a clinical setting. The interface is Qt-based and uses a MATLAB pipeline behind-the-
scenes for classification based on incoming data bridged from the ROS sensor drivers.


2. Compile and build the packages pow_analyzer and pow_gui

1. Create new ROS workspace  
2. Create new directory
3. Add to the ROS path
4. rosmake 

