<h1 align="center">怎么在这个网站上写一篇文章</h1>

[直接访问我的博客](https://yyyhat.github.io/my_blog/)


### 1、从 Github 上拉取整个工程
```
git clone --recurse-submodules https://github.com/yyyhat/my_blog.git
```

### 2、安装 Hugo
```
winget install Hugo.Hugo.Extended
```

### 3、进入工程目录并启动网站
```
cd my-blog
hugo server -D
```

### 4、多台电脑一同创作写之前请同步
```
git pull
git submodule update --init --recursive
```


