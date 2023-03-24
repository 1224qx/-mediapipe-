# -mediapipe-
MediaPipe：Google Research 开源的跨平台多媒体机器学习模型应用框架

MediaPipe的Python安装： 
（1） 安装 opencv pip install opencv-python 
（2） pip install mediapipe 直接安装由于网络问题

有些包下载不了，可以到https://pypi.org/project/ 手动下载相关的whl文件，利用pip install xxx.whl进行手动安装。

对手设立关键点，利用相应关键点构建一个凸包，通过计算剩余关键点谁在凸包外来进行简单的手势识别。
