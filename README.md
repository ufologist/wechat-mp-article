# wechat-mp-article
高颜值的微信公众号图文消息排版

## 使用手册
* [微信公众号图文消息默认样式](https://ufologist.github.io/wechat-mp-article/index.html)

  微信公众号的图文消息编辑器中提供了一般的富文本编辑功能, 例如粗体, 斜体, 颜色, 背景等等, 但默认的样式排版下不太适合阅读大段文字. 另外还提供了引用(`<blockquote>`)和表格(`<table>`)的默认样式.
* [高颜值的微信公众号图文消息排版](https://ufologist.github.io/wechat-mp-article/readability.html)

  使用了适合中文排版的 CSS 样式库, 让微信公众号图文消息阅读起来赏心悦目.

  基于 [typo.css](https://github.com/sofish/typo.css) 和 [Entry.css](https://github.com/zmmbreeze/Entry.css) 来实现排版效果, 例如 [typo.css 排版实例](http://typo.sofi.sh/#section2), [博文demo](http://zencode.in/Entry.css/demo.html), [散文demo](http://zencode.in/Entry.css/word.html)

  另外由于非常喜欢[WeicoNote](https://itunes.apple.com/us/app/weiconote-tu-wen-bian-ji-chuan/id1072357511?mt=8)简洁的编辑风格, 也做了些借鉴, 让写文章的时候可以更关注内容而非排版.

* [高颜值的微信公众号图文消息编辑器](https://ufologist.github.io/wechat-mp-article/editor.html)

  基于[Mditor](https://github.com/Houfeng/mditor)做了一个 markdown 的编辑器. 你可以使用这个编辑器来编写公众号图文消息, 编写完后全选右边的内容复制到公众号的图文消息编辑器中即可.

## 填过的坑
* 样式中不要有字体设置, 否则复制到图文消息的编辑器中, 会造成样式被丢弃
* 复制嵌套多级的 `ul/ol` 结构到图文消息的编辑器中, 会变成最多只有两级的结构
* `pre` 内容复制到图文消息编辑器中没有保留换行, 会造成所有内容都挤成一行