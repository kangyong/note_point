#### opencv3.1 diff opencv2.4

```
main.cpp:(.text+0x87): undefined reference to `cv::VideoCapture::VideoCapture(cv::String const&, int)'
main.cpp:(.text+0xb1): undefined reference to `cv::VideoCapture::operator>>(cv::Mat&)'
main.cpp:(.text+0x16c): undefined reference to `cv::VideoCapture::~VideoCapture()'
main.cpp:(.text+0x20c): undefined reference to `cv::VideoCapture::~VideoCapture()'
```
opencv3.x add 
add -lopencv_videoio -lopencv_imgcodecs


#### opencv env
出现问题后，一定要参考官网的安装


