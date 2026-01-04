[![MyAutoTask](https://github.com/1614229511/blabalink_daliy/actions/workflows/main.yml/badge.svg)](https://github.com/1614229511/blabalink_daliy/actions/workflows/main.yml)
# 作用
进行10个点赞, 五个帖子浏览, 之后领取每日奖励
登录的是blablalink繁体中文网页
# 用法
- Git clone项目后, pip install -r requirement安装依赖
- 配置环境变量运行, pycharm运行需要带环境变量ACCOUNT, PASSWORD, 区服只适配了日本/韓國/北美/東南亞/全球
- py main.py执行
# Github Actions自动执行用法
点按钮：点击 "Use this template" 创建你自己的仓库。
填密码：去你新仓库的 Settings -> Secrets and variables -> Actions。
加变量：点击 "New repository secret"，添加 ACCOUNT 和 PASSWORD。
点启动：去 Actions 检查是否识别到了main.yml文件，然后手动运行测试。
