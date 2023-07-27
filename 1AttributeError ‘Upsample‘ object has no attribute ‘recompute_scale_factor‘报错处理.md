YOLOV5-6.1AttributeError: ‘Upsample’ object has no attribute 'recompute_scale_factor’报错处理
本报错为Acaonda环境配置报错
点击报错里的

![img](https://img-blog.csdnimg.cn/82b0ca5899c94483a6a549922752958c.png)

进入到upsampling.py
更改forward函数，复制一遍，去掉下面一行的代码即可

![img](https://img-blog.csdnimg.cn/29cf7b30fef84aaead6d33efe9fa1f4b.png)



原文链接：https://blog.csdn.net/qq_42578742/article/details/123582773

