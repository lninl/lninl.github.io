# 使用 GitHub Pages 与 Jekyll 组合搭建个人博客


本文旨在记录自己在搭建博客过程中遇到的问题。这是一个足够简洁的、而且功能完备的博客。在这里会有几个关键功能点的实现，你可以将它们整合到你的博客中，增添出相同的功能。可以先[瞧一瞧](https://lninl.github.io/) ^_^ ...

### 内容排版

现阶段只完成了文字的排版工作。在[Jonathan McGlone](http://hankquinlan.github.io)博客的基础上做了修改。

#### 问题一：master 分支与 gh-pages 分支

搭建个人博客所创建的仓库中，master 分支里的文件才会被用来生成 Github Pages 站点，所以**请确保你的文件储存在 master 分支上**。不用在意 gh-pages 分支，这里有[详细的解释](http://jekyllcn.com/docs/github-pages/)。

#### 问题二：安装 Jekyll  

如果你不需要在本地预览博客的效果，那么可以不用在本地安装 Jekyll。只需要按照 Jekyll 的规格要求，将文件上传到 GitHub 上，GitHub 会自动按照 Jekyll 风格展示效果。想在本地安装 Jekyll，参见[官方文档](http://jekyllcn.com/docs/installation/) 。

#### 问题三：文字排版

主要对文字、代码块、引用等做了修改。当看到喜欢的样式，查看`html`源码，把相应的部分抠出来。方式是有些低级。详细情况请查看[main.css](https://github.com/lninl/lninl.github.io/blob/master/css/main.css)文件。

### 标签功能 TODO

### 写在最后

我看到过很多漂亮也很完善的博客站点，也可以直接`clone`过来，但是有很多地方想要自己定制，所以自己做着。同时也想把各个功能的实现分开，方便更多的人按需定制。这个站点你可以随意使用。

### 参考文献
1. [Jekyll 中文网站](http://jekyllcn.com)
2. [ProGit 中文版](http://git.oschina.net/progit/)
3. [Creating and Hosting a Personal Site on GitHub](http://jmcglone.com/guides/github-pages/)

### TODO
个人能力有限，欢迎大家的修改和补充，让 Ta 更完善。有意者[@me](jiaxiangluke@163.com)

* 标签功能
* 留言功能-多说
* 搜索功能
* 区域划分

### 历程
* 2017-03-02：初稿
* 2017-03-18：完成排版
