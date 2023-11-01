# About:
This file is about my personal file standard for programming.

# Folders:
Folders should be named based on requirements by their programming langauge/IDE/Project first.  
remaining folders will be named with the following requirements:\
\
The main program folder should be named after the project.  It should follow camelCase or use 
snake case in its name to avoid any spaces.\
\
Extra folders within the main program folder should be named by their purpose and follow 
camelCase only.  If there is a namespace contained within then it should be named after that 
namespace (./MyNameSpace/) unless it is within the folder containing the namespace's name 
in which case it is to be named after the class within it or by the general purpose of all 
classes and functions within it.  (./MyNameSpace/MyClass/ or ./MyNameSpace/vectorMath/) if it
is not named after a class or namespace the first letter should not be capitalized.\
\
***Examples:***
1. ./myProject/
2. ./my_project/
3. ./my_project/MyNameSpace/
4. ./my_project/MyNameSpace/MyClass/
5. ./my_project/MyNameSpace/matricies/
6. ./myProject/plans/

# Files:
Files should first be named by requirements by the programming language/IDE/Project first.  
Use defaults to minimize confusion.  Any remaining files should be named by the following:\
\
All files should follow camelCase.  Class names are capitalized.\
\
If the file contains a class, it should be named after that class.  (Vector3D.cs)  
If the file contains only functions and no class then it should be named after what 
the functions within it are supposed to do.  (vectorMath.cs)\
\
If the file is not a file containing code or any programming logic (IE a planning file) it should 
be named by the normal standard within README.md\
\
***Examples:***
1. MyClass.cs
2. vectorMath.cs
3. matrixMath.cs
4. mathGame.cpp
5. pythonExtension.c

# Related links:
[camelCase](https://en.wikipedia.org/wiki/Camel_case)
[snake_case](https://en.wikipedia.org/wiki/Snake_case#:~:text=Snake%20case%20(stylized%20as%20snake_case,subroutine%20names%2C%20and%20for%20filenames )
