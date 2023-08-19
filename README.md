# threejs 3D开发

喜欢的同学给个星星吧 (^_−)☆。 问题交流: wxsuperzay


### 介绍
对于这里的内容，需要你先去了解基础的webgl知识，了解矩阵、向量、透视投影、裁剪空间、视图变换、着色器原理、threejs框架等等内容。

之前在研究webgl和threejs的时候在网上查到了很多资料（包括郭隆邦的很多资料觉得很好），在此对所有小伙伴们表示感谢。这里也把之前研究的内容拆解出来，分享给感兴趣的小伙伴们学习研究和参考。也给大家推荐几本比较好的参考资料：OpenGL着色语言、OPENGL ES 3.0编程指南 第2版、3D游戏与计算机图形学中的数学方法  第3版。


### 文档，及演示
在线文档和演示demo：(http://test.spzay.com/me-smart-ui/)


### 目录结构
```
README.md
three
  |--wall // 光幕
  |--belt // 流动
  |--grow // 生长
  |--fly // 飞线
  |--gradient // 渐变
  |--opcity // 透明
  |--radar // 雷达
  |--line // 包围线
  |--chinaMap // 3D中国地图
  |--star // 粒子系统（星空）
  |--smoke // 粒子系统（烟雾）
  |--engine // 物理引擎
  |--bone // 骨骼动画（最简原理模型）
  |--scenery // 360°实景
  |--walk // 自由行走
  |--fly1 // 飞线（粒子系统版本）
  |--flow // 曲线色彩流淌
  |--train // 抖音挤地铁小游戏
  |--startCloud // 星云
  |--cloud // 蓝天白云
  |--pipe // 管道流动
  |--chip // 碎片化特效（图片）
  |--fence // 电子围栏
  |--road // 路面流光
  |--wave // 动感光波
  |--fire // 烈火燃烧
  |--fly2 // 粒子飞线（优化版）
  |--math
  |   |--boneCurve // 圆锥曲线3D图解
  |
  |--charts
  |     |--pie // 3D图表，饼图
  |
  |--noise // 噪声
  |    |--land // 随机地形，perlin噪声
  |    |--desert // 沙漠地形，perlin噪声
  |
  |--composer // 后期处理
  |     |--bloom // 辉光
  |
  |--gis // 地理信息
      |--earth-color // 五彩地球
      |--earth-star // 星光璀璨
      |--earth-line // 世界地图
```
 
### 使用说明
### #
直接下载项目，进入案例目录，运行index.html文件，即可查看

缺省插件和数据：
cannon-es/cannon-es-0.19.0.js
http://182.43.179.137:81/public/map/世界--国家级行政区域--地理信息数据--.json
http://182.43.179.137:81/public/map/全球夜晚密集亮点（假设）.json
http://182.43.179.137:81/public/3d-models/Soldier.glb
缺省图：
http://182.43.179.137:81/public/images/texture-gradient-left.png
texture-wood2.jpg
texture-fire.png
circle.png
texture-circle-gradient1.png
texture-earth2.png
texture-earth3.png
texture-sand3.jpg
texture-road.jpg
texture-flow-light.png
texture-wood2.jpg
texture-smoke.png
texture-earth.png
circle3.png
texture-wood2.jpg
texture-stone5.jpg
texture-stone3.jpg