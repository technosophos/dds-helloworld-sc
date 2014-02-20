dds-helloworld-sc
=================
WIN32 APPLICATION with Visual C++ 2010 Express : Hello World app project

This is the README file of the Hello World Application
      
Author: Darius D. Samah, 20-Feb-2014 (dsamah@luc.edu)


Summary:
--------
This simple app speaks the words "Hello World" and shows the basic programming knowlegde that is required to take an argument and return a string


This file summarizes what you will find in each of the files that make up your Hello_World application.
	hello_World.cpp         - This is the main application source file.
	Hello_world  		- This is the main application project file


Prerequisites:
--------------
1. uninstall .Net Framework 4.5 from your system;	    - Not compatible with visual c++ 2010
2. download .Net Framework 4.0 and install it;              - compatible with visual c++ 2010


Setup:
------
1. Visual Studio 2010 (Version 10) - (http://www.microsoft.com/visualstudio/en-us/products/2010-editions/visual-cpp-express)
2. .NET Framework 4.0
2. Git from Github.com

After compiling your source code in Visual C++ express, one will need to commit their code using Git Bash


Steps to Create a Hello World Application in Visual C++ 2010:
-------------------------------------------------------------

Step 0: Launch Application

Step 1: Create a new C++ Project from Start up page
	
	1.Select "File" -  "New" - "Project".
	
	2.The "New Project" dialog appears:
		
		a. In the "Installed Templates" pane, expand "Visual C++" node and select "Win32".
		b. In the "Name" field, enter "Hello_World" as the project name.
		c. In the "Location" field, choose your working directory, for example, C:\GIT_ROOT\dds-helloworld-sc\source
		d. In "Solution" (if there is one), select "Create New Solution".As mentioned, a solution consists of many related projects. 
		   By default, the solution name is the same as the first project in the solution.Accept the default. You can add more projects 
		   into this solution later
		e. Check "Create directory for solution".
		f. click ok
	
	3. The "Win32 Application Wizard" appears: Click "Next".
		a. In "Application type", select "Console application" (the default).
		b. In "Additional options", select "Empty project".
		c. Click "Finish".

Step 2: Write your program

	1. In the "Solution Explorer" pane (the leftmost pane), expand the "Hello_World" project node ? Right-click on "Sources Files"- "Add" -"New Item.
	
	2. The "Add New Item" dialog appears.
		
		a. In the "Installed Templates" pane, expand the "Visual C++" node and select "Code".
		b. Select "C++ File(.cpp)".
		c. In the "Name" field, enter "hello_world" as the filename
		d. Click "Add".
		e. In the editor pane for "hello_world.cpp", enter the following C++ codes:

	3. In the editor pane for "hello.cpp", enter the following C++ codes:
		
	// hello_world.cpp  : Defines the programmer entry point for the console application.
	//
	#include <iostream>

	int main() {

	std:: cout << "Hello Colleagues, welcome to my world\n";
	system ("PAUSE");

	}

Step 3: Build (Compile and Link) the Project

Step 4: Run the Project


License
-------
The MIT License (MIT)

Copyright (c) 2014 Darius Samah

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

















A basic open source programming code
