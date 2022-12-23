# How to install c/c++ environment in VS code
1. Install Visual Studio Windows C/C++ build tools (MSVC)
  
2. Install VS code
  
3. Install code runner extension in VS code
  
4. Install C++ IntelliSense extension in VS code
  
5. Download the MinGW g++ compiler and install that,
  
  ([Download MinGW - Minimalist GNU for Windows from SourceForge.net](https://sourceforge.net/projects/mingw/files/Installer/mingw-get-setup.exe/download?use_mirror=altushost-swe&download=&failedmirror=deac-ams.dl.sourceforge.net))
  
  select the following options and proceed with the installation,
  ![2022-12-23-18-39-42-image](https://user-images.githubusercontent.com/45464612/209340901-4d7fe0fc-f346-400a-98db-2fdee94f0422.png)
 once the download process is finished, select these files to be installed,
![2022-12-23-18-41-06-image](https://user-images.githubusercontent.com/45464612/209340925-b3490457-289c-43b8-b216-158ab6aedd65.png)


  
6. Add "C:\MinGW\bin" to your environment variable path,
  
7. Download the stdc++.h file and put it under this location on your PC,
  
  ```
  C:\Program Files (x86)\Microsoft Visual Studio\2022\BuildTools\VC\Tools\MSVC\14.32.31326\include\bits
  ```
  
8. Next, we need to open our VS code and fix something in the settings, check this box,
 ![2022-12-23-18-56-01-image](https://user-images.githubusercontent.com/45464612/209341000-518133a3-b492-4b29-a5db-0abc29afa90c.png)

  
  

We are good to go now; if you run the code using the play/run button, you should see something like this,
![2022-12-23-19-00-20-image](https://user-images.githubusercontent.com/45464612/209341025-787b9794-bb1f-431c-b5fa-7f9839489ffc.png)

