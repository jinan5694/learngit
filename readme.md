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
### 删除分支
```
git branch -d <branch_name>
```
### 合并分支的另一种方式
```
// 这样合并可以保留提交点
git merge --no-ff -m <message> <branch_name>
```
### stash 储藏当前工作现场
```
// save
git stash
// query
git stash list
// reset
git stash apply
git stash drop
// reset and remove
git stash pop
```
### 删除分支，强制删除分支
```
git branch -d <branch_name>
git branch -D <branch_name>
```

### 删除未暂存（stage）的文件
#### 查看未暂存的文件
  ```
  git clean -n
  ```
  #### 删除未暂存的文件
  ```
  git clean -f
  ```

  #### 删除未暂存目录（包括目录里的文件）
  ```
  git clean -fd
  ```
