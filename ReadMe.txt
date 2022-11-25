1. How to build the project
   - This project can be built with x64 configuration / Debug or Release Mode

   - How to build with MSBuild
   a) Download solution(or zip) file through Git.
   b) Open the MSBuildCommand.txt file.
   c) Replace "<Solution File Path>" to the directory where the solution is located actually.
   d) Input the command in the cmd window.

   - If you build with visual studio
     you can execute the application with visual studio,
     or with "3DScene.exe" flie in x64/Debug(Release) folder.

   - If you build with MSBuild
     you can execute the application with "3DScene.exe" in c:\cnd\Jihye_Yoon folder.

   - My coding work of project file is at the bottom of the file between annotations like below:
     <!--▼▼▼ BELOW HERE IS MY CUSTOM WORK ▼▼▼-->
     <!--▲▲▲ ABOVE HERE IS MY CUSTOM WORK ▲▲▲-->
     Worked file name: 3DScene\3DScene.vcxproj

   - Output Folder:
     C:\cnd\Jihye_Yoon

   - Files saved in output folder:
     3DScene.exe (Application execution File)
     DLL files (For OpenGL, Fmod, Personal Engine)
     Assets Folder (For all resources)
     Jihye_Yoon.zip (Zip file that includes all files in the output folder)

   - GitHub Link:
     https://github.com/kanious/Project03_MSBuild



2. User Input Option

 < For exploring OpenGL Scene >
 * WASD : Moving Camera (look/right direction).
 * Space/Left Shift : Up/Down Camera (up direction).
 * Alt : Enable/disable mouse. Rotating camera with mouse move when mouse is disabled.
