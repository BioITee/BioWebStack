# Hugo 版 WebStack 主题

本项目是基于**纯静态**的网址导航网站 [webstack.cc](https://github.com/WebStackPage/WebStackPage.github.io) 制作的 [Hugo](https://gohugo.io/) 主题，其中部分代码参考了以下几个开源项目：<br/>

- [https://github.com/liutongxu/liutongxu.github.io](https://github.com/liutongxu/liutongxu.github.io)
- [https://github.com/iplaycode/webstack-hugo](https://github.com/iplaycode/webstack-hugo)

<br/>

主题安装后，将 exampleSite 目录下的文件复制到 hugo 站点根目录，根据需要把 config.toml 的一些信息改成自己的，导航的网址信息可通过 data 目录下 webstack.yml 修改。

具体执行步骤如下：

- 克隆仓库

```
$ git clone https://github.com/shenweiyan/webstack-hugo.git
```

- 进入 exampleSite 目录执行 hugo server

```
$ cd webstack-hugo/exampleSite/
$ hugo server --themesDir ../..

# 如果你知道你的公网 ip, 如下面的 132.76.230.31, 可以使用下面的方式执行 hugo server
$ hugo server --baseUrl=132.76.230.31 --bind=0.0.0.0 --themesDir ../..
```

这是一个开源的公益项目，你可以拿来制作自己的网址导航，也可以做与导航无关的网站。

WebStack 有非常多的魔改版本，这是其中一个。如果你对本主题进行了一些个性化调整，欢迎来本项目中 issue 分享一下！

<br/>

### 主题开源地址

[https://github.com/shenweiyan/webstack-hugo](https://github.com/shenweiyan/webstack-hugo)

<br/>

### 主题演示地址

- [https://nav.bioitee.com](https://nav.bioitee.com)
- [https://shenweiyan.github.io/webstack-hugo](https://shenweiyan.github.io/webstack-hugo)

