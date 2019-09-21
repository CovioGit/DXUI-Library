# DXUI-Libaray
### 此库来之不易，使用请标明作者。商业用途请先联系我。
**共同维护良好的开源环境！**<br>
**QQ: 2441987560<br>
WeChat: yangzhen2441987560<br>
Email: 2441987560@qq.com**<br>
**欢迎通过各种方式提出宝贵的意见，每个周末我都会查看，有不懂的也可以找我交流。**<br><br>

一个 **超级简单、动画华丽** 的界面库<br>
取“DXUI”这个名字是因为此界面库使用Direct 2D图形库来绘制，使用Wic库实现加载图片及部分功能，使用DWrite库来绘制处理文字。<br>
基于Direct系列的界面库少之又少，一是实现太过复杂，学习成本太高。二是考虑到硬件兼容的问题。<br>
而Direct 2D完美的解决了这些问题，同时保留了硬件加速的优点，用来做界面库，实现流畅的动画再好不过了。<br><br>
DXUI界面库的优点是：
* 1.控件样式可以90%自定义，并且完善的透明度支持为界面增色不少。<br>
* 2.基于事件驱动的动画，用户无操作时不消耗资源。<br>
* 3.极低的CPU、GPU、内存占用，不用担心办公电脑等低配置环境的运行问题。<br>
* 4.局部刷新技术，背景图再大，上层控件动画也能流畅播放。<br>
* 5.非常简单，开发者只需要考虑如何找到好看的颜色，仅通过几行代码即可添加控件。<br>
* 6.高兼容性，无需考虑硬件支持问题，就算不支持，可无缝切换到软件绘制，效率优于GDI。<br>
* 7.拥有比GDI/GDI+更高的绘图质量，界面更清晰大方。<br>
* 8.完善的高DPI支持，再也不用担心系统缩放模糊的问题。<br><br>
**测试程序全部代码仅有350行(包括基础Win程序框架)，真正的简单、不繁琐。**<br>
预览图：<br>
![main0](https://github.com/IDXGI/DXUI-Libaray/blob/master/preview%20pictures/Main0.jpg)<br>
![main1](https://github.com/IDXGI/DXUI-Libaray/blob/master/preview%20pictures/Main1.jpg)<br><br>
以后有时间会继续添加控件页、列表框、视频框等控件。由于我上学，1周或2周回家一次，更新进度会比较慢。<br><br>

**————————190921 更新内容————————**<br>
1.优化了在客户区拖动窗口的实现方式，新方法没有任何特殊限制。<br>
2.优化ImageBox的加载函数，理论支持图片大小可达系统极限值，且上层控件动画依然流畅。还优化了加载失败后的处理。<br>
3.优化了示例程序的控件参数，使其更自然、流畅。还增加了一些控件，更好地展示此库的简单、美观。更新后示例程序去掉注释和换行，依旧只有350行左右。<br>
**———————————————————————**
