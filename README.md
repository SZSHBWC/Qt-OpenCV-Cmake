# Qt-OpenCV-Cmake
OpenCV460Cmake是使用Cmake编译的OpenCV-4.6.0，不包含拓展包。

  使用时将x:\xxx\OpenCV460Cmake\x64\mingw\bin添加到环境变量中。（x:\xxx更改为自己的路径）
  
  测试环境：Qt5.14.2 MinGW 7.3.0 64-bit
  
  在Qt中使用时，将以下两行添加到.pro文件中：
  
  INCLUDEPATH += x:\xxx\OpenCV460Cmake\include
  
  LIBS += x:\xxx\OpenCV460Cmake\x64\mingw\bin\libopencv_*.dll
