
> 管理员操作

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
- 管理员添加团队成员



> 团队成员操作

- 团队人员设置公钥：把本地C:\Users\lenovo\.ssh中的id_rsa.pub中的公钥复制到远程管理后台的设置中去
- 拷贝远程仓库：git clone
Administrator@47.103.61.198:darren/test.git
- 修改文件
- git add--all
- git commit -m ""
- git push origin master
- 拉取另一个团队成员的东西：git pull origin master
  

> 团队协作重要的一句话：先pull（拉取，保持更新）再push 





> 删除本地仓库并拷贝远程仓库

- 回退到本地仓库目录的上一级
- 删除仓库目录：rm -rf VS CODE
- 拷贝远程仓库：git clone 