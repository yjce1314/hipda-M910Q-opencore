## 主机参数

- 电脑型号 联想 ThinkCentre M910q
- 处理器 英特尔 I7-8700T ES @ 1.60GHz 六核
- 主板 联想 310B ( Q270 芯片组 )
- 显卡 英特尔 UHD Graphics 630 ( 128 MB / 联想 )
- 内存 16 GB ( 枭鲸 DDR4 2666MHz )
- 主硬盘 KIOXIA-EXCERIA SSD 500G
- 声卡 瑞昱 @ 英特尔 High Definition Audio 控制器
- 网卡 英特尔 Ethernet Connection I219-LM / 联想

## EFI文件

- 引导：opencore 0.5.8 ，目录结构如下，删除了一些没用或者冲突的文件，非常精简。

![img](https://p26-tt.byteimg.com/large/pgc-image/68675dca66a645e585b4cf0b29c16bf0)

- CPU：变频正常，日常使用40多摄氏度，风扇应该是900多转，非常安静。

![img](https://p29-tt.byteimg.com/large/pgc-image/5df476ff1e1445e3b62d4d965c7c3bcc)

- iGPU：驱动正常，显存2048M,VGA输出1080P 60Mhz（祖传显示器，没有DP口，所以DP没测试）

![img](https://p9-tt.byteimg.com/large/pgc-image/df6bcde4860442acb382b16cde0c1c01)

- WIFI 蓝牙：拆机94360cs2，无压力

![img](https://p26-tt.byteimg.com/large/pgc-image/d18c0369a12c4bc385777455520c0291)

![img](https://p1-tt.byteimg.com/large/pgc-image/29d18aa207ea4962aab8e13d1579f66f)

- AirDrop：正常

![img](https://p6-tt.byteimg.com/large/pgc-image/cfe428197b6541a4a08cb635b9620c7a)

- 声卡：注入ID 12，内置喇叭正常，3.5输出正常，蓝牙音响正常

![img](https://p29-tt.byteimg.com/large/pgc-image/07bbe0c092a34956a32e530c5f048d86)

- 有线网卡：正常

![img](https://p6-tt.byteimg.com/large/pgc-image/a5d077e1b050436fa205cf3a7cfcb925)

- USB：重新定制，3.0接口5G速率正常，电流正常。

![img](https://p9-tt.byteimg.com/large/pgc-image/15f614c6fec7483380b1840ccc0aaef2)

![img](https://p9-tt.byteimg.com/large/pgc-image/7fc266d76fd64f4a871eedc6724faf2b)

- TRIM：正常

![img](https://p1-tt.byteimg.com/large/pgc-image/6e0daa707b1344069534586baf5ca3cd)

- 亮度 声音调节：正常

![img](https://p9-tt.byteimg.com/large/pgc-image/cee846cadb0b403f97048a587b390634)

![img](https://p6-tt.byteimg.com/large/pgc-image/39a77461c138456489b5f6f72a08e6bf)

声音我双飞燕的无线键盘 FN+F2/F3原生支持调节。亮度下载了一个MonitorControl 按scroll lock/pause break调节

- **睡眠：异常**

![img](https://p26-tt.byteimg.com/large/pgc-image/482a7aeaa8554e5e81ccbbc5d5d3b668)

睡眠问题有点难搞，黑果小兵有一台M710Q，也是睡眠没折腾好。现在直接关掉自动睡眠，BIOS开启键盘开机，ALT+P直接开机很方便。