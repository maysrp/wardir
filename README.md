#wardir
整合了webdir于yaaw，可以在在线播放mp4视频，预览PDF等.

需要aria2的首先安装并且配置好。

###配置
密码:
```
define("PASS", "admin");
```
配置显示文件以及文件夹
```
$this->notex=array("php","js","tgz");//不允许显示的后缀名文件
$this->notdir=array("a","phpmyadmin");//不允许显示的文件夹
```
###使用

将整个文件夹中的文件放在你的网站根目录中：

点击 
>详细管理>界面管理.html 

即可进入原有的<a href="https://binux.github.io/yaaw/">Yaaw</a>，可以在上面添加种子,管理之前的下载。
[iframe大法好，惊呼！]
![001](http://git.oschina.net/uploads/images/2016/1223/191116_8b496e8a_700748.png "wardir/")
![002](http://git.oschina.net/uploads/images/2016/1223/191131_b0e23a59_700748.png "wardir/")
![003](http://git.oschina.net/uploads/images/2016/1223/191140_3c93a4ee_700748.png "wardir/")
