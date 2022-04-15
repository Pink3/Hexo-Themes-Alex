<p align="center" class="mb-2">
<img class="not-gallery-item" height="48" src="https://tangjianpeng.com/css/images/logo.png">
<br> A simple, delicate, and modern theme for the static site generator Hexo.
<br>
<a href="https://tangjianpeng.com/">Preview</a> |
<a href="https://github.com/Pink3/Hexo-Themes-Alex">Documentation</a> |
<a href="https://github.com/Pink3/Hexo-Themes-Alex/discussions">Discuss on GitHub</a>
<br>
</p>

![](https://img.tangjianpeng.com/home.jpg "Alex Preview")

欢迎使用Alex！ Alex是由<a href="https://github.com/ppoffice">ppoffice</a>大神制作的一款静态网站生成器Hexo的简单，精致，而现代的主题。 它力求设计上的优雅，但也不抛弃使用上的简单明了。 它灵活且多功能的配置系统让资深用户也能极尽细节地装饰他们的站点。


在你继续安装Alex之前，请先花些时间阅览Hexo文档。 如要安装Alex，你可以选择如下两种方式中的任意一种：

从GitHub的仓库中下载源码的压缩包并解压到你Hexo站点的主题目录中。 或者，你可以使用Git来克隆Alex的代码仓库到`themes`目录下：
```Git Bash/命令行

git clone https://github.com/Pink3/Hexo-Themes-Alex.git themes/Alex -b <version number> --depth 1
```
你可以省略`-b <version number>`来获取Alex的最新开发版本。 如果你想同时下载Git仓库的完整提交历史，请同时省略`--depth 1`
另外，你也可以使用下面的命令将Alex安装为Git子模块(submodule)：

```Git Bash/命令行

git submodule add https://github.com/ppoffice/hexo-theme-Alex.git themes/Alex
```
接下来，在你的站点的_config.yml文件中的开启Alex：

```_config.yml

theme: Alex
```
或使用hexo命令修改主题为Alex:

```命令行
hexo config theme Alex
```
最后，使用如下命令来启动Hexo本地测试服务器并开始创作。

```命令行
hexo server
```
