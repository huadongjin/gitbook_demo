# GitBook&GitBook Editor介绍


###GitBook介绍
> GitBook 是一个命令行工具（也是 Node.js 库），让你能够使用 GitHub/Git 和 Markdown 构建出美丽的书籍，可以包含互动的练习。GitBook 支持使用多种语言构建书籍。GitBook被广泛运用于技术文档的编写。具体gitbook的介绍可见：[gitbook介绍](https://github.com/GitbookIO/gitbook)


GitBook支持输出多种文档格式，如：
* 静态站点：GitBook默认输出该种格式，生成的静态站点可直接托管搭载Github Pages服务上；
* PDF：需要安装gitbook-pdf依赖；
* eBook：需要安装ebook-convert；
* 单HTML网页：支持将内容输出为单页的HTML，不过一般用在将电子书格式转换为PDF或eBook的中间过程；
* JSON：一般用于电子书的调试或元数据提取。


[GitBook项目官网](http://www.gitbook.ioGitBook)   [Github地址](https://github.com/GitbookIO/gitbook)
###客户端GitBook Editor介绍

* 类似于Github，有版本控制。就是一个电子书版的Github。
* Gitbook Editor是一个很好用的Markdown编辑器，有很多贴心的快捷键让你发掘，比如cmd+shift+d，如果你用习惯Atom、Sublime、Textmate之类的编辑器，会很喜欢这些特性。当然此类快捷键也不是很多，但是相信以后Editor功能会更加丰富，因为我刚才说的这个特性应该也是新加的。起码比Logdown这个Markdown编辑器好用多了。


###GitBook 如何安装
gitbook是命令行工具，我们先搭建环境：

1.Node.js安装
Node.js是一个基于Chrome JavaScript运行时建立的一个平台，用来方便地搭建快速的，易于扩展的网络应用。Node.js借助事件驱动，非阻塞I/O模型变动轻量和高效，非常适合 run accoss distributed devices的data-intensive的实时应用。

登录Node.js[官网](http://www.nodejs.org/),下载安装包并安装。
安装好后请校验对应的版本。

```bash
node -v
```

有对应的版本提示说明安装成功。
node版本可通过版本管理器进行管理（nvm或者n),NVM的全称就是Node Version Manager,是一个简单的bash脚本用来管理系统中已经存在的多个Node.js版本。
对于管理node版本用NVM还是n的问题，可参见[node管理](http://web.jobbole.com/84249/)

2.GitBook安装
GitBook是从NMP上安装的，命令行：
```bash
npm install gitbook -g
```
安装好之后，检验下是否安装成功
```
gitbook -V
20.4.2
```
如果看到类似的版本信息，表示已成功安装GitBook.

3.calibre安装
这个鬼东西负责各种电子书的转换，我搞了两小时一直不生效。果断搁置先。
calibre是个开源的一站式电子书解决方案，GitBook会用到其中ebook-convert功能组件来完成书籍格式的转换。

登录官网http://www.calibre-ebook.com/,选择对应的平台进行安装。


###GitBook Editor安装
这个是个客户端，安装好马上可用。
GitBook Editor实际上就是个特殊的Markdown编辑器。可以选择新建或者导入本地的gitbook。一般会有如下三个文件/文件夹
* _book 文件夹
* SUMMARY.md
* README.md
在gitbook editor里面你只要编辑README.md文件即可，其他两个文件都是自动会生成和填充的。







