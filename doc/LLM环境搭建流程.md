# 牛马之路 -- 以ChatGLM为例

## 1.查看需要大模型的pytorch版本
## 2.去pytorch官网查看需要的cuda

- [Start Locally | PyTorch](https://pytorch.org/get-started/locally/)

## 3.去英伟达官网下载cuda

- [Linux安装CUDA & 添加环境变量 & 多版本CUDA切换 (软链接)_cuda安装 linux-CSDN博客](https://blog.csdn.net/m0_46093829/article/details/128073309)

## 4.安装cuda
- 先安装缺少的包
- - apt-get install libxml2
  - apt-get update
  - apt-get install kmod dkms
  - sudo
- 添加路径[linux用户下更换cuda版本及部分细节_linux更新cuda__Keep _Going的博客-CSDN博客](https://blog.csdn.net/qq_44759942/article/details/131784977)

## 5.下载模型

- 由于实验室服务器访问huggingface的问题，建议启动本地模型

## 6.使用模型

- [ChatGLM2微调保姆级教程~ - 知乎 (zhihu.com)](https://zhuanlan.zhihu.com/p/641047705)
- 仅加载模型约占用显存13G