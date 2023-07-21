# Seminar Homepage

蛤蛤！我现在来教你了。

首先，学习下这个：<https://www.jekyll.com.cn/>
我们这东西啊，是基于这个：<https://github.com/tuna/tuna.moe>


## 安装
假设你是ubuntu：

```sh
sudo apt install gem
```
.bashrc 里面加上：

```sh
### WARNING: FOR GEM!!!
export PATH=$HOME/.gem/ruby/2.7.0/bin:$PATH
export BUNDLE_PATH=$HOME/.gem
export GEM_PATH=$HOME/.gem
```

git clone这个仓库，然后在这个仓库的文件夹下执行这个：
```sh
gem install --user bundler jekyll
bundle install
bundle update
bundle exec jekyll serve
```



如果要部署，那么

```sh
bundle exec jekyll build
```
生成的东西会在 _site 下，然后想干嘛干嘛！
