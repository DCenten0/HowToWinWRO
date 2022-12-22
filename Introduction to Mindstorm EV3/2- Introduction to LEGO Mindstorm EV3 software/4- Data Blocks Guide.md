<h1 align="center"> Data Blocks Guide </h1>

<p align="center">
  <img src="https://user-images.githubusercontent.com/101992463/209065198-5e308558-fcec-41bf-a29a-35adbdb10378.PNG">
</p>

In this section will we see the Data Operations Blocks that include the Math block, the Random block, the Compare block, and the Logic Operations block. Each block has its own function, but they all process values carried by data wires and generate new values based on the input values.

<h2>Variable Block:</h2>

![VariableBlock](https://user-images.githubusercontent.com/101992463/209067063-08457f77-a82b-4a63-a195-32a8ef3b8566.PNG)

The Variable block lets you read or write a Variable in your program. You can also create a new Variable and name it.

A Variable is a location in the memory of the EV3 Brick that can store a data value. You can write to a Variable to store a data value.
Later in the program, you can read from the Variable to access the stored value.

Each variable has a Type and a Name. The different Types are Numeric, Logic, Text, Numeric Array, and Logic Array.

You can choose the Name of the variable, which is used to identify the variable.

You can change the value of the variable while the program is running. 

For example you create a program that registers the intensity light every second in the variable called "Intensity_Light_Value" and every second that passes the value will be updated in the same variable. 


<h2>Contants:</h2>

![ConstantsBlock](https://user-images.githubusercontent.com/101992463/209068838-63b66be5-39b1-4f6a-bbfa-3cd19a1be9c8.PNG)

The Constant block lets you enter a value that you can use in several different places in your program.

The funtion it is to similar as the Variable Block but if you change the value of the constant, all places where you use the constant will get the updated value.


<h2>Array Operations Block:</h2>

![ArrayBlock](https://user-images.githubusercontent.com/101992463/209072899-b4cffa6c-3bdc-4850-9edd-ed7b7a040624.PNG)

The Array Operations block does operations on the Numeric Array and Logic Array data types.

You can create an array, add elements, read and write individual elements, and get the length of an array.

<h3>Modes:</h3>

- **Append:** With this function you can insert a value at the end of the array. Works in logic and numerical mode. 
- **Read at Index:** As the name says you can read a specific value indicating the index of the array. Works in logic and numerical mode. 
- **Write at Index:** It is similar to the last one but now you indicate the index of the array to introduce or update a value in that position. Works in logic and numerical mode.
- **Length:** This function only returns the length of the array. Works in logic and numerical mode. 

<h2>Logic Operation Block:</h2>

![LogicBlock](https://user-images.githubusercontent.com/101992463/209075096-08380cdc-4a15-46f0-bb17-4217a6a7d361.PNG)

The Logic Operations block does a Logic operation on its inputs, and outputs the result.

A Logic operation takes inputs that are True or False, and produces a True/False output.

The Logic operations available are AND, OR, XOR, and NOT.
　
Choose the Logic operation you want to use by selecting a mode with the Mode Selector.

The block will calculate the Result based on the Inputs, as shown in this table.

**Here I give you a Truth Tables of every possible output using every mode:**






