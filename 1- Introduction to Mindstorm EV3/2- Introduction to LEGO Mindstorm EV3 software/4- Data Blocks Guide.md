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

- **AND Gate**

<table>
  <tr>
    <th>A</th>
    <th>B</th>
    <th>A.B</th>
  </tr>
  <tr>
    <td>0</td>
    <td>0</td>
    <td>0</td>    
  </tr>
  
  <tr>
    <td>0</td>
    <td>1</td>
    <td>0</td>  
  </tr>
  
  <tr>
    <td>1</td>
    <td>0</td>
    <td>0</td>  
  </tr>
  
  <tr>
    <td>1</td>
    <td>1</td>
    <td>1</td>  
  </tr>
  
</table>

- **OR Gate**

<table>
  <tr>
    <th>A</th>
    <th>B</th>
    <th>A.B</th>
  </tr>
  <tr>
    <td>0</td>
    <td>0</td>
    <td>0</td>    
  </tr>
  
  <tr>
    <td>0</td>
    <td>1</td>
    <td>1</td>  
  </tr>
  
  <tr>
    <td>1</td>
    <td>0</td>
    <td>1</td>  
  </tr>
  
  <tr>
    <td>1</td>
    <td>1</td>
    <td>1</td>  
  </tr>
  
</table>

- **XOR Gate**

<table>
  <tr>
    <th>A</th>
    <th>B</th>
    <th>A.B</th>
  </tr>
  <tr>
    <td>0</td>
    <td>0</td>
    <td>0</td>    
  </tr>
  
  <tr>
    <td>0</td>
    <td>1</td>
    <td>1</td>  
  </tr>
  
  <tr>
    <td>1</td>
    <td>0</td>
    <td>1</td>  
  </tr>
  
  <tr>
    <td>1</td>
    <td>1</td>
    <td>0</td>  
  </tr>
  
</table>

- **NOT Gate**

<table>
  <tr>
    <th>A</th>
    <th>NOT A</th>
  </tr>
  
  <tr>
    <td>0</td>
    <td>1</td>  
  </tr>
  
  <tr>
    <td>1</td>
    <td>0</td>  
  </tr>
  
</table>

<h2>Math Block:</h2>

![MathBlock](https://user-images.githubusercontent.com/101992463/209078447-ba68489c-0c95-4070-a539-cb48cc311aea.PNG)

The Math block does a math calculation on its inputs, and outputs the result.

You can do a simple math operation with one or two inputs, or enter a formula with up to four inputs.

Choose the math operation you want to use by selecting a mode with the Mode Selector.

After selecting the mode, you can choose values for the inputs. The inputs available will change depending on the mode.

If you want to do a more complicated equation you can use the advanced mode and introduce your equation. 

<h2>Round Block:</h2>

![RoundBlock](https://user-images.githubusercontent.com/101992463/209078997-2906571d-37c7-466e-a67c-3c5ac0b20cdf.PNG)

The Round block rounds a decimal number to an integer value.

- You can round a number up, down, or to the nearest integer.
- You can also truncate a number to a certain number of decimal places.
 
Use the Mode Selector to choose the type of rounding to use.

<h2>Compare Block:</h2>

![CompareBlock](https://user-images.githubusercontent.com/101992463/209079448-5e352a25-7471-4bd0-9197-5f96c99d3ee4.PNG)

The Compare block compares two numbers to find out whether they are equal, or which number is greater. You can choose one of six different comparisons.

The output result is True or False.

<h2>Range Block:</h2>

![RangeBlock](https://user-images.githubusercontent.com/101992463/209079818-5b867536-2308-416a-b8f9-b1f9ffac7df4.PNG)

The Range block tests whether a number is inside or outside a specified numerical range.

The Result will be set to True or False, based on the result of the comparison.

<h2>Text Block:</h2>

![TextBlock](https://user-images.githubusercontent.com/101992463/209080149-815c4c31-df77-418b-8a0a-e1986a640781.PNG)

The Text block can combine up to three text strings into one text string.

You can utilize this block to show information on the screen. 

<h2>Random Block:</h2>

![RandomBlock](https://user-images.githubusercontent.com/101992463/209080566-5c7e0927-ae83-4f5e-9086-cd878a48766e.PNG)

The Random block can output a random Numeric or Logic value.

- In the numeric mode you select the limits to appear a number. 
- With the logic mode you indicate the percentage of appearance of True. 
