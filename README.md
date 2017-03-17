# hfut-autologin
--------------------------
合肥工业大学 校园网自动登陆脚本

## 实现功能
* 开机直接运行bat脚本(windows)或者shell脚本(linux)实现自动登陆校园网，省的打开浏览器再登陆。

## 使用方法
* 下载本代码
* 如果是windows系统：
	* 将本文件目录下，windows目录下的curl.exe(64位的，32位的自己去[官网](https://curl.haxx.se/download.html)下吧)复制到```C:\Windows\System32```目录下。
	* 将```login.bat```复制到```C:\ProgramData\Microsoft\Windows\Start Menu\Programs\StartUp```目录下(实现开机启动这个bat文件)。
	* OK，下次开机就会自动登陆校园网了。
* 如果是Linux系统：
	* 将linux目录下的```login.sh```加入到开机启动项，方法自己百度吧。

## 说明
只是为了方便合工大的学生，当然如果有些学校也是采用这种方式进行上网验证的，可以自己适当改一改参数,说不定也能实现自动登陆校园网。