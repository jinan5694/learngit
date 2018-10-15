### 关联一个远程仓库的命令
```
git remote add origin https://github.com/jinan5694/learngit.git
```
### 提交代码到github，我是master code
```
git push origin master
```
## 分支
### 创建分支
```
git branch dev
git checkout dev
// or
git checkout -b dev
```
### 查看当前分支
```
git branch
```
### 切换分支
```
git checkout branch_name
```
### 合并分支,命令用于合并指定分支到当前分支
```
git merge <branch_name>
```
### 删除分支，制造一些冲突内容
```
git branch -d <branch_name>
```
### dev