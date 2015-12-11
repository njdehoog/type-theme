---
layout: post
title: Markdown and HTML
---

Spelt supports the use of [Markdown](http://daringfireball.net/projects/markdown/syntax) with inline HTML tags which makes it easier to quickly write posts with Spelt, without having to worry too much about text formatting. A sample of the formatting follows.

Tables have also been extended from Markdown:

First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell

Here's an example of an image, which is included using Markdown:

![Geometric pattern with fading gradient](/img/sample_feature_img_2.png)

Syntax highlighting is done using [highlight.js](https://highlightjs.org/):

```js
// count to ten
for (var i = 1; i <= 10; i++) {
    console.log(i);
}

// count to twenty
var j = 0;
while (j < 20) {
    j++;
    console.log(j);
}
```

Type Theme uses KaTeX to display maths. Equations such as {% katex inline:true %}S_n = a \times \frac{1-r^n}{1-r}{% endkatex %}
 can be displayed inline.

Alternatively, they can be shown on a new line:

{% katex %}
f(x) = \int \frac{2x^2+4x+6}{x-2}
{% endkatex %}

