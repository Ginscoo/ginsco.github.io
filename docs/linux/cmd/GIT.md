## 记住密码
    # 全局设置
    git config --global credential.helper store
    # 单个项目
    cd ${project_dir}
    git config credential.helper store

## 常用命令

### 切换分支
    # 切换到新分支
    git checkout -b current_branch_name remote_branch_name
    
### 重新设置远程GIT仓库地址
    # 查看当前GIT仓库地址
    git remote -v
    # 重设GIT远程仓库地址
    git remote set-url origin ${remote_url}

### TAG
    # 查看tag
    git tag -l
    # 打tag
    git tag tag_name
    # 推送到远程
    git push --tags
