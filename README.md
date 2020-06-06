首发在张大妈，想着还是放到GitHub好维护点，就直接copy过来了，先这样吧。

## 主机参数

-  电脑型号       联想 ThinkCentre M910q 
-  处理器        英特尔 I7-8700T ES @ 1.60GHz 六核
-  主板         联想 310B ( Q270 芯片组 )
-  显卡         英特尔 UHD Graphics 630 ( 128 MB / 联想 )
-  内存         16 GB ( 枭鲸 DDR4 2666MHz )
-  主硬盘        KIOXIA-EXCERIA SSD 500G
-  声卡         瑞昱  @ 英特尔 High Definition Audio 控制器
-  网卡         英特尔 Ethernet Connection  I219-LM / 联想

## 黑果展示

- 引导：opencore 0.5.8 ，目录结构如下，删除了一些没用或者冲突的文件，非常精简。

[![联想M910Q 黑苹果折腾系列① 成果展示 opencore EFI分享](https://qnam.smzdm.com/202006/05/5ed9c7825a8196234.png_e680.jpg)](https://post.smzdm.com/p/a78zgzko/pic_2/)

- CPU：变频正常，日常使用40多摄氏度，风扇应该是900多转，非常安静。

[![联想M910Q 黑苹果折腾系列① 成果展示 opencore EFI分享](https://qnam.smzdm.com/202006/05/5ed9c844b5cad32.png_e680.jpg)](https://post.smzdm.com/p/a78zgzko/pic_3/)

- iGPU：驱动正常，显存2048M,VGA输出1080P 60Mhz（祖传显示器，没有DP口，所以DP没测试）

[![联想M910Q 黑苹果折腾系列① 成果展示 opencore EFI分享](https://qnam.smzdm.com/202006/05/5ed9c94ea0d866035.png_e680.jpg)](https://post.smzdm.com/p/a78zgzko/pic_4/)

-    WIFI 蓝牙：拆机94360cs2，无压力

[![联想M910Q 黑苹果折腾系列① 成果展示 opencore EFI分享](https://qnam.smzdm.com/202006/05/5ed9ca2e4c9a83586.png_e680.jpg)](https://post.smzdm.com/p/a78zgzko/pic_5/)

[![联想M910Q 黑苹果折腾系列① 成果展示 opencore EFI分享](https://qnam.smzdm.com/202006/05/5ed9ca3847dd83231.png_e680.jpg)](https://post.smzdm.com/p/a78zgzko/pic_6/)

- AirDrop：正常

[![联想M910Q 黑苹果折腾系列① 成果展示 opencore EFI分享](https://qnam.smzdm.com/202006/05/5ed9cae62ba2a4571.png_e680.jpg)](https://post.smzdm.com/p/a78zgzko/pic_7/)

- 声卡：注入ID 12，内置喇叭正常，3.5输出正常，蓝牙音响正常

[![联想M910Q 黑苹果折腾系列① 成果展示 opencore EFI分享](https://qnam.smzdm.com/202006/05/5ed9cb728f2db157.png_e680.jpg)](https://post.smzdm.com/p/a78zgzko/pic_8/)

- 有线网卡：正常

[![联想M910Q 黑苹果折腾系列① 成果展示 opencore EFI分享](https://qnam.smzdm.com/202006/05/5ed9cbe1c87c78165.png_e680.jpg)](https://post.smzdm.com/p/a78zgzko/pic_9/)

- USB：重新定制，3.0接口5G速率正常，电流正常。

[![联想M910Q 黑苹果折腾系列① 成果展示 opencore EFI分享](https://qnam.smzdm.com/202006/05/5ed9cc77181689115.png_e680.jpg)](https://post.smzdm.com/p/a78zgzko/pic_10/)

[![联想M910Q 黑苹果折腾系列① 成果展示 opencore EFI分享](https://qnam.smzdm.com/202006/05/5ed9ccece9c855303.png_e680.jpg)](https://post.smzdm.com/p/a78zgzko/pic_11/)

- TRIM：正常

[![联想M910Q 黑苹果折腾系列① 成果展示 opencore EFI分享](https://qnam.smzdm.com/202006/05/5ed9cd3e645564211.png_e680.jpg)](https://post.smzdm.com/p/a78zgzko/pic_12/)

- 亮度 声音调节：正常
  


[![联想M910Q 黑苹果折腾系列① 成果展示 opencore EFI分享](https://qnam.smzdm.com/202006/05/5ed9ce53345441781.png_e680.jpg)](https://post.smzdm.com/p/a78zgzko/pic_13/)

[![联想M910Q 黑苹果折腾系列① 成果展示 opencore EFI分享](https://qnam.smzdm.com/202006/05/5ed9ce5a52c6d5884.png_e680.jpg)](https://post.smzdm.com/p/a78zgzko/pic_14/)

声音我双飞燕的无线键盘 FN+F2/F3原生支持调节。亮度下载了一个[MonitorControl](https://github.com/MonitorControl/MonitorControl) 按scroll lock/pause break调节

- **睡眠：异常** 



[![联想M910Q 黑苹果折腾系列① 成果展示 opencore EFI分享](https://qnam.smzdm.com/202006/05/5ed9cf58bb4d71069.png_e680.jpg)](https://post.smzdm.com/p/a78zgzko/pic_15/)

睡眠问题有点难搞，[黑果小兵有一台M710Q](https://github.com/daliansky/Lenovo-M710Q-Hackintosh)，也是睡眠没折腾好。现在直接关掉自动睡眠，BIOS开启键盘开机，ALT+P直接开机很方便。

## 使用感受 

###     除了睡眠其他都完美了，日常使用15W左右功耗，不关机压力不大，晚上直接关机早上键盘开机也很方便，基本上不会折腾了就这样用，如果有搞定睡眠请大力PM我。