# 第二部分


在体验Gitbook Editor的时候碰到以下几个问题点：

 ###gitbook editor 问题点：
* 同步到的是远程的git仓库，不能马上本地生效，需要pull下来才行；
* 因为是提交到远程仓库，所以提交过程比较慢；
* 提交到远程仓库，如果多人协作不太好； 另外，对于gitbook，如果多个部门维护同一份，直观性不强。建议每个部门单独维护一份，如，recomm-docs.xxx.net, fe-docs.xxx.net 然后把各自的域名拉出来建个目录。 


###关于保存
在gitbook editor中编辑好保存的文章按如下步骤可以立即生效：

1.本地已经build过并起了对应的web服务，假设我本地有gitbook_demo,经过gitbook build和gitbook serve .,通过浏览器访问localhost:4000即可访问，默认端口是4000，如下：
```bash
gitbook build
```

![gitbook build](https://pan.baidu.com/disk/home#list/vmode=grid&path=%2F%E5%B7%A5%E4%BD%9C%E7%94%A8%E5%9B%BE%2FGitBook_pic)

