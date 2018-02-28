---
layout: post
title:  "Jekyll Introduction"
date:   2018-02-27 21:55:06 +0900
categories: Jekyll
---
## Layout

```html
<!DOCTYPE html>
<html>
{% raw %} {% include head.html %} {% endraw %}
<body>
{% raw %} {% include header.html %} {% endraw %}
<div id="content">
{% raw %}    {{ content }} {% endraw %}
</div>
{% raw %} {% include footer.html %} {% endraw %}
</body>
</html>
```

## How-To

* [How to override defualt theme][Jekyll-doc-overriding-theme]!
* [How to Add Bootstrap4 to Jekyll][jekyll-add-bootstrap4-how-to]
* [HenryThemes][jekyll-henrythemes]

[Jekyll-doc-overriding-theme]: https://jekyllrb.com/docs/themes/#overriding-theme-defaults

[jekyll-add-bootstrap4-how-to]:https://simpleit.rocks/how-to-add-bootstrap-4-to-jekyll-the-right-way/

[jekyll-henrythemes]:https://github.com/henrythemes