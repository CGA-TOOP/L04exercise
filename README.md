# Lesson 05 In Class exercise - Your First C++ Program
## Overview
Let's compile your first program in VSCode!  This example is based upon [cplusplus.com](https://www.cplusplus.com/doc/tutorial/program_structure/)

## Your first program
### Step 1
Open VS Code. 

### Step 2
Organize your file system.  Create a TOOP directory in ~/Documents.  Insde that TOOP folder, create additional directories for assignments/homeworks etc.  

>**Note**
  >Organize your file system such that all the files for each assisgnment are in their own directory.

Once created, go to VS Code, select File > Open Folder, and select the folder you just created.  

### Step 3
From VSCode, open up your directory under the explorer window and create a new .cpp file.  Name this file `HelloWorld.cpp`

### Step 4
Copy and paste the following code into your .cpp file.

```
// my first program in C++
#include <iostream>

int main()
{
  std::cout << "Hello World!";
}
```
### Step 5
Select the Run and Debug icon.  When prompted, be sure to select `C/C++:g++ build and dubug active file`. This ensures that you use the G++ compiler that you installed previously.

Once you have selected that you should be able to see the result of your program in the terminal window at the bottom of VS Code.

## More Practice
### Step 1
Create a new project directory and open the directory in vscode

### Step 2
Create a new .cpp file and use the following code.

```
//File: main.cpp
//Name: (Your name here)
//Class: TOOP03
//Description: Walk through of the basics of C++
//Date: (Today's date)

#include <iostream>

int main()
{
  int i = 100;
  char c = '!';
  double d = 20.01;
  bool b = true;
  std:cout << "i times d is " << i*d;
  return 0;
}
```

### Step 3
Add a comment to each row of code with some notes and observations of what that line of code does.





  
