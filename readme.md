### 特性
* 支持MacOS 10.8以上系统
* 支持windows7 以上系统(32位,64位)
* 支持多屏幕操作
* 支持屏幕实时展示
* 特殊快捷键设置.切换屏幕.切换笔刷等功能
* 支持屏幕旋转，画板旋转，映射区域选择
* windows支持wintab32,windows lnk模式
* windows以及mac的所有绘图软件支持压感
* mac和windows两个版本的驱动交互界面和使用方式几乎一摸一样，没有任何区别。
* **驱动联系邮箱:531401335@qq.com**
### 源码介绍
#### windows
##### 源码包含3大模块，耦合性低
* gui, 主要用于用户交互界面
* TabletDriverSerivce， 主要用于处理数位板的逻辑业务数据。
* wintab, 所有绘图软件都调用wintab的接口，否则绘图软件没有压感状态，相当于无法正常使用。我们重新开发了wintab的相关接口，能够很好的与windows lnk模式一起使用，而且在 win10,win7系统上完美的兼容市面上的绘图软件。

#### MacOS
* 支持10.8以上的系统。整个驱动模块，模拟了手写板的压感，完美兼容了市面上的所有绘图软件。
### 以下软件经过测试,没有任何问题
#### windows测试列表
* Adobe Photoshop
* CorelDRAW 
* Corel PHOTO-PAINT
* openCanvas
* MediBang Paint Pro
* PaintToolSai
* SketchBook 
* windows lnk(win10)
![在这里插入图片描述](https://img-blog.csdnimg.cn/20191002181033276.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L1J1U2hyb29N,size_16,color_FFFFFF,t_70)
#### macOS测试列表
* Artrage_5.0.4 
* Photoshop_2019
* SketchBook Pro 2020
* Corel_Painter_2018
* Adobe_Animate_2019
* Photoshop CS6
### 界面展示，上图是windows,下图为MacOS
* 支持多屏幕扩展,屏幕区域自由选择,等比例缩放,自定义区域设置
* 支持数位板旋转,区域映射
* 支持笔压软硬设置,数位笔按钮设置
* 支持多种数位笔模式,windows lnk, 笔模式,鼠标模式
* 支持数位板快捷键,一键绑定多种组合功能键.以及显示按键状态
* 特殊按键设置
##### 工作区域展示
* 屏幕标识,可拖动映射区域.数位板旋转等等
_windows_
![windows](https://img-blog.csdnimg.cn/20191002181137214.jpg?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L1J1U2hyb29N,size_16,color_FFFFFF,t_70)
__macos__
![mac](https://img-blog.csdnimg.cn/20191229012054417.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L1J1U2hyb29N,size_16,color_FFFFFF,t_70)
###### 数位笔设置展示
* 支持笔尖感应设置,笔压设置.
* 数位板快捷键设置, 特殊快捷键设置.切换屏幕.切换笔刷等功能
* 多种绘图模式
__windows__
![windows](https://img-blog.csdnimg.cn/20191002181145565.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L1J1U2hyb29N,size_16,color_FFFFFF,t_70)
![windows](https://img-blog.csdnimg.cn/20191002181151776.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L1J1U2hyb29N,size_16,color_FFFFFF,t_70)
__macos__
![macos](https://img-blog.csdnimg.cn/20191229012257258.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L1J1U2hyb29N,size_16,color_FFFFFF,t_70)
![macos](https://img-blog.csdnimg.cn/20191229012356879.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L1J1U2hyb29N,size_16,color_FFFFFF,t_70)
##### 快捷键界面展示
* 支持快捷键实时显示
* 多种组合键设置
* 特殊快捷键设置.切换屏幕.切换笔刷等功能



__windows__
![windows](https://img-blog.csdnimg.cn/20191002181204869.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L1J1U2hyb29N,size_16,color_FFFFFF,t_70)

![windows](https://img-blog.csdnimg.cn/20191002181210662.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L1J1U2hyb29N,size_16,color_FFFFFF,t_70)
![windows](https://img-blog.csdnimg.cn/20191002181218612.jpg)
__macos__
![mac](https://img-blog.csdnimg.cn/20191229012515207.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L1J1U2hyb29N,size_16,color_FFFFFF,t_70)![macos](https://img-blog.csdnimg.cn/20191229012622683.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L1J1U2hyb29N,size_16,color_FFFFFF,t_70)
