YOLOV5-6.1AttributeError: ‘Upsample’ object has no attribute 'recompute_scale_factor’报错处理
本报错为Acaonda环境配置报错
点击报错里的

![1690449066965](C:\Users\28422\AppData\Roaming\Typora\typora-user-images\1690449066965.png)



进入到upsampling.py
更改forward函数，复制一遍，去掉下面一行的代码即可

![1690449080931](C:\Users\28422\AppData\Roaming\Typora\typora-user-images\1690449080931.png)



原文链接：https://blog.csdn.net/qq_42578742/article/details/123582773