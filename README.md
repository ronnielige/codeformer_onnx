# 参考资料
* 源码参考：       https://github.com/hpc203/CodeFormer-onnxrun-cpp-py
* csdn文章参考：   https://blog.csdn.net/fengqiao1999/article/details/139027453
* 自己项目代码地址：https://github.com/ronnielige/codeformer_onnx

# 1、安装onnxruntime和opencv
* onnxruntime下载地址： https://github.com/microsoft/onnxruntime/releases
这里要下载早期的onnxruntime版本，最新的版本已经无法调用本项目中的onnx模型，而且接口名称也有改变：ort_session->GetInputName和ort_session->GetOutputName 都已经没有了。
本工程用的onnx runtime版本为 1.5.2，其页面地址为https://github.com/microsoft/onnxruntime/releases?page=4，下载地址为https://github.com/microsoft/onnxruntime/releases/download/v1.5.2/onnxruntime-win-x86-1.5.2.zip
* opencv下载地址：          https://opencv.org/releases/

# 2、opencv配置方法
https://blog.csdn.net/weixin_43889994/article/details/137809523
