# musicnow
移动网页音乐体验，搜索和下载网易云音乐；
快速体验[个人音乐实验室](http://tv.osome.top:16881/)（请使用手机体验）。

#### 一、来源
基于[音乐搜索器 - 多站合一音乐搜索解决方案](https://github.com/maicong/music)

使用go语言制作，目前只做了网易云音乐的接口，可以直接下载应用程序，部署到服务器，不用安装go编译器。
#### 二、特点
1. go语言编写，可以部署安装包
2. 动态获取数据，交互基本在客户端
3. 手机网页友好，可在线试听

#### 三、部署
##### linux服务器
架构为linux、amd64：
1. 下载music_linux.zip压缩包，解压；
2. 进入相应文件夹，chmod +x music，也就是给该文件赋予可执行权限，如果原生满足，则到下一步；
3. 修改conf文件下app.conf文件的监听端口和mode，dev会显示日志，改为test或者其它标签即可；
4. 运行程序，./music
其它服务器：使用go编译器自行编译，具体百度或者Google。
##### Windows服务器
架构为Windows、amd64：
1. 下载music_win.zip压缩包，解压；
2. 修改conf文件下app.conf文件的监听端口和mode，dev会显示日志，改为test或者其它标签即可；
3. 运行程序，双击music.exe即可运行
其它服务器：使用go编译器自行编译，具体百度或者Google。

#### 四、计划
1. 支持pc端
2. 支持更多网站

#### 五、其它
个人网站[方圆实验室](http://www.fysys.top/)
