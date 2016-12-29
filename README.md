&gt;技术文档中心介绍

\#\#\#技术文档中心

当前wd的文档中心，不能满足专业性质的技术文档编写。在对MD、插图等编辑手段方面不够友好。某些技术文章编写后可以直接对外，故搭建技术文档中心，便于大家协作。

gitbook 介绍：\[https:\/\/github.com\/GitbookIO\/gitbook\]gitbook





\#gitbook写技术文档的有点

使用gitbook写Api文档，我总结了几个优点：

* 类似于Github，有版本控制。就是一个电子书版的Github。
* Gitbook Editor是一个很好用的Markdown编辑器，有很多贴心的快捷键让你发掘，比如cmd+shift+d，如果你用习惯Atom、Sublime、Textmate之类的编辑器，会很喜欢这些特性。当然此类快捷键也不是很多，但是相信以后Editor功能会更加丰富，因为我刚才说的这个特性应该也是新加的。起码比Logdown这个Markdown编辑器好用多了。
* 一次编写，多处使用。接下来我们重点说这个，也就是我今天重点要说的。

### **一次编写，多处使用。**

现在是移动互联网时代，很多App已经开发在维护，还有很多很多的App待开发，而且HTML5、js mvc框架的发展，有很多人都在维护Api接口。那么写一个可维护、可读性高、带版本控制、可随心所欲分发的接口文档是多么重要。

#### **可读性\/ 可维护 \/ 版本控制**

Gitbook是用Markdown写的，还支持语法高亮等，用它写出来的文档，那看起来是相当愉悦的。

Gitbook正是天生带版本控制，你可以选择任意一个你发布过的版本。

#### **可随心所欲分发**

1. 文档写好以后，你可以把Gitbook源目录下面的所有文件都复制到你项目下\(app\_root\/docs\/api\/gitbook\_api\_dir\)。这样，你的项目就多了一份漂亮的文档，开发人员还可以在本地打开Web Preview生成在\_book目录下的静态网页愉悦的看你的Api接口文档。 如果觉得复制太土了，你可以直接把Gitbook Editor的Api文档目录创建在项目中。

2. 后台接口项目、Android App项目、iOS App项目都可以分发一份，大家可以使用Gitbook Editor来协同管理接口。

3. 上传到Github，也可以在线修改阅读你的文档，因为Github也支持Markdown。


