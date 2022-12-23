<h1 align="center"> Advanced Blocks Guide </h1>

<p align="center">
  <img src="https://user-images.githubusercontent.com/101992463/209285476-136d465e-1b6d-44ed-875f-ea782d7cc516.PNG">
</p>

In this section we will find really useful blocks to create more complicated and versatile programs. 

<h2>File Access Block:</h2>

![FileAccessBlock](https://user-images.githubusercontent.com/101992463/209289636-2ca7f412-f733-4a68-808b-55492ea8914d.PNG)

The File Access block allows you to read and write data to and from files on your EV3 Brick. Once files are created, they can be accessed either through the File Access block or the Memory Browser.

It is a useful block because with this block you can create programs available to save a value into the block and use in the future. For example create a program that permits you to save the light intensity automatically and dont modify the main program to set the new value. 

In the future we are going to create a really useful program that will be a great help in the competition.

<h2>Messaging Block:</h2>

![MessagingBlock](https://user-images.githubusercontent.com/101992463/209291707-aad17941-4e34-4da6-8a26-057bf5e389db.PNG)

The Messaging Block is used to send Bluetooth Messages between EV3 Bricks.

To send or receive a message, the EV3 Bricks must first be connected, either by the on-brick Bluetooth Menu or through the Bluetooth Connection block.

I will not explain much of this because in the competition the bluethooth functions are fully provided.

**This block have 3 modes:**

- Send
- Receive
- Compare

<h2>Bluetooth Connection Block:</h2>

![BluethoothConnection](https://user-images.githubusercontent.com/101992463/209292464-68ceb325-4e5c-445c-86bd-bcf43512de6e.PNG)

Use the Bluetooth Connection block to turn Bluetooth on or off, connect to another Bluetooth device, or clear the connection to another Bluetooth device.

If you have already established a Bluetooth Connection using the EV3 On-brick menu, you do not need to use the Bluetooth Connection Block.

The Bluetooth protocol in the EV3 system works by choosing a Master EV3 Brick and using that to connect to a Slave EV3 Brick.

One Master EV3 Brick can connect to up to seven Slave EV3 Bricks. The Master EV3 Brick can send messages to each Slave EV3 Brick.

The Slave EV3 Bricks, however, can only send messages back to the Master EV3 Brick. Slave EV3 Bricks cannot send messages directly to other Slave EV3 Bricks.


<h2>Keep Awake Block:</h2>

![KeepAwakeBlock](https://user-images.githubusercontent.com/101992463/209293016-2f9de1a1-ae2b-4ae7-9c28-b50ed3ad4f62.PNG)

This block reset the EV3 Brick sleep timer.

If you want to wait longer for the EV3 Brick Sleep Settings this block is the best.   

The Sleep Setting is configured using the EV3 Brick Interface.

<h2>Raw Sensor Value Block:</h2>

![RawSensorValueBlock](https://user-images.githubusercontent.com/101992463/209293795-7fa2afb0-389c-4849-8ce1-9b1717b8f84d.PNG)

The Raw Sensor Value block outputs the unprocessed sensor reading, which is a value in the range 0 to 4095, but this depends on the state of the sensor in some occasions the max value could be less than indicated. The Raw Sensor Value block only has one mode.

The block is too powerful if you know how to use it because if you don't have the best sensor as they are "HiTechnic color sensor" (This color sensor is the unique sensor permitted in the competition that is not an official LEGO sensor product) you can use this block to read with more precision the value of a color creating new limits of reflection. I am going to talk more deeply about how to read with more precision using this method. 

<h2>Raw Sensor Value Block:</h2>

