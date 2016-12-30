# 第二部分

在体验Gitbook Editor的时候碰到以下几个问题点：

### gitbook editor 问题点：

* 同步到的是远程的git仓库，不能马上本地生效，需要pull下来才行；
* 因为是提交到远程仓库，所以提交过程比较慢；
* 提交到远程仓库，如果多人协作不太好； 另外，对于gitbook，如果多个部门维护同一份，直观性不强。建议每个部门单独维护一份，如，recomm-docs.xxx.net, fe-docs.xxx.net 然后把各自的域名拉出来建个目录。 

### 关于保存

在gitbook editor中编辑好保存的文章按如下步骤可以立即生效：

1.本地已经build过并起了对应的web服务，假设我本地有gitbook_demo,经过gitbook build和gitbook serve .,通过浏览器访问localhost:4000即可访问，默认端口是4000，如下：cd到gitbook_demo目录下

```bash
 $ gitbook build 
info: 7 plugins are installed
info: 6 explicitly listed
info: loading plugin "highlight"... OK
info: loading plugin "search"... OK
info: loading plugin "lunr"... OK
info: loading plugin "sharing"... OK
info: loading plugin "fontsettings"... OK
info: loading plugin "theme-default"... OK
info: found 4 pages
info: found 1 asset files
info: >> generation finished with success in 1.4s !
```

```bash
 $ gitbook serve . 
Live reload server started on port: 35729
Press CTRL+C to quit ...

info: 7 plugins are installed
info: loading plugin "livereload"... OK
info: loading plugin "highlight"... OK
info: loading plugin "search"... OK
info: loading plugin "lunr"... OK
info: loading plugin "sharing"... OK
info: loading plugin "fontsettings"... OK
info: loading plugin "theme-default"... OK
info: found 4 pages
info: found 1 asset files
info: >> generation finished with success in 1.5s !

Starting server ...
Serving book on http://localhost:4000
```
然后通过浏览器访问http://localhost:4000 可看到自己编辑的文章。

