# Autofishing_Playtogether
Auto fishing using OpenCV and Win32api.sendmessage
## 1. Overview
Autofishing is a tool that was made by me. It will help you fishing in Play together. Let’s take a look of how it works.
- Detect and meansure the fish shadow
  * Raw image: <br />
 ![Raw](https://github.com/Uranium1901/Autofishing_Playtogether/blob/15603354d42f793cfb709837f59f52e41fdbab1b/Example/raw.jpg)
  * Preprocess image: <br />
 ![Preprocess](https://github.com/Uranium1901/Autofishing_Playtogether/blob/15603354d42f793cfb709837f59f52e41fdbab1b/Example/preprocess.jpg)
  * Result: <br />
 ![Preprocess](https://github.com/Uranium1901/Autofishing_Playtogether/blob/d9713f480f076cedd0e096fb12f2bca80e738e1e/Example/result.jpg)
- Detect exclamation mark when pixel value be changed
  * Exclamation mark: <br />
  ![Exclamation mark](https://github.com/Uranium1901/Autofishing_Playtogether/blob/d51c0db6280358346cc919181414c7a86f282399/Example/exclamation%20mark.jpg)
 ## 2. How to use
  1. Instalation
  - LDPlayer emulator
  - Python version 3.9.6
  ```
  pip install pywin32
  pip install numpy
  pip install imutils
  pip install PyAutoGUI
  pip install scipy
  pip install Pillow-PIL
  pip install opencv-python
  pip install times
  ```
 2. You need to clone the repository using gitbash (if gitbash is already installed) or you can download the zip file.
  ```
  git clone https://github.com/Uranium1901/Autofishing_Playtogether.git
  ```
 3. Setup in emulator :
  * Resolution: 960x540 (dpi 160) <br />
  ![Resolution](https://github.com/Uranium1901/Autofishing_Playtogether/blob/43640c4002bd3b429d96879d69b928c7e50cd6d1/Example/resolution.jpg)
  * You need change language to Vietnamese (Tiếng việt):
  ![Language](https://github.com/Uranium1901/Autofishing_Playtogether/blob/43640c4002bd3b429d96879d69b928c7e50cd6d1/Example/language.jpg)
  * Button: <br />
  ![Button](https://github.com/Uranium1901/Autofishing_Playtogether/blob/43640c4002bd3b429d96879d69b928c7e50cd6d1/Example/SetupButton%20.jpg)
  * You need change highest view (zoomless):  <br />
  ![View](https://github.com/Uranium1901/Autofishing_Playtogether/blob/43640c4002bd3b429d96879d69b928c7e50cd6d1/Example/View.jpg)
 4. Runing file Autofishing.py
## 3. Example
![Example](https://github.com/Uranium1901/Autofishing_Playtogether/blob/43640c4002bd3b429d96879d69b928c7e50cd6d1/Example/Example.gif)
