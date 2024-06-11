**Learning CUDA and TensorRT**

A large number of CUDA/TensorRT examples are provided in this project.

- **CUDA Driver API**
- **CUDA Runtime API**
- **Introduction to TensorRT Basics**
- **Basic TensorRT Learning**
- **Plugins and ONNX Parser**
- **Advanced TensorRT Applications**
- **Exporting ONNX Models, Preprocessing, and Postprocessing**
- **Handling Complex Situations with Specific Project Examples**

This is a source code project for learning CUDA and TensorRT through examples. It covers a wide range of cases, from basic CUDA driver and runtime APIs to introductory and advanced TensorRT concepts. It also includes model export, preprocessing, postprocessing, and multithreading encapsulation.

**Usage Instructions - Manual Environment Configuration**

- All examples use Makefile as the build tool.
- Special variables like `${@CUDA_HOME}` should be replaced with your system's actual environment values.
- After configuration, you can usually compile and run with `make run`.

**Usage Instructions - Automatic Environment Configuration**

- Requires a Linux system (Ubuntu 16.04 or higher) with GPU and NVIDIA driver version 495 or higher.
- Install the Python package: `pip install trtpy -U -i https://pypi.org/simple`
- Set up shortcut: `echo alias trtpy="python -m trtpy" >> ~/.bashrc`
- Apply shortcut: `source ~/.bashrc`
- Configure key: `trtpy set-key sxaikiwik`
- Fetch and configure environment: `trtpy get-env --cuda=11` (supports CUDA versions 10 and 11 only)
- Automatically update configuration variables: `trtpy prep-vars .` to replace all variables in the current directory.
- Run with `make run`

**References**

- [TensorRT Bilibili Video Explanation](https://www.bilibili.com/video/BV1Xw411f7FW)
- [Official Video Explanation](https://www.bilibili.com/video/BV15Y4y1W73E)
- [TRTPy Introduction Document](https://zhuanlan.zhihu.com/p/462980738)
- [Video Tutorial for This Source Code (Tencent Classroom)](https://ke.qq.com/course/4993141)
