# markdown2slides
Tools for converting Markdown Source File to Reveal.js HTML5 slides

## Usage:

在这个文件夹下，使用`python3 md2slide.py xxx.md`来将markdown文件转换成html文件。

在config中修改配置：

```
{
  "revealjs_export_dir": "export",
  "author_name_english": "Huanyu Wang",
  "author_name_chinese": "王环宇",
  "revealjs_theme": "white",
  "revealjs_transition": "convex"
}
```

Theme修改主题内容， 可选主题在https://github.com/hakimel/reveal.js#theming中查看。



### Theming

The framework comes with a few different themes included:

- **black**: Black background, white text, blue links (default theme)
- **white**: White background, black text, blue links
- **league**: Gray background, white text, blue links (default theme for reveal.js < 3.0.0)
- **beige**: Beige background, dark text, brown links
- **sky**: Blue background, thin dark text, blue links
- **night**: Black background, thick white text, orange links
- **serif**: Cappuccino background, gray text, brown links
- **simple**: White background, black text, blue links
- **solarized**: Cream-colored background, dark green text, blue links



### Transition Styles

+ None
+ Fade
+ Slide
+ Convex
+ Concave
+ Zoom