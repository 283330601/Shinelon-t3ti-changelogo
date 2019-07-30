# Shinelon-t3ti-changelogo
替换炫龙T3TI开机画面

针对T3TI，方法理论上可适用于大部分INSYDE BIOS。
固件源文件来源于神舟 (http://kfgl.hasee.com/lookup/bios/index.asp)

1.使用H2OEZE-x64.exe（我用的100.00.03.04版本）打开固件
2.依次打开Function-Components-Logo
3.替换相应图片（最好是分辨率差不多的JPG格式）
4.保存固件文件

5.打开固件刷写文件夹
6.新建一个文本文件，写入如下内容(flash.fd更改为固件文件名)：
      cd /d %~dp0
      fptw64.exe -bios -f flash.fd
7.保存为.BAT格式
8.右键以管理员权限运行BAT
9.等命令行走完后重启计算机，开机会黑屏，不要动，等电源灯自动熄灭后开机
