# Visual Studio openfolders with cmake and vcpkg
<br>
Base C++ project utilizing vcpkg, CMake ninja multi-config and VS open folders.<br>
You can finally add files, folders and work on your project from within IDE without the need to edit cmake files!<br>
Automatically detects changes in CMake files and rebuilds project if needed<br>
Consume libraries from VCPKG, with fmt example in vcpkg.json and /src/CMakeLists.txt<br>
It also has support for custom vcpkg ports, which goes to .vcpkg folder - this project doesn't show how to use those though


<br>
Requirements:<br>
- environment variable named VCPKG_ROOT and the value should be a path to where vcpkg is installed.<br>
- CMake 3.20 and above<br>
<br>
On windows, simply right-click in root folder of the repository and select option "Open with Visual Studio"<br>


![image](https://user-images.githubusercontent.com/16348711/182658136-1b918d5b-2d47-4a8a-8b07-431b2d32849f.png)

Wait until cmake generation is done and code away. If you want to launch app with debugger, you need to change this setting:
![image](https://user-images.githubusercontent.com/16348711/182663696-521f24f1-4e01-47c5-b6bd-8ef8e5e7acc9.png)

to whatever your project is named - in my case OpenfoldersBaseProject.exe<br>
<br>
On linux, i assume you know what you're doing. You need to add a linux build preset in CMakePresets.json and execute cmake preset via command
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
Consider buying me a coffee if you found it useful<br>
https://www.buymeacoffee.com/Riztazz 

