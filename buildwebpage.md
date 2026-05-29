# 本地构建网页：

## 安装 Ruby
sudo apt update & sudo apt install ruby-full build-essential zlib1g-dev
## 安装 Bundler
gem install bundler
cd homepage
## 安装项目依赖
bundle install
## 构建网页
bundle exec jekyll build
## 本地预览
bundle exec jekyll serve --no-watch
## webpage位置
build 后网页资源内容都在 _site 目录中
