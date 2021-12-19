当我看到“WPS Office”在我的电脑中写入了上万条注册表项时，我几乎要崩溃了。这个……有点太多了吧。
___
# 软件绿化工具
**环境**
[Workstation 15.5 Player for Windows](https://www.vmware.com/go/getplayer-win)
**绿化软件**
[VMware ThinApp](https://download.csdn.net/download/weixin_47513791/12394582)
___
# 软件绿化过程
 1. 首先安装`VMware Workstation 15.5 Player for Windows`。
 2. 为了更好更方便的绿化软件，我们需要下载Windows10虚拟系统映像。
（[**官方地址**](https://az792536.vo.msecnd.net/vms/VMBuild_20190311/VMware/MSEdge/MSEdge.Win10.VMware.zip)）
3. 安装镜像至虚拟机，详细教程见：[教程](https://blog.csdn.net/unfound/article/details/81220744)，只不过需选择“安装程序光盘映像文件(iso)(M)：”。
4. 虚拟机内不要安装杀软（360、火绒、Kaspersky、金山毒霸等任何计算机杀毒管理软件，最好禁掉Windows Defender，所有警告全部放行。
5. 将`VMware ThinApp`下载至虚拟系统，以下所有操作均在虚拟机内进行。
6. 运行`VMware ThinApp`，下一步。![界面](https://img-blog.csdnimg.cn/20200510193931192.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80NzUxMzc5MQ==,size_16,color_FFFFFF,t_70#pic_center)
7. 预扫描，如果警告：有应用欲修改开机启动项，请给予放行。![预扫描](https://img-blog.csdnimg.cn/20200511105906735.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80NzUxMzc5MQ==,size_16,color_FFFFFF,t_70#pic_center)
8. 安装软件，不要更改安装位置！![安装](https://img-blog.csdnimg.cn/20200511110000127.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80NzUxMzc5MQ==,size_16,color_FFFFFF,t_70#pic_center)
9. 后期扫描。![后期扫描](https://img-blog.csdnimg.cn/20200511110021188.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80NzUxMzc5MQ==,size_16,color_FFFFFF,t_70#pic_center)
10. 入口点：即主程序，如“setup_capture.exe”就是“VMware ThinApp”的主程序。![入口点](https://img-blog.csdnimg.cn/20200511110045302.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80NzUxMzc5MQ==,size_16,color_FFFFFF,t_70#pic_center)
11. 警告不用管。![警告](https://img-blog.csdnimg.cn/20200511110128697.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80NzUxMzc5MQ==,size_16,color_FFFFFF,t_70#pic_center)
12. ![准备创建](https://img-blog.csdnimg.cn/20200511110616125.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80NzUxMzc5MQ==,size_16,color_FFFFFF,t_70#pic_center)
13. 完成。

至此，绿软制作完成。
绿软路径：`%drive_C%\Program Files`

文件夹中的“*.bat”不要管，三个文本文档是注册表修改的项，通过文本文档可以看出这个软件到底写了多少注册项。
然后，重装系统，准备下一次的绿化。
___
# 视频
[链接](https://pan.baidu.com/s/1ATWtN0UxvQgZLUeW8d2pMA)
csdn
作者原创，此视频无版权。
___
# 绿软快捷方式
[工具链接1（不确定有效）](https://download.csdn.net/download/weixin_47513791/12396646)
[工具链接2（不确定有效）](https://www.lanzous.com/iccikwj)![在这里插入图片描述](https://img-blog.csdnimg.cn/20200511132712618.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80NzUxMzc5MQ==,size_16,color_FFFFFF,t_70#pic_center)
### 制作过程
1. 下载工具，工具链接1或工具链接2为同一文件。
2. 选择生成的启动软件。
3. 输入主程序相对于启动软件的相对路径。
4. 生成。
5. 测试，一般可以跨设备使用。
### 注意
如果选择了绝对路径，那就是绝对的绝对路径。（Windows快捷方式指向文件只要存在，就能找到，改名也可以。）
___
___

# 写在最后
> ###### 绿色软件的缺点
> 1. 有的不稳定，会有许多的错误。
> 2. 免安装，当然也就不会写入注册表，这样卸载时就方便了。但同时不会关联相关的文件，比如我绿化过WPS Photo + v2019，硬盘里的图片不能直接用它打开，就算是修改了打开方式也不行。必须先打开WPS Photo + v2019绿色版，再从里面打开图片。
> 3. 单文件的绿软可能会报毒。
> 4. 无法保存软件配置，每次都要修改。
> 5. 多多少少会有些不方便，比如7-zip，右键菜单都不会出现。
> 6. 需注册激活的软件每次打开都要输入激活码/密钥/注册码/注册信息。
> 7. 携带版的便携是牺牲功能性（诸如系统集成）和清理能力（便携版导入的临时文件往往不会被清除）换来的。
> 8. 安装式软件在安装后会保留安装日志，在使用卸载程序的时候反而可以比较干净的将非安装目录文件清理掉，大部分软件的卸载程序一般会清理使用中添加的注册表和非安装目录的附加文件，比如随着windows权限安全的不断完善，一般侧重安全的非独立用户安装的程序，会在使用者的"ProgramData""AppData"等目录下释放程序的主要组件，很多安全性要求高的软件甚至直接默认安装到“AppData”目录（如chrome等），再比如很多在系统注册的动态链接库会在卸载时询问你是否还需要，等等。这些都让你可以安全和稳定的使用程序，并且在不需要之后，较为干净的清除他，而那些所谓的“绿色软件”，其实只是满足了那些什么都不懂的一些用户对于干净清洁的心理需求而已。另外，如果是MSI包安装的软件，更不需要绿色化，MSI的安装卸载日志严格，卸载后会非常干净，注册项与原来完全相同。这是windows的包管理机制决定的，更没必要去追求什么绿色版了。
> 9. 绿色软件更容易受到污染，但由于一些用户缺乏相关知识，只能看到事物的表面，不愿意寻找官方渠道。很多开源工具，官方明明提供了非常细致的编译后版本和各国翻译者贡献的语言包，却还有一些用户在贴吧和知道里求汉化版，非常的匪夷所思。大部分时候，这些用户寻找软件时，习惯在百度中随便搜索，然后去下一些软件下载站提供的软件，这些软件不是被重新打包，添加了各中附加的推广应用，就是被人为挂了马污染过，推广应用有些通过隐蔽的在多处提供选项，让你漏选，有些则直接默认安装不告知。一些很有“名气”的下载站现在基本都靠这个做法盈利。
> 10. 有些用户容易简单的将不用安装理解为干净绿色，甚至连系统安装盘这么重要和底层的东西，也追求民间的修改版本，事实上微软官方的MSDN提供了所有微软产品的官方镜像，国内也有非常著名的整理站点如itellyou等，可以找到所有微软产品的原版镜像官方下载链接，大不了用KMS激活。但是大部分用户还是更偏爱诸如番茄花园、深度、老毛桃等修改版本。要知道目前在修改版系统中安插木马、预留后门、修改主页、安置推广链接和页面，甚至偷偷挖矿等流氓行为，早已成为这类“民间制作版”软件的主要盈利模式，很多民间制作的系统安装盘维护盘都修改了大量系统设置，隐蔽的安插了各种广告插件或预装以此牟利。
> 11. 一些用户下载绿软后总是经常出现诸如使用一段时间后，被莫名篡改浏览器首页、莫名弹窗、系统莫名变卡，莫名被安装奇怪插件等问题，这类问题刺激用户寻求更激进的使用策略，比如养成了极端追求主观上“干净”的软件，极端追求系统的“整洁”的偏好，甚至精简清除自己认为无用的系统组件、关闭系统更新以及不愿意安装安全补丁等等行为。但是同时，这类偏好和行为加重了系统的安全问题。由于缺乏真正正确的知识和理解，陷入这种“面临更严重的性能和安全问题”——“追求更激进的使用策略”，“追求更激进的使用策略”——“面临更严重的性能和安全问题”的恶性循环中，把一个在生产环境中文职员工都能安全健康的使用多年的系统用的举步维艰。
> 12. 本引用来自[这里](https://www.zhihu.com/question/26851356)。


