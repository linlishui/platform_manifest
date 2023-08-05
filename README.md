





Ubuntu下的AOSP源码下载：

- 新建一个工程目录。如：`mkdir aosp`
- 设置REPO_URL地址。如：`export REPO_URL="https://gerrit-googlesource.proxy.ustclug.org/git-repo"`
- 初始化仓库。如初始化指定分支的manifest配置：`repo init -u git@github.com:linlishui/platform_manifest.git -b android-12.0.0_r34`
- 同步源码树。`repo sync`