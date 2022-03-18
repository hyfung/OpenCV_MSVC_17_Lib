# OpenCV_MSVC_17_Lib
Prebuilt MSVC 17 OpenCV libraries and dlls

# Instruction for MSVS Projects
- `git clone` this repo to `C:\`
- Linker -> Input -> Additional Dependencies
```
C:\OpenCV_MSVC_17_Lib\lib\opencv_calib3d455.lib
C:\OpenCV_MSVC_17_Lib\lib\opencv_core455.lib
C:\OpenCV_MSVC_17_Lib\lib\opencv_features2d455.lib
C:\OpenCV_MSVC_17_Lib\lib\opencv_flann455.lib
C:\OpenCV_MSVC_17_Lib\lib\opencv_highgui455.lib
C:\OpenCV_MSVC_17_Lib\lib\opencv_imgcodecs455.lib
C:\OpenCV_MSVC_17_Lib\lib\opencv_imgproc455.lib
C:\OpenCV_MSVC_17_Lib\lib\opencv_ml455.lib
C:\OpenCV_MSVC_17_Lib\lib\opencv_photo455.lib
C:\OpenCV_MSVC_17_Lib\lib\opencv_ts455.lib
C:\OpenCV_MSVC_17_Lib\lib\opencv_videoio455.lib
```
- VC++ Directories -> Library Directories: `C:\OpenCV_MSVC_17_Lib\lib`

# To static link OpenCV
C/C++ -> Code Generation -> Runtime Library -> Multi-threaded

# Instructions for Qt MSVC
In the project file add these lines
```
C:\OpenCV_MSVC_17_Lib\lib\Release\*.lib
C:\OpenCV_MSVC_17_Lib\lib\Debug\*.lib
```
