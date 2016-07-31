##Git 小组练习
---

##资源
* [官方教程](https://git-scm.com/book/zh/v2)
* [廖雪峰git教程](http://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000)
* [Markdown语法](http://www.jianshu.com/p/q81RER)
---

##申明：

1. 所有文件命名请用英文！
2. 所有`commit`操作一定要添加注释内容（内容需与所推送内容相关）!

---

##git操作说明
1. 开发新功能先切到`dev`分支, 若不存在`dev`分支，则从`master`切个`dev`分支 `git checkout -b dev`
2. 从`dev`分支切个新功能分支 `git checkout -b feature/功能名(请用英文)`
3. 新功能开发完后，申请把`新功能分支`合并到`dev`分支
4. 小组确认无误后，申请把`dev`合并到`master`
5. 删除`dev`

---

##基础命令

1. 克隆仓库
```bash
git clone [url]
```
例如：
```bash
git clone git@github.com:Ferry1005/git-practice.git
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

3. 提交到本地仓库
```bash
git commit -m '注释内容'
```
> 第2步和第3步可合并命令为 `git commit -a -m '注释内容'`

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
```bash
git push origin dev
```


- 查看状态
```bash
git status
```

---

##分支

- 查看分支
```bash
git branch
```
注： 星号（*）代表当前分支


- 创建分支
```bash
git branch [分支名]
```

- 切换分支
```bash
git checkout [分支名]
```

##其他

- 查看配置信息
```bash
git confit --list
```

- 查看帮助
```bash
git help
```
- 查看某条命令的帮助信息
```bash
git help <verb>
git <verb> --help
man git-<verb>
```

##查看已缓存和未缓存的改动内容
- 查看尚未缓存的改动内容
```bash
git diff
```

- 查看已经缓存的改动内容
```bash
git diff --staged
```
