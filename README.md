# VR-ROOM

## **IDEA**


The purpose of this project is to help medical students in providing hands-on experience because textbooks are not enough for the students to get familiar with medical-surgical and para surgical procedures. Here the students can access the resources and perform the operations virtually with the help of VIFE(Discussed later) which can act as various types of medical equipment. 


## **SOLUTION**


When users enter the virtual simulation, the user will have the option of logging in as a student or teacher. The teacher will be able to upload the curriculum and study material to the database, while the student will have the option of accessing them. A student logs in and can view two views, in one view they can learn about the various surgical and para-surgical procedures, and in the other view, they will be provided with all the instruments and resources necessary to perform the particular surgery in the simulation by which they can practice their learned lesson.We are using VIFE (Virtual knife) which will work as real hand.

**VIRTUAL KNIFE**


VIFE is an ESP32 based device with an MPU6050 accelerometer & gyroscope sensor to get the values of acceleration and gyroscope of x, y & z coordinates in real-time and send these coordinates to the application with the help of Bluetooth. The received values are processed on the user's device to demonstrate it in the application and also feedback is sent from the application to VIFE. For accessing the different tools in the application user can use the SSD1306 0.91" OLED display given on VIFE with the help of provided buttons. To make it portable we will use a 18650 li-ion cell along with a TP4056 Charging module. 

## **TECH STACK**

**1. Firebase :** Firebase platform developed by Google for creating mobile and web applications. Used to store the data related to individuals.

**2. Unity :** Unity is a cross-platform game engine that allows you to import & assemble assets, write code to interact with your objects, and much more.

**3. Blender :** Blender is a free and open-source 3D computer graphics software toolset used for creating visual effects, interactive 3D applications, virtual reality, and computer games.

**4. ESP32 :** ESP32 by Espressif Systems is a feature-rich MCU with integrated Wi-Fi and Bluetooth connectivity for a wide range of applications. It comes with ultra-low power consumption with a combination of several types of proprietary software.

**5. Arduino IDE :** Arduino IDE is open-source software for programming various types of microcontrollers including ESP32. It comes with a plethora of inbuilt libraries. And it is based on C, C++ and Java.


## **DEPENDENCIES**




