# SegConvert  | 实例分割标注格式转换



## 概要

[标注工具ISAT](https://github.com/yatengLG/ISAT_with_segment_anything) 是一个基于[Facebook的实例分割框架SAM(Segment Anything Model)](https://github.com/facebookresearch/segment-anything) 的实例分割标注软件。使用它可以鼠标点一点就可以实现实例分割的标注，极大提升数据标注效率。作者使用的实例分割标注格式是自己定义的ISAT格式， 而使用YoloV8则需要转换为Yolo格式。 如果使用MaskRCNN则需要转换为COCO格式。

**本仓库是实例分割标注文件格式转换脚本工具集， 提供了将ISAT格式转换为Yolo与COCO格式的转换脚本。**

----

作者: 阿凯爱玩机器人 | 微信: xingshunkai  | QQ: 244561792 | [B站](https://space.bilibili.com/40344504) 



## ISAT标注工具

效果展示: [集成segment anything的图像分割标注工具](https://www.bilibili.com/video/BV1Lk4y1J7uB/)

Github代码仓库: https://github.com/yatengLG/ISAT_with_segment_anything

**标注软件具体看作者的视频， 还有Github代码仓库上的Wiki**。

**注意事项** : 在安装的时候，不要一股脑的执行一键安装依赖的操作， 容易把环境搞坏， 安装最新版就可以， 版本号不需要一致。 另外不要安装`requirement.txt` 里面的`opencv-python-headless`。

**常用快捷键**

* `Q` 开始选择Segment Anything进行标注
* `E` 完成标注
* `S` 保存当前的标注
* `D` 下一张图片
* `A` 上一张图片

----

[B站](https://space.bilibili.com/40344504) | [淘宝店铺](https://shop140985627.taobao.com) | [Gemini2 双目结构光3D相机-购买链接](https://item.taobao.com/item.htm?id=710217613927)

<img src="./Gemini2.png" style="zoom:50%;" />
