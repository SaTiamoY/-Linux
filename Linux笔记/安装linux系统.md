# 旧笔记本安装linux系统[B站指导视频](https://www.bilibili.com/video/BV1hL411r7p2/?spm_id_from=333.337.search-card.all.click&vd_source=51464752742948750380d6832ffd9b50)

## linux系统选择

选择CentOS-7系统 系统镜像放在阿里云盘镜像文件夹中

## 刻录工具

使用YUMI刻录工具，工具也在阿里云盘上备份

工具操作比较傻瓜式的

## 系统的安装

### 笔记本电脑U盘启动

#### 通BIOS界面设置U盘启动

1. ThinkPad笔记本通过F1进入BIOS界面

2. 在BIOS界面选择 <font color="red">**Security**</font> 菜单

3. 在选择<font color="red">**Secure Boot**</font>选项

4. 在<font color="red">**Secure Boot**</font>中，将“<font color="red">**Secure Boot**</font>”选项设置为“<font color="red">**Disabled**</font>”

5. 然后再选择<font color="red">**Startup**</font>栏目

6. 在<font color="red">**Startup**</font>栏目中，找到“UEFI/Legacy Boot”选项，设置为“Legacy Only”，并将“CSM Support”设置为“YES”，然后找到“Boot”，回车进入

7. 在Boot页面中，将带有<font color="red">**USB HDD**</font>字样的选项，通过键盘上的“上下方向键”和“+号-号”调整到第一的位置，然后按“F10”保存BIOS设置，直接重启电脑即可U盘启动，随后就可进入快启动U盘启动中

   #### 不通BIOS界面U盘启动

   在window系统开始菜单中选择恢复选项，选择U盘启动

   ### linux系统安装

   1. 进入U盘进入下一步就能进行系统安装



