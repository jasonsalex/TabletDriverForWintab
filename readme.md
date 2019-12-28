数位板驱动(手绘板驱动)，wintab 8192级压感，TabletDriver通用, 支持windows, mac系统
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
![在这里插入图片描述](https://upload-images.jianshu.io/upload_images/4548881-04d91294cded5a50?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
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
![windows](https://upload-images.jianshu.io/upload_images/4548881-f8db84f0a7d048f0?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
__macos__
![mac](https://upload-images.jianshu.io/upload_images/4548881-b636a6dc42cc2d6c?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
###### 数位笔设置展示
* 支持笔尖感应设置,笔压设置.
* 数位板快捷键设置, 特殊快捷键设置.切换屏幕.切换笔刷等功能
* 多种绘图模式
__windows__
![windows](https://upload-images.jianshu.io/upload_images/4548881-fad90f5d5ff26ae3?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![windows](https://upload-images.jianshu.io/upload_images/4548881-5089f50005660565?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
__macos__
![macos](https://upload-images.jianshu.io/upload_images/4548881-8c2f83d9f78f946b?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![macos](https://upload-images.jianshu.io/upload_images/4548881-331ec05ed76cc6e7?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
##### 快捷键界面展示
* 支持快捷键实时显示
* 多种组合键设置
* 特殊快捷键设置.切换屏幕.切换笔刷等功能



__windows__
![windows](https://upload-images.jianshu.io/upload_images/4548881-2df31618f7136036?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![windows](https://upload-images.jianshu.io/upload_images/4548881-faa830a014b4132f?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![windows](https://upload-images.jianshu.io/upload_images/4548881-7b1872d8172bc829.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
__macos__
![mac](https://upload-images.jianshu.io/upload_images/4548881-b3798ef4488f0bf4?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)![macos](https://upload-images.jianshu.io/upload_images/4548881-126addf45d3be9f5?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
