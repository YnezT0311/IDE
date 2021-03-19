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

### Prepare our project: (Mac as example)
1. Find and click Original.pro, and build this Qt project.
2. Under the Qt Debug folder, Find and move the Original.app (Original.exe for
windows) into the Project(Project Win for windows) folder.
3. Find and click Editor.pro, build and run it with Qt creator.
<br>
Notice: due to a lack of Debug folder to optimize memory, the following scenario might occur, if so, do not worry, close it and build it again.
<br>

An editor window should pop up already. The user can then enter any program he or she wish to test it, note the following points:
<br>
1. If the user simply copy and paste another program inside, the IDE will con- sider not editing is in procress, so make sure in this case, type something extra like a blank space to notify the IDE.
2. The programming language we supoort is almost the same as C++. Minor di↵erences are in ways of input and output, as well as our main program does not have a return value, libary inclusion and namespace. You can only edit under the main function. PS: You may find some prepared sample test files available under the project folder.
3. The supported functions include all the essentials of empirical programming. For example, arithmetic at any level of complexties, logic operator( and/or ), if, for and while loop, input and output. Four data types are supported: int, char, int array, char array (Like string).
Notice, the user is recommended to look into appendix C for details about for functions of C++ we support and what di↵erences we have with standard C++
4.During editing, we implemented common features of C++ program editor that will bring convinience for the program. These features including, di↵er- ent color for di↵rent syntax, auto-suggestion list of keywords, auto-completion of brackets, state bar for operation instructions etc. The user can look into our editor section to get more details.
5.When finishing the editing of the program. To execute the program, the user should press the run button directly and then he or she will be prompted to save the file in any directory and the execution follows.
6.Note, input must be entered in English Mode instead of Chinese or others to ensure the success of the execution.

### Notice: the full edition of user manual is also uploaded
