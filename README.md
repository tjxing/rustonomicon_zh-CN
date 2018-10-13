# Rust死灵书

《Rust死灵书 - Rust高级与非安全程序设计》(Rustonomicon)的简体中文翻译版。

原文链接：<https://doc.rust-lang.org/nomicon/>  
原文Repository：<https://github.com/rust-lang-nursery/nomicon>

## 注意

**《Rust死灵书》的原文还处于不稳定状态（而且由于涉及到Rust许多新的和不稳定的功能，极可能长期都保持不稳定状态），官方声明可能含有过时或错误的内容。而译本不保证随原文实时更新，部分章节可能存在更大的滞后性。**

当前的译本是基于2018年9月3日的原文版本翻译和校对的。

## Build

构建本文档需要[mdbook](https://github.com/azerupi/mdBook)。

安装mdbook：

```
$ cargo install mdbook
```

构建本文档：

```
$ cd rustonomicon_zh-CN
$ mdbook build
```

最终结果会输出到`book`子目录中，可以用浏览器打开book/index.html文件查看。
