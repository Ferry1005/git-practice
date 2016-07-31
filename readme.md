Git 小组练习

##命令

1. 克隆项目
```bash
git clone [url]
```

2. 添加到缓存
添加所有修改
```bash
git add -A
```
或添加指定文件
```bash
git add [url/文件名]
```

3. 推送到本地仓库
```bash
git commit -m '注释内容'
```

4. 从远程仓库拉取分支
```bash
git pull [分支名]
```
例如：
```bash
git pull origin master
```
```bash
git pull origin dev
```

5. 推送到远程仓库
```bash
git push [分支名]
```
例如：
```bash
git push origin master
```
```zsh
git push origin dev
```


查看状态
```bash
git status
```
##分支
查看分支
```bash
git branch
```
注： 星号（*）代表当前分支


创建分支
```bash
git branch [分支名]
```

切换分支
```bash
git checkout [分支名]
```