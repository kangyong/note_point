### Caffe
1. caffe complie
```
cudnn 
/tmp/....
```
cudnn没有安装好。
解决方法：
A. CMakeLists.txt中OFF掉cudnn

```
# caffe_option(USE_CUDNN "Build Caffe with cuDNN library support" ON IF NOT CPU_ONLY)
caffe_option(USE_CUDNN "Build Caffe with cuDNN library support" OFF)
```
### OpenCV



### Python


### C++






