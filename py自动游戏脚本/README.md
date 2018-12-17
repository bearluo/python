# python
连连看

https://blog.csdn.net/jnxxhzz/article/details/81275542

图像相似度算法

https://blog.csdn.net/feimengjuan/article/details/51279629

python 自动游戏脚本

python3.6 + opencv-python + pywin32 + PIL + numpy

若缺失库,这里给出安装命令

pip install opencv-python

pip install pypiwin32

pip install PIL

pip install numpy

使用 pip install PIL 时报如下错误：

Collecting PIL

Could not find a version that satisfies the requirement PIL (from versions: )

No matching distribution found for PIL

可能应是 PIL 已经是 deprecated 了，

参考：
http://stackoverflow.com/questions/20060096/installing-pil-with-pip

使用新的 PIL fork 版的 Pillow 即可。

pip install Pillow
