iojs-cn articles site
=======
This branch contains the articles written or translated by iojs-cn.

目录规范
----------
- 翻译的文章内容发布到 `articles/_posts` 中，周报发布到 `weekly/_posts` 中。文章的文件名格式为 YYYY-m-d-title.md，如 2012-12-2-how-to-contribute.md，内容格式为：

      ---
      layout: post
      title: io.js 如何在一天时间内吸引 146 人参与，被翻译成 27 种语言？
      author: mikeal
      reference: https://medium.com/@mikeal/65e5b1c49a62
      ---

      {{正文内容}}

   其中 `author` 和 `reference` 表示文章的原作者和出处。

- 文章图片放在相应目录的 `images` 子目录下的与标题同名目录中，如 `articles/images/2012-12-2-how-to-contribute/1.png`

- 提交 Pull Request 前推荐先在本地预览最终效果。方式为在项目根目录中（切换到 `gh-pages` 分支）：
    1. 执行 `$ gem install github-pages` 以安装 Jekyll 和相关插件；
    2. 运行网站 `jekyll serve`，jekyll 会自动监控文件的变化
    3. 访问 http://0.0.0.0:4000/iojs-cn 来查看效果
