### 如何解决Chrome浏览器 "喔唷 崩溃啦" (Aw Snap)问题？
![](http://ww1.sinaimg.cn/large/006XqkXegy1frracm7fmvj30e506eaa0.jpg)<br/>
>  Chrome浏览器打开不了任何网页，包括Chrome：//Setting（设置）页面也无法打开，打开后就会出现"喔唷 崩溃啦"(Aw Snap)的错误。

#### 1.确认Chrome没有运行在兼容模式<br/>
找到Chrome浏览器的快捷方式，选中该快捷方式，按下鼠标右键，在弹出菜单中选择"属性"，在弹出的属性对话框中选择"兼容性"页签，确认"以兼容模式运行这个程序"没有选择<br/>
![](http://ww1.sinaimg.cn/large/006XqkXegy1frraecurtzj30af0dbjsg.jpg)
#### 2.可能和百度安全卫士驱动冲突<br/>
检查C:\Windows\System32\drives目录下面是否有下列文件，如果有，则移到其它地方删除或者用360强力删除：bd0001.sys、bd0002.sys、bd0003.sys、bd0004.sys、bdXXX.sys(以bd开头的扩展名为.sys的所有驱动文件)。<br/>
