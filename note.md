# 添加远程仓库
    git remote add <repo nicknane> <repo url>

# 修改已有远程地址(一般是https改为ssh)
    git remote set-url <repo nickname> <new repo url>

# 修改本地分支名称
    git branch -m <new name>

## 修改 git 配置，让以后的默认初始化分支都为 main
    git config --global init.defaultBranch main