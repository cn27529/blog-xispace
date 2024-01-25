# hexo-blog

Build hexo blog for My blog, And other include transfer my google blogger and transfer log work

# use rss to hexo \_posts .MDs

```bash
https://hexo.io/zh-tw/docs/migration
```

# create a hexo blog

```bash
hexo init blog
```

# cd to your a blog folder

```bash
$ cd blog/
```

# install hexo-mirateor-rss in your blog folder

```bash
npm install hexo-migrator-rss --save
```

# defind your a blogger rss url and props, ex: this a url

```bash
https://blog.xispace.app/feeds/posts/default?alt=rss&max-results=500

```

# hexo magrate rss

```bash
hexo migrate rss 'https://blog.xispace.app/feeds/posts/default?alt=rss&max-results=10000'
```

# deploy to

deploy to https://github.com/cn27529/blog-xispace.git repo on https://blog.xispace.app/ site source from https://github.com/cn27529/hexo-blog.git
