### import cv2

```
kangyong@XX:~$ python3.4
Python 3.4.3 (default, Oct 14 2015, 20:28:29) 
[GCC 4.8.4] on linux
Type "help", "copyright", "credits" or "license" for more information.
»> import cv2
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
ImportError: No module named 'cv2'
```

先执行 export PYTHONPATH="${PYTHONPATH}:/opt/lib/python3.4/dist-packages"

```
康勇, [31.05.16 10:56]
咋样才能让我本地的python3支持cv2？ ubuntu apt-get install pyhon-opencv  ，无python3-opencv

Isaac Ge, [31.05.16 10:57]
重新编译 OpenCV 3, 让它检测到 Python 3 解释器

康勇, [31.05.16 10:56]
咋样才能让我本地的python3支持cv2？ ubuntu apt-get install pyhon-opencv  ，无python3-opencv

Isaac Ge, [31.05.16 10:57]
重新编译 OpenCV 3, 让它检测到 Python 3 解释器

此外还要装 Python 3 的 numpy 库

先装 Python 3 的 numpy 库，再重新编译 OpenCV 3

```
install

```
sudo apt-get install python3-numpy

```

then cmake opencv-3.1.0

```
--   Python 2:
--     Interpreter:                 /usr/bin/python2.7 (ver 2.7.10)
--     Libraries:                   /usr/lib/x86_64-linux-gnu/libpython2.7.so (ver 2.7.10)
--     numpy:                       /usr/lib/python2.7/dist-packages/numpy/core/include (ver 1.8.2)
--     packages path:               lib/python2.7/dist-packages
-- 
--   Python 3:
--     Interpreter:                 /usr/bin/python3.4 (ver 3.4.3)
-- 
--   Python (for build):            /usr/bin/python2.7
```
install python3-numpy ,but display numpy and Libraries..

must rm -fr *


pip3 install numpy
opencv-3.0

