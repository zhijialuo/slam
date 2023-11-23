# slam
slam定位和建图
## demo1
定位和建图效果，机器在原始户型图片上反推激光，通过激光数据进行实时建图和定位，并通过探索算法计算机器目标点，导航规划进行探索建图。
https://github.com/zhijialuo/slam/blob/main/demo1/demo-mapping.mp4

## demo2
重定位效果，通过选取一个候选点，通过原始户型图片在候选点位置反推一帧激光雷达，通过全局匹配方式进行重定位，并输出重定位后的点以及误差。使用分支定界算法优化重定位速度。
https://github.com/zhijialuo/slam/blob/main/demo2/demo-relocalization.mp4

PS：以上均未采用成熟的gmapping或cartographer里面的代码，纯属耳濡目染结合自己的理解手写的demo。
