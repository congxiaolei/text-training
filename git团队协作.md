- 管理员远程创建仓库
- 管理员本地创建目录/仓库
- 使用vs打开目录：code .
- 创建文件：touch README.md
- 初始化：git init
- 查看状态：git status
- 放到缓存区：git add --all
- 再查看一次：git status，变成绿色
- 提交：git commit -m "the first commit"
- 查看分支：git branch（仓库的名称是origin，默认的分支是master）
- 查看commit历史记录：git log --oneline
- 本地指向到远程：git remote add origin ...test.git
- 查看本地的远程指向：git remote -v
- 推送：git push origin master（如果当前账号不是管理员，需要在远程设置协助人）


> 删除本地仓库并拷贝远程仓库

- 回退到本地仓库目录的上一级
- 删除仓库目录：rm -rf VS CODE
- 拷贝远程仓库：git clone 