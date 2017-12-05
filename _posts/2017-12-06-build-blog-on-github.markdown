# 如何搭建一个基于github与jekyll的blog

# Step1: 申请一个github-pages blog

新建一个仓库，名字为`yourname.github.io`, github会自动生成blog结构

# Step2: 在本地搭建一个jekyll环境

1. 首先安装ruby

2. 安装jekyll

```gem install jekyll```

3. 创建一个新的路径用来创建本地的blog的文章

```
   mkdir -p ~/blog 
   cd ~/blog
   jekyll new .

```
4. 开启jekyll服务，在本地预览

```
   cd ~/blog
   jekyll serve

```

在浏览器中输入` 127.0.0.1:4000` 就可以看到如下效果：

[](./jekyll_init.png) 

# Step3: 进行一些简单的配置
修改blog的名称，个人信息等，都可以在_config.yml中设置。
```
title: <title>
email: <email>
description: 
github_name: <github_username>
```

在index页面也可以增加excerpt文章简介功能。
在`index.html`中的`site.pages`这一行下增加一行`{{ post.excerpt}}`

# help

[github help about jekyll](https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/)
