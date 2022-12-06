<h1 align="center"> Introduction to LEGO Mindstorm EV3 - Sensors</h1>

<p align="center">
  <img src="https://user-images.githubusercontent.com/101992463/200483465-c4d38d4b-7ee1-4f84-b695-e809c3cb4066.png" />
</p>

<h2> Inputs Sensors </h2> 

In this part we have more variety types of inputs like color sensors, touch indicator, Ultrasonic sensor and gyroscope. One important thing that I need to mention is that we can use the motors and sensors of the Kit NXT. If you have one, you will not have any problem using these components with the EV3 brick.

In the WRO it's common to only use sensor color because normally in the table game we had a lot of indications that we can read or detect with these sensors. But it depends because all the years the table changes and it's possible that you need to use a proximity sensor to do an action and in that case it already depends on you. For that reason, this repository will be talking about the best way to realize a good design of a robot.

<h2>Types of Inputs</h2>

<h3 class="bolded">Color Sensor</h3> The EV3 color sensor have 3 mode:

- **Color Detection**: This mode of the sensor is one of the most used and important sensors that we have in the kit, because this sensor is capable of reading 7 different types of colors. But the accuracy of the reading depends on the distance the sensor is from the object. Normally this sensor has a good accuracy with 1 or 2 centimeters (0.79 inches) of distance from the object. If you see this sensor it's not the best for reading color in large distances. But this is not a limitation because I am going to show you how you can use this sensor in a more efficient way later. 

Here you can see the colour and light data table: 

<table>
  <tr>
    <th>Data</th>
    <th>Type</th>
    <th>Range</th>
    <th>Notes</th>
  </tr>
  <tr>
    <td>Colour</td>
    <td>Numeric</td>
    <td>0-7</td>    
    <td>
        <p>0 = No Colour</p>
        <p>1 = Black</p>
        <p>2 = Blue</p>
        <p>3 = Green</p>
        <p>4 = Yellow</p>
        <p>5 = Red</p>
        <p>6 = White</p>
        <p>7 = Brown</p>
    </td>
    
  </tr>
  <tr>
    <td>Light</td>
    <td>Numeric</td>
    <td>0-100</td>
    <td>Used in Reflected Light Intensity and Ambient Light Intensity modes. Measures light intensity as a percentage, 0 = darkest, 100 = brightest.</td>   
  </tr>
</table>

- **Refled light intensity:** This mode is also one of the most used because with this mode we will follow the line if we have black lines in the table. In this mode, the colour sensor emits a red light and measures the amount reflected back into itself from the surface you are testing. The intensity of the light is measured as a percentage from 0 to 100, with 0 being very dark, and 100 being very bright.
- **Ambient light intensity:**  In this mode, the colour sensor measures the amount of light in its environment, without producing its own light source. Ambient light intensity is measured as a percentage from 0 to 100, with 0 being very dark, and 100 being very bright. 

<p align="center">
  <img src="https://user-images.githubusercontent.com/101992463/202639619-6bbb0169-adb7-4ec3-a727-9b3199693fe0.jpg" />
</p>


<h3 class="bolded">Ultrasonic Sensor</h3>

The ultrasonic sensor measures distance to an object up to a maximum of 255cm (or 100 inches) away. It does this by sending out high frequency sound waves that bounce off any object in range, and measuring how long it takes the sound to return to the sensor. In the software, you can select whether the distance is given in centimetres or inches.

The ultrasonic sensor also has a“listen only” mode that can detect whether another robot is using an ultrasonic sensor nearby. In this mode, the sensor listens for signals but does not send them.

<p align="center">
  <img src="https://user-images.githubusercontent.com/101992463/202644461-4b1c0110-e5cf-4625-9cc0-6f1f10c4524c.jpg" />
</p>

<h3 class="bolded">Gyro Sensor</h3>

The gyro sensor detects rotational motion in the plane indicated by the arrows on the top of the sensor housing. The sensor measures the rate of rotation in degrees per second and keeps track of the total angle of rotation in degrees. It is very strange that this sensor is used in competition but it's good know a little bit about it. 

<p align="center">
  <img src="https://user-images.githubusercontent.com/101992463/202645266-451ab7f0-5ecc-475d-b6c3-cd8347c4de68.png" />
</p>

<h3 class="bolded">Infrared Sensor</h3>

The infrared sensor can measure distance or detect signals that are sent from the infrared beacon (see below). 

The infrared sensor can be used in three different modes: 

- **Proximity:** The infrared sensor sends an infrared signal and detects the reflection of this signal by an object in front of the sensor. The strength of the reflected signal can be used to estimate the distance to the object. Its maximum range is approximately 100 cm.
- **Beacon:** In this mode, the infrared sensor can detect an infrared beacon, set to beacon mode. The infrared sensor can detect the beacon’s proximity (relative distance from the sensor) and its heading (angle from the direction the sensor is pointing). See the table below for more information.
- **Remote:** The infrared sensor can detect button presses on the IR beacon. The infrared sensor can detect which button on the remote infrared beacon is pressed. You can also detect when certain combinations of two buttons are pressed at the same time.

<p align="center">
  <img src="https://user-images.githubusercontent.com/101992463/202646540-e7a47fbc-318b-48a5-ba48-f1830390e244.jpg"/>
</p>

<h3 class="bolded">Large and medium motors (rotation)</h3>

And yes motors also can be used as an input because both the large and medium servo motors are equipped with internal rotation sensors. The rotation sensor is used to measure how far a motor has turned (or has been turned). Rotation sensors can detect an amount of rotation in degrees or full rotations. You can also use the rotation sensor to find out what power level a motor is currently running at. And this propriety of the motors will be super important in the future to do more precision movements.

<p align="center">
  <img src="https://user-images.githubusercontent.com/101992463/202647390-4f6c3f20-078f-456c-a349-7490989e9b5d.jpg"/>
  <img src="https://user-images.githubusercontent.com/101992463/202647424-39f1f650-5651-4474-8bfd-177e9a407f5c.jpg"/>
</p>


<h3 class="bolded">Touch Sensor</h3>

And last but not least the touch sensor, this sensor gives your robot a sense of touch. The touch sensor detects when it is being pressed or released. It can even be programmed to wait until it is both pressed and released (we call this bumped).

<p align="center">
  <img src="https://user-images.githubusercontent.com/101992463/202647997-e9cd63f1-6e5d-46e7-8ab2-82914250e060.jpg"/>
</p>
