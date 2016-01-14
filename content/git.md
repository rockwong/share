#git使用教程

###Rockwong

---

##安装

[Git官网下载地址](http://git-scm.com/download)

[图形化工具Sourcetree](https://www.sourcetreeapp.com/)

---

##创建新仓库

Sourcetree: 点击 “+ 新仓库”   <!-- .element: class="fragment" data-fragment-index="1" -->

![git init](images/git/git-init.jpg) <!-- .element: class="fragment" data-fragment-index="2" -->

命令行：    <!-- .element: class="fragment" data-fragment-index="3" -->


```
    $ git init
```
<!-- .element: class="fragment" data-fragment-index="4" -->

---


##添加和提交

Sourcetree: 勾选 “未暂存文件”，并填写提交信息。   <!-- .element: class="fragment" data-fragment-index="1" -->

![git init](images/git/git-commit.jpg) <!-- .element: class="fragment" data-fragment-index="2" -->

--
命令行：

```
    $ git add --all
    $ git commit -m 'add: git.html#/3 添加和提交'
```
<!-- .element: class="fragment" data-fragment-index="3" -->
--


---

## 推送提交
Sourcetree: 点击推送，勾选分支 <!-- .element: class="fragment" data-fragment-index="1" -->
![git init](images/git/push.jpg) <!-- .element: class="fragment" data-fragment-index="1" -->

命令行：<!-- .element: class="fragment" data-fragment-index="2" -->

```
    $ git push origin master
```
<!-- .element: class="fragment" data-fragment-index="2" -->

---

## 获取提交
Sourcetree: 点击拉取 <!-- .element: class="fragment" data-fragment-index="1" -->
![git init](images/git/pull.jpg) <!-- .element: class="fragment" data-fragment-index="1" -->

命令行：<!-- .element: class="fragment" data-fragment-index="2" -->

```
    $ git pull
```
<!-- .element: class="fragment" data-fragment-index="2" -->

---

## 如何编写一个良好的提交信息

提交的动作 + 修改的位置 + 修改的说明 <!-- .element: class="fragment" data-fragment-index="1" -->
Note:
    Tip:不要填写无意义或空白的提交信息。

--
    ##提交的动作

    * `update` / 更新     <!-- .element: class="fragment" data-fragment-index="1" -->
    * `add` / 新增<!-- .element: class="fragment" data-fragment-index="1" -->
    * `polish` / 改进     <!-- .element: class="fragment" data-fragment-index="1" -->
    * `fix` / 修复        <!-- .element: class="fragment" data-fragment-index="1" -->
--
     ##修改的位置

     * slide1 <!-- .element: class="fragment" data-fragment-index="1" -->
     * homepage <!-- .element: class="fragment" data-fragment-index="1" -->
     * login.html  <!-- .element: class="fragment" data-fragment-index="1" -->
--
    ##修改的说明

    * 去掉多余图片 <!-- .element: class="fragment" data-fragment-index="1" -->
    * 更换最新版Jquery库 <!-- .element: class="fragment" data-fragment-index="1" -->
    * 新增登录页面  <!-- .element: class="fragment" data-fragment-index="1" -->
--
## 示例

![git init](images/git/commit-info.jpg)

```
add : slide1 red done

fix: 拖拽窗口页面混乱的问题

update: 更改jquery 插件版本

polish: pop重构 统一风格减少代码

```

---

#没有Git服务器？

[Coding](https://coding.net/) 国内速度快、免费 、稳定性稍差

<!-- .element: class="fragment" data-fragment-index="1" -->

[Bitbucket](https://bitbucket.org/) 国外速度稍慢、免费

<!-- .element: class="fragment" data-fragment-index="2" -->

[Github](http://github.com/) 私有库收费

<!-- .element: class="fragment" data-fragment-index="3" -->

---

#Github Pages

用来制作个人网站和项目网站 <!-- .element: class="fragment" data-fragment-index="1" -->


---

#创建一个Github Page

创建一个仓库名称为： username.github.io


---

#绑定域名

在项目的根目录下建立一个文件：CNAME

```
域名.com
```

域名解析到 username.github.io 即可


---

##推荐git小游戏

[githug](https://github.com/Gazler/githug)

[游戏秘籍](http://www.jianshu.com/p/482b32716bbe)
<!-- .element: class="fragment" data-fragment-index="1" -->

---

#thanks!





