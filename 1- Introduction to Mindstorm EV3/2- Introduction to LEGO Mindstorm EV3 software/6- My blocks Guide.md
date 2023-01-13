<h1 align="center"> My Blocks Guide </h1>

<p align="center">
  <img src="https://user-images.githubusercontent.com/101992463/212257608-70ac7931-aa55-45a8-a3fc-3287b1472c3c.PNG">
</p>


This is a really important part when you want to create an advanced program for your robot because in this section you will visualize all the custom blocks that you create. At first this section will be empty because you need to create a block to visualize your block here. so next I will show you how to create a custom block. 

<h2>Create your block:</h2>

If you have ever programmed you can see this part like a function that receives a value and returns a processed value, it's not obligated that your function receive a value or return a value that depends on you and whatever you do with your function. 

Well, knowing that, I going to show you a little example about how to create your custom block, this block will be about a simple line follower with the type of control ON-OFF this type of control is one of the easier type control to follow a line, so the block will receive a number that will be the set point to follow the line (If you don't understand something dont worry in the next sections I going talk deep of these types of follower control) and whit this value generate an action in the direction of the motors. 

And this is how the program looks:

![SimpleLineFollower](https://user-images.githubusercontent.com/101992463/212253912-4a079000-32bb-411f-bf5d-74f25ee4a26f.PNG)

Next, having all the components and conditions that you want in your block you only need to select all the blocks that you want to convert into a custom block or in your function and next go to "Tools --> My block builder".

![MyBlockBuilder](https://user-images.githubusercontent.com/101992463/212254339-b05ae74f-3f89-45d8-905a-f5298d5b413c.png)

Now, new windows will appear where you need to put a name for your block and if you want to create a description of the functionality of your block, also you can select a custom icon to represent the functionality of your block.

![NewWindows](https://user-images.githubusercontent.com/101992463/212251177-80ac4659-7749-485e-83c7-c72768a9303c.png)

I marked in a red square the section where you can add an input or an output of you block in my case my block needs a input where I going to introduce the value of my setpoint so, the to touch the button plus you need to configure your input or output you can send or receive 5 differents types of data like: "Number, Logic, Text, Numeric array and Logic array" in my case I need to set a number value. And in the section of the “parameter icon” you can select a custom icon that represents the type of data that you will send or receive from your function.Also you can select how you want to introduce the data you can do it using a slide bar or simply write the value that is my case.

![FinalConfiguration](https://user-images.githubusercontent.com/101992463/212253253-d63cea22-2dbe-496a-9fe1-341fa6cb26de.PNG)

Once you configure all that you want and personalize click on finish and a totally new block will appear. 

![NewBlockCreated](https://user-images.githubusercontent.com/101992463/212255177-257a1b6f-16a2-4bac-a47e-c32bc8163bf5.PNG)

If you want to edit your block you can do it by clicking on the gear icon in the top left of your block. And If you can see now we will have a block in the part of "My blocks" in the program and you can use this block like the rest of the other blocks. 

Now to complete your block by double click you can go into your block and see all the components and blocks that the block uses, so, in this part you only need to connect the input wherever you want to use that value. In my case I get the value of the setpoint and I stored that value in a variable to then read it and compare to create an action on my robot.

![CompleteBlock](https://user-images.githubusercontent.com/101992463/212257168-2e9f8d69-46f4-4f22-9486-f4f740625d18.PNG)

Now using this block my robot is ready to follow a line.

![Totallyfinished](https://user-images.githubusercontent.com/101992463/212257501-9d1505a1-4fe7-4323-939e-cad0ca065793.PNG)



