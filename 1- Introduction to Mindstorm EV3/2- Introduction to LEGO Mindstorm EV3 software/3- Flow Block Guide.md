<h1 align="center"> Flow Block Guide </h1>

<p align="center">
  <img src="https://user-images.githubusercontent.com/101992463/205810810-3d16d8f2-c792-44c2-900f-bd302bb7916a.PNG"/>
</p>

If you have programmed before there are three main blocks used for program flow are the Wait, Switch, and Loop blocks; actions with which it might already be related. These blocks are so important because with these blocks we can realize all the conditional logic in our program and decide where to realize an action or not.

<h2>Start:</h2>

![StartBlock](https://user-images.githubusercontent.com/101992463/205814383-970f1ee3-28d2-4af0-b243-0121160d77f5.PNG)

The Start block marks the beginning of a programming block sequence in your program. Your program can have more than one sequence. All sequences with a Start block will start automatically when a program is run, and the sequences will run at the same time.

If your robot is turned on and connected to your computer (by USB, Bluetooth, or Wi-Fi), you can also click on the green arrow on the Start block to immediately run that single sequence in your program. 

<h2>Wait:</h2>

![WaitBlock](https://user-images.githubusercontent.com/101992463/205819359-f57c2b63-7139-4db2-a3b2-ee4d952f28e4.PNG)

The Wait block makes your program wait for something before continuing to the next block in the sequence. You can wait for a certain amount of time, for a sensor to reach a certain value, or for a sensor value to change.

**Important: The Wait block does not make your robot stop. If any motors are on at the beginning of the block, they will stay on during the wait.**

<h3>The modes are: </h3> 

- **Brick Buttons:** As the name says this mode is used when you want to continue an action after you touch an assigned button to compare. 
- **Color Sensor:** In this mode we can compare a specific color to realize an action or compare a value of reflected light intensity.
- **Infrared Sensor:** As all the other ones this mode continues the wait block after to compare the distance that you assigne.
- **Motor Rotation:** This mode continues the wait block when the rotation of the motor is the same as the value you indicated. 
- **Timer:** This mode works as a timer where you have an ID to identify the timer, a compare type, a threshold value and an output of the timer. 
- **Touch Sensor:** The wait block will continue until the touch sensor is pressed.
- **Messaging:** It is a functionality that we can use to continue the wait block using a message through bluetooth.
- **Time:** And the most used mode "Time" in this mode the wait block will wait until the values in seconds that you indicated (You can use float values if you want to wait a half of a second "0.5").

**Important: Each of the sensor types listed in the Wait block has one or more Compare modes. A Compare mode will continuously read data from the sensor and wait for it to reach a value that you specify.
Some types of sensor data can be compared to a Threshold Value, and other types can be compared to certain specific values.**

<h2>Loop:</h2>

![LoopBlock](https://user-images.githubusercontent.com/101992463/205844685-67f284f5-97f4-45ac-8c7e-82f1d4d682f6.PNG)

The Loop block is a container that can hold a sequence of programming blocks. It will make the sequence of blocks inside it repeat.
You can choose to repeat the blocks forever, a certain number of times, or until a sensor test or other condition is True. You can see this block as the while loop in programming because the loop will repeat until comply with a condition. 
　
Use the Mode Selector to control how the loop will repeat. The different modes specify what condition will make the loop end.

Also you can finish the loop using the other modes mentioned before in the wait block.

You can enter a name for the loop in the Loop Name field on the top of the Loop block. This name is used by the Loop Interrupt block to give you another way to end the loop.

Blocks inside the loop can use the Loop Index output to tell how many times the loop has repeated.

<h2>Switch:</h2>

![SwithBlock](https://user-images.githubusercontent.com/101992463/205846685-69094d0f-bf89-4824-890c-c16b1f4fdfb0.PNG)

The Switch block is a container that can contain two or more sequences of programming blocks. Each sequence is called a Case.
A test at the beginning of the Switch determines which Case will run. Only one Case will run each time the Switch is executed.
　
The Switch test shown here can decide which Case to run based on a sensor data value or a value from a Data Wire.

You can put another switch in the false case and in this way you can use the switch as an else if, where do you have more of two possible cases. 

You can use all the condition or modes mentioned before to create a true case.

<h2>Loop Interrupt block:</h2>

![BreakBlock](https://user-images.githubusercontent.com/101992463/205848213-225d45c1-f979-4eb2-9706-b8f351c1bd8b.PNG)

The Loop Interrupt block makes a Loop block end. No more blocks in the loop sequence will execute, and the program will continue with any blocks that are after the loop. You can specify which Loop block to interrupt by using its Loop Name.
You can use the Loop Interrupt block to make a loop exit sooner than it normally would, or in response to a different condition. You can interrupt a loop from inside the loop itself, or from another block sequence that is running at the same time.


