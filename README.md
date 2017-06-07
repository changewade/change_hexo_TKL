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
10、修改<code>WORKS</code>下子标题为博客内容标签。
11、修改<code>LINKS</code>下子标题为其他常用网站。
12、加大<code>WORKS、LINKS</code>下子标题缩进距离。
13、修改底栏<code>2017-2017，Content By Changewade. All Rights Reserved</code>。
14、修改<code>Read More</code>标签线框大小。
15、修改文章底部左右跳转标签线框大小。
16、增加了时间线。http://localhost:4000/timeline/

／********************未完待续********************／
```

## 安装主题：
1、利用cd命令进入<code>hexo/themes/ </code>目录下。

2、克隆主题：
```
$ git clone git@github.com:changewade/change_hexo_TKL.git
```
3、打开hexo录了下<code>_config.yml</code>文件（记事本即可）。

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


## 其他操作：
#### 1、新建日志：

终端进入hexo目录下使用如下命令：
```
$ hexo new "title"
```
注：title更改为你新日志标题，支持中文

新日志存储在<code>/hexo/source/_posts/</code>中

#### 2、添加标签：

打开<code>/hexo/source/_posts/title／</code>，修改内容如下：
```
---
title: title
tags: 
---

###此处键入文章内容###
```
在<code>tags: </code>后键入标签名称

注意：

* <code>title: </code>后内容与文件名一致

* 冒号后均有一空格

#### 3、修改<code>WORKS</code>下子标题为博客内容标签。

打开<code>/change_hexo_TKL/themes/_config.yml</code>文件（记事本即可）。

找到如下内容：
```
#Works
works: 
- works_name: timeline
works_url: http://www.changewade.live/timeline/
- works_name: 博客入门
works_url: http://www.changewade.live/tags/博客入门/
- works_name: 书与影
works_url: http://www.changewade.live/tags/书与影/
- works_name: 趣知识
works_url: http://www.changewade.live/tags/趣知识/
- works_name: 文章
works_url: http://www.changewade.live/tags/文章/
```
将<code>timeline、博客入门、书与影、趣知识、文章</code>修改为自己的<code>标签</code>名称即可。

#### 4、修改<code>LINKS</code>下网页链接。
打开<code>/change_hexo_TKL/themes/_config.yml</code>文件（记事本即可）。

找到如下内容：
```
#Links
links:
- name: Bing
link: https://www.bing.com/
- name: Google
link: https://www.google.com/
- name: Github
……
```
自行修改即可。

#### 5、如何不显示<code>WORKS、LINKS</code>
只需要将<code>#works</code>下<code>works</code>删除一个字母即可。<code>Links</code>同理。

#### 6、timeline内容修改。
打开<code>/change_hexo_TKL/themes/_config.yml</code>文件（记事本即可）。

找到如下内容：
```
#about  timeline
timeline:
- num: 1
word: 2017/05/19-Start
- num: 2
word: 2017/06/03-简介
- num: 3
word: 2017/06/03-博客内容书写基础知识
- num: 4
word: 2017/06/03-草稿与主题
- num: 5
word: 2017/06/03-书影短评
- num: 6
word: 2017/06/03-书单与影单
- num: 7
word: 2017/06/05-趣知识一
- num: 8
word: More
```
自行修改即可。


































