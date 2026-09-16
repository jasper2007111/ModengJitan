# 摩登纪谭 - 一本开放的禅宗书籍

这是基于mdbook构建的一本关于禅宗系列文章的开放书籍。

### 问题
mdbook无法生成sitemap，原本使用了`mdbook-sitemap-generator`库，不过这个库的作者已经好久不更新了，在最新的Rust使用中会报错。最后从别人修改错误的一个库fork了一份，不过依然有错，所以现在使用的是我自己定制的[mdbook-sitemap-generator](https://github.com/jasper2007111/mdbook-sitemap-generator)。