# change_TKL
change_hexo_TKL是我个人对SuperKieran的TKL做的修改。
原TKL链接如下：https://github.com/SuperKieran/TKL
同时，change_hexo_TKL是Hexo的一个主题。
个人主页效果预览：www.changewade.live

目前，已做更改如下：
```
01、修改大标题<code>title</code>为：YOU CAN DO ALL THINGS, WELCOME.
02、修改<code>content</code>为：每个清晨你都必须醒来，坐上地铁，路过他们的世界，人来人往，去属于你自己的地方。
03、改变<code>content</code>字体大小及位置。
04、修改背景图片<code>bg_img</code>。
05、修改<code>bottom_saying</code>。
06、删除顶栏及底栏，<code>gitHub，twitter，facebook，google，weibo</code>图标。
07、修改侧边栏menu中<code>HOME、ARCHIVES、WORKS、LINKS</code>字间距。
08、移除侧边栏menu中<code>ABOUT、RSS</code>。
09、加大<code>HOME、ARCHIVES、WORKS、LINKS</code>及子标题缩进动画效果。
10、修改<code>WORKS</code>下子标题为其他常用网站。
11、修改<code>LINKS</code>下子标题为博客内容标签。
12、加大<code>WORKS、LINKS</code>下子标题缩进距离。
13、修改底栏<code>2017-2017，Content By Changewade. All Rights Reserved</code>。
14、修改<code>Read More</code>标签线框大小。
15、修改文章底部左右跳转标签线框大小。
16、修改了时间线。隐藏网址get：http://localhost:4000/archive/
／********************未完待续********************／
```
安装主题：
1、利用cd命令进入<code>hexo/themes/ </code>目录下。

2、克隆主题：
```
$ git clone git@github.com:changewade/change_hexo_TKL.git
```
3、打开hexo录了下<code>_config.yml</code>文件。

4、找到如下内容：
```
# Extensions
## Plugins: https://hexo.io/plugins/
## Themes: https://hexo.io/themes/
theme: 
```
5、将theme: 后内容改为<code>change_hexo_TKL</code>。

注意，冒号后有一个空格。冒号应为英文输入。

theme: 后主题名称与<code>/hexo/themes/ </code>克隆主题文件夹名一致即可。

