# Welcome to Brainlack

Welcome to the Brainlack language documentation. Brainlack is a simple, yet powerful language that uses a unique set of commands to manipulate memory cells and pointers.

    [: This command increments the value in the current memory cell by 1. If the current value is 5, after this command it will be 6.
    ]: This command decrements the value in the current memory cell by 1. If the current value is 5, after this command it will be 4.
    *: This command doubles the value in the current memory cell. If the current value is 5, after this command it will be 10.
    ,: This command triples the value in the current memory cell. If the current value is 5, after this command it will be 15.
    (: This command moves the memory pointer one step to the right.
    ): This command moves the memory pointer one step to the left.
    .: This command outputs the ASCII value of the current memory cell. For example, if the current value is 65, it will output 'A'.
    %: This command clears the memory, setting all cells to 0.

Brainlack reads commands from a file and executes them one by one. If the file cannot be opened, the interpreter will print an error message and exit. Let's learn about it!

## Example
> ```[..*,,(.*).]```<br>

This command sequence will increment the value in the current memory cell twice, double it, triple it twice, move the memory pointer to the right, double the value in the new memory cell, output the ASCII value, move the memory pointer to the left, and output the ASCII value again.

    This can be saved as a `.bl` file and be run with the instructions given later here.

## Understanding Memory Cells and Pointers
In Brainlack, memory is represented as an array of cells, and there's a pointer that can move left or right to different cells. Each cell can hold a numerical value, and the commands you write will manipulate these values and the position of the pointer.

## Writing Your First Brainlack Program
Let's write a simple Brainlack program that increments a memory cell, moves the pointer, and then decrements the new memory cell. Here's how:

1. **Open a new file in your text editor.**
2. **Type the following commands: [.(.]**
3. **Save the file with the name "main.bl".**

This program will increment the value in the first memory cell, move the pointer to the right, and then decrement the value in the second memory cell.

## Debugging your Brainlack Program
If your program isn't working as expected, here are some debugging tips

- **Check your commands:** Make sure you're using the correct commands for what you want to do. Remember, each command in Brainlack has a specific function.
- **Check your memory cells:** If your program involves moving the pointer, make sure you're keeping track of which cell the pointer is currently on.
- **Check your values:** If your program involves manipulating the values in the memory cells, make sure the values are what you expect them to be.

## Running the Project
 _⚡ We will explain how to add bl.exe to PATH here too._

1. Download Brainlack [(bl.exe)](https://github.com/armature64/brainlack/releases/download/v2/bl.exe)
2. Locate the downloaded bl.exe file and put it in a folder named `brainlack`. Put it in the `%USERPROFILE%` directory.
3. Follow the guide to add to PATH based on your operating system.

🪟 **On Windows,** you can add bl.exe to your PATH by following these steps:

1. In Windows search, look up "env" and press "Enter"
2. Click on "Environment Variables...".
3. Under "System variables", find and select the "Path" variable, then click on "Edit...".
4. In the "Variable value" field, add %USERPROFILE%\brainlack.
5. Click "OK" on all dialogs to save your changes.

Once you've added bl.exe to your PATH, you can run a Brainlack program by typing `bl .bl` in your terminal, where `.bl` is the name of your Brainlack program file.
