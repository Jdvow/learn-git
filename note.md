# 添加远程仓库
    git remote add <repo nicknane> <repo url>

# 修改已有远程地址(一般是https改为ssh)
    git remote set-url <repo nickname> <new repo url>

# 修改本地分支名称
    git branch -m <new name>

# 修改 git 配置，让以后的默认初始化分支都为 main
    git config --global init.defaultBranch main

# 推送到远程仓库
    git push <repo name> <branch name>
    note:
    1，确保本地更新已经提交；
    2，远程仓库未被修改过，如果已经被修改，需要先将远程仓库的内容同步到本地。

# 拉取远程仓库代码
    git pull <repo name> <branch>
    