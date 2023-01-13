<h1 align="center"> Action Block Guide </h1>

<p align="center">
  <img src="https://user-images.githubusercontent.com/101992463/204196330-73f94df0-bfa4-4868-8649-5054c42d4abe.PNG" />
</p>

The action blocks, see these blocks like all the output manipulation that we can do with the robot. In this section we will see in detail each block. 

<h2>Medium motor:</h2>

![MediumMotorActionBlocks](https://user-images.githubusercontent.com/101992463/204197924-55ab1ff2-6973-4c27-9a7c-eaece9d38056.PNG)

With this block you can control only the medium motor and you have 4 forms of control.

- **On for rotation:** With this method of control you can move the motor indicating the power of the motor, the number of rotations and finally if you want that the motor stop abruptly or not. 

- **On for degrees:** This method is very similar to the previous one only that in this case you need to indicate the degrees values that you want the motor to move.

- **On for seconds:** This method also is similar to the previous ones only that in this case you need to indicate the time values that you want the motor to move.

- **On:** And finally "On" with this method you only need to indicate the power because the motor will pass on until you stop or end the execution.

<h2>Large motor:</h2>

![LargeMotorBlock](https://user-images.githubusercontent.com/101992463/204200542-2c042977-5009-4a65-9fd6-ad19769efc47.PNG)

With this block you can control only one of the large motor and you have 4 forms of control that are the same of the medium motor, for that reason I will not to repeat this part.

<h2>Move Steering:</h2>

![MoveSteeringblock](https://user-images.githubusercontent.com/101992463/204201352-0d1752a1-142d-44d4-b84a-8d228281ce0a.PNG)

With this block you can control to large motors at the same time, this block also have 4 forms of control that are the same that you already know only that in this occasion we have a new section that is the "steering" if you see in the image if the steering = 0 the motor B and C will be move at the same time but if you change the value in that section the motors will be move with a different velocity and degrees normally is used to realize turns or to move straight. I invite you to change the values and notice what happens when you change the value.

<h2> Move tank </h2>

![MoveTankBlock](https://user-images.githubusercontent.com/101992463/204203231-dd00aa55-662c-40ca-966c-b67d11e4ceeb.PNG)

Block has the same functions as Large Motor, while operating two motors. Alternative power of the speeds result in the motors moving at different speeds. The default setting we use is degrees.

<h2> Display </h2>

![DisplayBlock](https://user-images.githubusercontent.com/101992463/204203663-f31e5f5a-3cfb-4e56-b649-19b4c25e2d0d.PNG)

This block displays information on the brick's screen. Information can be shown as text, shapes, images. This block also has the capability to reset the screen to blank.

The 'Wire' input option allows you to use the output of another block as your input value.

X, Y Coordinates will determine placement of display on screen.

<h2> Sound </h2>

![SoundBlock](https://user-images.githubusercontent.com/101992463/204204063-dcdff5f2-7170-4b7a-8e84-4ab788e0bd3a.PNG)

Block has the capability to play a file, a tone, a note, or just make the sound stop altogether.

- File Name: Wired, Project Sounds, Lego Sound Files
- Volume: 0 to 100
- Play Type: Wait for Completion, Play Once, Repeat

<h2> Brick status light </h2>

![BrickStatusLight](https://user-images.githubusercontent.com/101992463/204204471-67a7e15d-80b5-404f-970f-d5a4916b3781.PNG)

The Brick Status Light surrounds the brick buttons on the face of the EV3 Brick. You can turn the Brick Status Light on in green, orange, or red, turn it off, or make it pulse on and off. Use the Mode Selector to choose how you want to control the Brick Status Light.

If you select the On mode, you can choose the color and the pulse option using the Inputs. The modes and inputs are described below.

Modes : On , Off , Reset.
