可以参考 <https://gohugo.io/getting-started/quick-start/>

# 安装

可以直接从 github releases 下载：<https://github.com/gohugoio/hugo/releases/tag/v0.123.6>

Hugo 是用 Go 写的，所以只需要单个可执行文件。

# 新建 Post

```
hugo new content posts/[FILENAME].md
vim content/posts/[FILENAME].md
```

# 预览

```
hugo server
```

# 发布

生成静态文件
```
hugo
```

直接提交到这个仓库，会自动发布到 Github Pages。