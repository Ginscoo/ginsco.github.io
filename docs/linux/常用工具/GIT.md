## 记住密码
    # 全局设置
    git config --global credential.helper store
    # 单个项目
    cd ${project_dir}
    git config credential.helper store