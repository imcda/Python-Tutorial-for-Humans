# 前言

本教程就是在 Git 的基础上完成的，因此我花了不少时间来学习 Git。

# 安装并与 Github 连接


# 常用操作
## 添加文件到缓存区
```
git add .
git add <filename>
```

## 提交文件
```
git commit -m '在这里添加描述'
```

## 推送到远程仓库
```
git push -u origin <分支名>
```

以本教程为例，我在`editing`分支做日常的编辑，因此我每次推送远程仓库是用：
```
git push -u origin editing
```

## 更新到主仓库
先切换到master分支
```
git swtich master
```
在对分支进行合并
```
git merge editing
```
这样，大家就可以在`master`分支看到最新版本了。

## 检查记录

```
git log --all --decorate --oneline --graph
```

# 真实案例

以 [Python-Tutorial-for-Humans](https://github.com/imcda/Python-Tutorial-for-Humans)

## 问题一：回退版本

当我开始尝试一些 Github 网页版的操作的时候，经常会对远程仓库造成改变，而我的本地仓库没有变化，这个时候就存在不一致的问题了。如果我尝试的结果，不是我需要的，我就会选择回退版本，方法如下：

1. 本地仓库同步拉取远程仓库

2. 本地仓库查看版本记录

执行
```
git log
```
可以得到需要回退版本的 hash value

3. 本地仓库执行回退版本

执行
```
git reset --hard XXXhash valueXXX
```

4. 本地仓库推送远程仓库

执行
```
git push -f
```

用`-f`的原因是，本地目前跟远程是不一致的，但是你希望远程跟本地一样，因此这样操作。

**思考**
写到这里，我发现一个问题，如果我不拉取，不回退，直接 force push 是不是也可以，也就是在目前只有我修改了一处，又只有我在push的情况下比较合适，否则，还是要同步拉取一下远程仓库比较合适，看看到底要要回退到哪个版本。


## 问题二：多了一个提问模板

我通过页面操作新增一个提问模版


editing 分支没有 merge master 分支。

在编辑过 editing 分支后，回到 master 分支，使用 merge，需要输入 merge 的理由，然后 merge 成功后