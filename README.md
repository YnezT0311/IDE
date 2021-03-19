# IDE
This is a mini IDE for fun, including editor, assembler, simulator, linker and compiler. There are two edition, one for MacOS and one for Win
<br>
## 1. System/lib
To use this code, you need to unpack the lib.zip file. This is a modified edition of Stanford C++ Library.
For more information, you can refer to: https://web.stanford.edu/dept/cs_edu/cppdoc/
<br>
<br>
## 2. User Manul
The following guides the user through the process of deploying our project, we aslo made a demo video available at
https://cuhko365-my.sharepoint.com/:v:/g/personal/118010073_link_cuhk_ edu_cn/EdASXJhSaB9HpB4hc1ux0nYBE6n1qX8jKQZitle58mAMjQ?e=ciH8pl
<br>
### Installation: 
Download our Qt Mega project to your two personal computer. We have two versions available depending on your operating system, one for Windows 10, the other for MacOS. Folder for MacOS is named “Project”, folder for Windows 10 is named “Project Win”. A Qt environment is required, version is expected to be the latest.
<br>

### Prepare for our project: (Mac as example)
1. Find and click Original.pro, and build this Qt project.
2. Under the Qt Debug folder, Find and move the Original.app (Original.exe for
windows) into the Project(Project Win for windows) folder.
3. Find and click Editor.pro, build and run it with Qt creator.
<br>
Notice: due to a lack of Debug folder to optimize memory, the following scenario might occur, if so, do not worry, close it and build it again.
<br><br>

4. An editor window should pop up already. The user can then enter any program he or she wish to test it, note the following points:
<br>
a. If the user simply copy and paste another program inside, the IDE will con- sider not editing is in procress, so make sure in this case, type something extra like a blank space to notify the IDE.
b. The programming language we supoort is almost the same as C++. Minor di↵erences are in ways of input and output, as well as our main program does not have a return value, libary inclusion and namespace. You can only edit under the main function. PS: You may find some prepared sample test files available under the project folder.
c. The supported functions include all the essentials of empirical programming. For example, arithmetic at any level of complexties, logic operator( and/or ), if, for and while loop, input and output. Four data types are supported: int, char, int array, char array (Like string).
Notice, the user is recommended to look into appendix C for details about for functions of C++ we support and what di↵erences we have with standard C++
d.During editing, we implemented common features of C++ program editor that will bring convinience for the program. These features including, di↵er- ent color for di↵rent syntax, auto-suggestion list of keywords, auto-completion of brackets, state bar for operation instructions etc. The user can look into our editor section to get more details.
e.When finishing the editing of the program. To execute the program, the user should press the run button directly and then he or she will be prompted to save the file in any directory and the execution follows.
f.Note, input must be entered in English Mode instead of Chinese or others to ensure the success of the execution.

<br><br>

### After Execution
By now, we are capable of executing the program and the user should get the interaction or results he or she is expecting. However, note it is really hard to demonstrate our work of compiler, assembler and simulator, since they are mostly performing low-level software or even (virtual) hardware tasks, so they do not have any user friendly output. To shed more lights on these components, the user will see the next additional features other than the normal output of his or her program.

<br>

• First, the user can check the same folder he or she stored the original program, there will be two new files that are the corresponding MIPS assembly and binary equivalents, translated by compiler and assembler respectively.
<br>
• We believe the simulator is the most crucial component since it can leverage all the work done by the previous ones, from a high level language program, we now have a binary program that follows strict rules and syntax. Therefore, when executing the program, whenever an instruction pointed by the program counter is currently being executed, we will print the its location in memory. Whenever the content of any register is changed, we will print out this information. Whenever a branching occured, the destination will be printed. All data loading from the data segment of main memory will also be wise to the user.
<br>
• For user-friendly concerns, all helping information mentioned above will be printed out in a di↵rent color then the actual output of the program.
<br><br>

### Notice: the full edition of user manual is also uploaded
