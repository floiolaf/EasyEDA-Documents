
# 演示视频

<iframe frameborder="0" width="906" height="610" src="https://v.qq.com/iframe/player.html?vid=r05228zg4fw&tiny=0&auto=0" allowfullscreen></iframe>

# 文件下载

**帮助文档和本地自动布线下载**

最新版帮助文档PDF支持书签导航。  
下载地址1(百度网盘)：[立创EDA帮助文档.pdf & EasyEDA Router.7z](https://pan.baidu.com/s/1eRT18kE#list/path=%2F)  
下载地址2(Google Drive)：[立创EDA帮助文档.pdf & EasyEDA Router.7z](https://drive.google.com/drive/folders/0BwqCaNlgtS3UZkM3UFZqVkRqNHM)  
下载地址3(GitHub)：[立创EDA帮助文档.pdf & EasyEDA Router.7z](https://github.com/dillonHe/EasyEDA-Documents/tree/master/Tutorial/Doc)  

**客户端下载：**

由于立创EDA的更新迭代非常快速，客户端不适合每周甚至每天更新，很多新功能的开发与发布已经受制于客户端，所以我们决定暂时停止客户端的下载与开发（最慢一年内再次提供），请各位用户将未同步到服务器的数据同步至服务器，或者下载到本地硬盘，并暂时使用网页版开发。  
同时立创EDA很快会提供私有化部署，用户可在自己局域网部署一个类似立创EDA的服务，完全脱离外网。  
有问题请联系技术支持QQ3001956291<a target="_blank" href="http://wpa.qq.com/msgrd?v=3&uin=3001956291&site=qq&menu=yes"><img border="0" src="http://wpa.qq.com/pa?p=2:3001956291:51" alt="点击这里给我发消息" title="点击这里给我发消息"/></a>。

2017.09.30


# 更新说明


**v4.11.9更新说明**

2017.11.22： 

-	改善：

	-	修复铺铜无间隙问题
	-	修复仿真无法运行问题
	
	
**v4.11.5更新说明**

2017.11.17： 

-	改善：

	-	修复PCB工具里的连接焊盘功能
	-	改善复制粘贴焊盘编号序号问题
	-	修复封装管理器对有相同焊盘编号的封装会报红问题
	-	修复自动布线时，导线换层时出现重复焊盘与过孔的问题
	-	优化多层焊盘切换至单层问题
	-	焊盘内量测无信息弹出问题
	-	兼容旧PCB的网络更新问题
	-	系统库加入了全新的KiCAD原理图库和PCB库
	-	修复无法标注无数字编号的bug
	-	修复了某种特殊情况下铺铜无间隙的bug
	-	修复移动封装飞线残留问题
	-	改善了关闭吸附后导线无法连接元件引脚问题
	-	改善了过孔与多层焊盘内孔直径设置问题
	-	去除快捷键G关闭吸附的功能，避免误按导致原理图电气连接丢失。
	-	去除无效快捷键ctrl+shift+v
	-	修复无焊盘封装导入偏移太远的问题

**v4.10.3更新说明**

2017.10.20： 

-	改善：

	-	改善大量走线的删除效率。以前删除1000+走线需要几分钟，现在只要几秒即可完成。
	-	修复飞线在完成布线后没有消失的问题。
	-	修复删除铺铜后铜箔没有消失的问题。


**v4.10.2更新说明**

2017.10.17：  

-	改善：

	-	修复网络标签不连接问题

	
**v4.10.1更新说明**

2017.10.16：

-	新功能：
	-	新的“帮助”菜单。
	-	新增[布局传递](https://lceda.cn/Doc/Tutorial/Schematic.htm#布局传递)功能, 快捷键 “ctrl + shift + X”
	![](./images/295_Schematic_CrossProbeAndPlace1.gif)
	-	新增本地自动布线支持Linux (64位)
	
-	改善：

	-	优化网络名按时间顺序排序
	-	优化多网络标签显示  
	*在以前的版本，当放置一个零件在导线上，其网络名称会改变，并且更新至PCB后会导致网络名与走线变更，从这个版本开始，我们已经解决这个问题，但若更新至PCB则，无法保持原有的PCB网络与走线，所以如果你需要保留之前的PCB布局，你只能使用`转为PCB`而不是`更新PCB`。*
	-	优化原理图绘制的卡顿感
	-	修复封装名空格导致更新封装失败问题
	-	修复右键取消复制粘贴的bug
	-	修复PIN脚改长度导致旋转角度错误的bug
	-	修复文字对齐问题导致移动电路导线断开连接的bug
	-	优化火狐缩放体验，改善缩放卡顿感
	-	修复网络名称的特殊字符与空格导致自动布线失败的bug
	-	修复圆弧铺铜出现非圆润毛刺问题
	-	优化BOM导出按钮
	-	优化导出坐标文件单位跟随画布单位，支持mm单位。
	

**v4.9.3更新说明**

-	**本地自动布线**

	-	由于使用服务器进行自动布线，当使用人数较多时，需进行排队，并出现服务器繁忙的情况，为了解决这一问题所以我们特意开发了本地自动布线插件，请大家优先使用本地自动布线，功能与服务器自动布线一致。  
![](./images/288_PCB_LocalAutoRouter_Dialog.png)
插件下载地址：[EasyEDA Router.zip](https://lceda.cn/EasyEDA-Router.zip)  
使用前，浏览器需要进行相应的配置，具体信息请查看：[https://lceda.cn/Doc/Tutorial/PCB.htm#本地自动布线](https://lceda.cn/Doc/Tutorial/PCB.htm#本地自动布线)

-	**支持AD格式文件导出**

	-	如同之前承诺，AD格式文件导出功能已经发布。   
**注意：***由于是初版导出功能，可能会有我们还没有发现的问题，AD打开后请注意检查。*
 ![](images/289_Export_SchematicInAltium.png)  
具体信息请查看：  
[https://lceda.cn/Doc/Tutorial/Export.htm#用Altium-Designer格式导出原理图](https://lceda.cn/Doc/Tutorial/Export.htm#用Altium-Designer格式导出原理图)  
[https://lceda.cn/Doc/Tutorial/Export.htm#用Altium-Designer格式导出PCB](https://lceda.cn/Doc/Tutorial/Export.htm#用Altium-Designer格式导出PCB)

 
**v4.8.5更新说明**

-	**封装管理器功能增强**

	-	1、打开封装管理器后，它会自动检查你零件的封装是否存在，是否正确。如果零件没有指定封装，或封装不在个人库和系统库中，或零件引脚编号与封装焊盘编号无法正常对应时， 封装管理器会在零件名前出现错误图标，并使零件名标红。例如：你的零件U1有两个引脚，编号分别是1、2，名称分别是VCC和GND；但是你用的封装的焊盘编号是A、B，所以左边列表会报错标红，要修正错误要么你将1、2改成A、B，要么将封装的焊盘编号A、B改成1、2；要么更换封装。  
	**注意：** *如果你的原理图使用了数量较多的不同名称的封装，封装管理器在检测封装焊盘编号与元件引脚编号的对应关系时，会与服务器进行封装数据查找和对比，这将花费一定时间，请耐心等待。*   

	-	2、在零件和封装的预览窗口，你可以用鼠标拖动，放大缩小预览图。 
![](images/281_Schematic_FootprintManagerEnhance.png)

-	**新增立创贴片零件库**

	-	我们新增了一个立创可贴片零件库，这个库属于立创商城库的子集，可方便使用立创贴片服务的用户选料，里面包含了690种零件，数量在不断增加中。预计今年年底就可以提供更多的种类元件的贴片服务，敬请期待。
![](images/282_Schematic_Parts_AssemblyComponents.png)

-	**文件标签切换**

	-	已经可以进行标签切换。   
![](images/279_Introduction_EditorTabSwitch.gif)

-	**量角器**

	-	加了一个新功能，量角器。  
![](images/280_PCB_PCBTools_Protractor.gif)



**v4.6.4更新说明**


2017.06.28:
-	**新封装管理器**

	-	在这个版本我们提供了一个新功能，封装管理器。它支持批量修改封装。更多介绍请参考：[封装管理器](./Schematic.htm#封装管理器)
![](images/264_Schematic_FootprintManager.png)
![](images/267_Schematic_FootprintManagerUI.png)


-	**新的画圆工具**

	-	该工具先确定圆心再确定半径进行画圆。
![](./images/269_PCB_Arc_Center.gif)

-	**全局删除**

	-	你可以很容易进行不同种类元素的全部删除。
![](./images/272_Introduction_Skill_GlobalDelete.png)

-	**零件移动走线跟随**

	-	当移动零件时，连接的走线可垂直或平行跟随移动。
![](images/273_Schematic_WireAndComponentMove.gif)

-	**BOM表导出图标**  
![](images/273_Export_BOM_Icon.png)

	-	在BOM表导出窗口，你可以给相应零件分配一个立创商城的产品编号，以利于在立创商城购买零件。
![](images/085_Export_BOM_Assign.png)

	-	点击分配图标后会弹出元器件库搜索界面，选择你所需要的零件，点击右下角的分配按钮即可。
![](images/274_Export_BOM_Assigned.png)


-	**更多对齐功能**

	-	我们提供了更多对齐功能，具体可以自己体验一下。
![](images/275_Introduction_Align.png)


-	**导入功能增强**

	-     新的AD文件导入  
AD文件导入更快了，效果更好，同时支持30M以内的大文件。需要注意的是，AD文件必须另存为ASCII格式才可以被导入。
	-     更好的DXF导入     
 对DXF导入的功能改善，比以前优化了导入速度和生成质量。

