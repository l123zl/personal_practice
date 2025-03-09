# 安装Anaconda教程（中科大镜像源已失效）
https://blog.csdn.net/qq_44000789/article/details/142214660
.condarc文件修改如下（添加镜像源）
channels:
  - defaults
show_channel_urls: true
default_channels:
  - https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/main
  - https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/r
  - https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/msys2
custom_channels:
  conda-forge: https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud
  msys2: https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud
  bioconda: https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud
  menpo: https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud
  pytorch: https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud
  simpleitk: https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud
# Anaconda 修改base 环境read only
https://blog.csdn.net/i1yo_kiki/article/details/134096362
# 安装cuda（安装时第一次不用管，第二次自定义设置更改路径，不要设置同一路径下）
https://blog.csdn.net/Stromboli/article/details/142705892
# 安装cudnn（下载压缩包就行）安装pytorch-gpu（在官网找对应版本）
https://blog.csdn.net/m0_68220374/article/details/144835095
# 安装opencv-python(到清华源查找对应版本下载 ，opencv-python，opencv-contrib-python)
https://pypi.tuna.tsinghua.edu.cn/simple/opencv-python/
# 解决pip下载速度慢的问题(extra-index-url配置时只能出现一次)
https://blog.csdn.net/qq_43811536/article/details/141963366
