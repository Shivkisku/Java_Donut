## Java_Donut


The Donut class is defined, which contains the main method, the entry point for the program.
Two float variables A and B are initialized to 0, which are used to control the movement and rotation of the donut.
Two arrays, z and b, of type float and char are created with sizes 1760, used to store the z-buffer and the characters for the ASCII art, respectively.
The line System.out.print("\033[2J"); is used to clear the console at the beginning of the program.
The program enters an infinite loop using for(;;). Inside this loop, the arrays b and z are filled with default values.
Two nested loops are used to calculate the positions and characters for the ASCII art, using trigonometric functions such as Math.sin and Math.cos for the 3D rendering.
The calculated values are used to update the arrays b and z with the appropriate characters and z-buffer values based on the calculated conditions.
The code then prints the ASCII art to the console using System.out.print("\033[H") and a loop that iterates over the array b.
The values of A and B are incremented by 0.04 and 0.02, respectively, in each iteration to create the spinning effect.
The code essentially creates a rotating donut-like figure using ASCII characters and simple math calculations to simulate a 3D effect.




#### cmd to run this 

```
javac Donut.java
```

```
java Donut
```
