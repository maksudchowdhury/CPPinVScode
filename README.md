# How to install c/c++ environment in VS code
1. Install Visual Studio Windows C/C++ build tools (MSVC)
  
2. Install VS code
  
3. Install code runner extension in VS code
  
4. Install C++ IntelliSense extension in VS code
  
5. Download the MinGW g++ compiler and install that,
  
  ([Download MinGW - Minimalist GNU for Windows from SourceForge.net](https://sourceforge.net/projects/mingw/files/Installer/mingw-get-setup.exe/download?use_mirror=altushost-swe&download=&failedmirror=deac-ams.dl.sourceforge.net))
  
  select the following options and proceed with the installation,
  
  ![](file://C:\Users\Maksud\AppData\Roaming\marktext\images\2022-12-23-18-39-42-image.png?msec=1671799182962)![](file:///C:/Users/Maksud/AppData/Roaming/marktext/images/2022-12-23-18-41-06-image.png?msec=1671799278546)
  ![](file:///C:/Users/Maksud/AppData/Roaming/marktext/images/2022-12-23-18-41-49-image.png?msec=1671799315866)
  
6. Add "C:\MinGW\bin" to your environment variable path,
  
7. Download the stdc++.h file and put it under this location on your PC,
  
  ```
  C:\Program Files (x86)\Microsoft Visual Studio\2022\BuildTools\VC\Tools\MSVC\14.32.31326\include\bits
  ```
  
8. Next, we need to open our VS code and fix something in the settings, check this box,
  
  ![](file://C:\Users\Maksud\AppData\Roaming\marktext\images\2022-12-23-18-56-11-image.png?msec=1671800171279)
  

We are good to go now; if you run the code using the play/run button, you should see something like this,
