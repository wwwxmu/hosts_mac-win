# hosts

> [hosts来源于laod.cn | 更新于:2017-02-09]

### 如何下载
`git clone https://github.com/wwwxmu/hosts_linux.git`

### hosts所在文件夹：
Android（安卓）系统hosts位于 /etc/hosts
Linux系统hosts位于 /etc/hosts
绝大多数Unix系统都是在 /etc/hosts

### 修改hosts后生效的方法：

1 Linux
终端输入
`sudo rcnscd restart`
对于systemd发行版，请使用命令
`sudo systemctl restart NetworkManager`
如果不懂请都尝试下

2 Android
开启飞行模式 -> 关闭飞行模式

3 通用方法
拔网线(断网) -> 插网线(重新连接网络)
(有时候不需要这么做也可以的，反正老D很少刷新DNS，刷新可以更快的解析)

### 注意
Google、Gmail、维基百科、Twitter、Facebook等必须请用https加密方式打开。
一般这些网站都是SSL加密链接，如：

谷歌学术：https://scholar.google.com/

谷歌：https://www.google.com/ncr

谷歌香港：https://www.google.com.hk/ncr

Twitter：https://twitter.com/?lang=zh-cn

另外可能有的地区&网络（铁通、联通）hosts无法正常使用，这个不是你我能左右的！
建议不要使用国产浏览器，国产软件也是，特别是360，因为国产浏览器即使你使用https
它也会强制你使用默认http，还有就是会上传用户数据，尽可能使用Chrome
下载&修改hosts安全软件可能会“报毒”（误报）你可以暂时退出或者添加信任即可！

> 本hosts仅限于学习使用！
