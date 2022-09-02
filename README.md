Intel (R) Flash Programming Tool Version: 15.0.1.1347一种基于Intel平台使用FPT刷新BIOS的方法技术的工具
第一种操作方法：双击backup.exe便是备份，双击flash便是写入。 
![image](https://user-images.githubusercontent.com/38132402/188080812-9dcad861-43c3-4874-a662-84c8b0656d53.png)
第二种操作方法：当然也支持传统桥命令。
备份：  ./fptw64 -d b.bin -bios
写入：  ./fptw64 -f b.bin -bios
本发明专利技术提供一种基于Intel平台使用FPT刷新BIOS的方法，采用Intel的FPT工具刷新BIOS。方法步骤如下：

1）、将要刷新的BIOS文件复制到USB Flash，然后将FPT刷新工具复制到 USB Flash；

2）、将要刷新的机器引导进入U盘；

3）、引导进入U盘后，在命令行输入fpt-f XXX.rom，即可自动开始刷新BIOS；

4）、刷新完成后将机器断电后再开机，查看BIOS的版本及Release Date是否有更新。本方法摆脱单一、局限的刷新BIOS的方法，实现多元化，刷新区域更全面。
![image](https://user-images.githubusercontent.com/38132402/188080839-b9ff4656-a446-4fbf-bcb8-63408bfefcb9.png)
