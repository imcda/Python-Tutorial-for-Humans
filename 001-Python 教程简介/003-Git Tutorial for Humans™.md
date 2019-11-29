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