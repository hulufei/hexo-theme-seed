title: Tag Plugins
---

This post is used for testing tag plugins. See [docs](http://zespia.tw/hexo/docs/tag-plugins.html) for more info.

## Blockquote

### Normal blockquote

{% blockquote %}
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque hendrerit lacus ut purus iaculis feugiat. Sed nec tempor elit, quis aliquam neque. Curabitur sed diam eget dolor fermentum semper at eu lorem. 
{% endblockquote %}

### Quote from a book

{% blockquote David Levithan, Wide Awake %}
Do not just seek happiness for yourself. Seek happiness for all. Through kindness. Through mercy.
{% endblockquote %}

### Quote from Twitter

{% blockquote @DevDocs https://twitter.com/devdocs/status/356095192085962752 %}
NEW: DevDocs now comes with syntax highlighting. http://devdocs.io
{% endblockquote %}

### Quote from an article on the web

{% blockquote Seth Godin http://sethgodin.typepad.com/seths_blog/2009/07/welcome-to-island-marketing.html Welcome to Island Marketing %}
Every interaction is both precious and an opportunity to delight.
{% endblockquote %}

### Quote Chinese

中文引用文字效果：

{% blockquote From http://www.richyli.com/tool/loremipsum/ 亂數假文產生器 - Chinese Lorem Ipsum %}
工步他始能詩的，裝進分星海演意學值例道……於財型目古香亮自和這乎？化經溫詩。只賽嚴大一主價世哥受的沒有中年即病行金拉麼河。主小路了種就小為廣不？
{% endblockquote %}

## Code Block

### A normal code block

{% codeblock %}
alert('Hello World!');
{% endcodeblock %}

### Specify language

```objc
[rectangle setX: 10 y: 10 width: 20 height: 20];
```

### Add caption to code block

``` javascript Array.map
array.map(callback[, thisArg])
```

### Add caption with an optional URL

{% codeblock .compact http://underscorejs.org/#compact Underscore.js %}
.compact([0, 1, false, 2, '', 3]);
=> [1, 2, 3]
{% endcodeblock %}

## Pull Quote

This plugin helps you insert a pull quote in posts.

{% pullquote %}
Lorem ipsum dolor sit amet, consectetur adipiscing elit.
{% endpullquote %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas tempus molestie arcu, et fringilla mauris placerat ac. Nullam luctus bibendum risus. Ut cursus sed ipsum feugiat egestas. Suspendisse elementum, velit eu consequat consequat, augue lorem dapibus libero, eget pulvinar dolor est sit amet nulla. Suspendisse a porta tortor, et posuere mi. Pellentesque ultricies, mi quis volutpat malesuada, erat felis vulputate nisl.
