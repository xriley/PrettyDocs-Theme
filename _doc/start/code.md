---
title: Code
sections:
- HTML
- CSS
- LESS
- Sass
- JavaScript
- Python
- PHP
- Handlebars
- Git
---

[PrismJS](http://prismjs.com/) is used as the syntax highlighter here.
You can [build your own version](http://prismjs.com/download.html) via their website should you need to.


<div class="callout-block callout-success"><div class="icon-holder">*&nbsp;*{: .fa .fa-thumbs-up}	
</div><div class="content">
{: .callout-title}
Useful Tip:

You can use this online [HTML entity encoder/decoder](https://mothereff.in/html-entities)
to generate your code examples.

</div></div>


{: #html}
###### HTML Code Example

```html
<!DOCTYPE html>
<html lang="en">
    ...
    <div class="jumbotron">
        <h1>Hello, world!</h1>
        <p>...</p>
        <p><a class="btn btn-primary btn-lg" href="#" role="button">Learn more</a></p>
    </div>
    <div class="jumbotron">
        <h1>Hello, world!</h1>
        <p>...</p>
        <p><a class="btn btn-primary btn-lg" href="#" role="button">Learn more</a></p>
    </div>
    ...
</html>
```


{: #css}
###### CSS Code Example

```css
/* ======= Base Styling ======= */
body {
    font-family: 'Open Sans', arial, sans-serif;
    color: #333;
    font-size: 16px;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
}
```


{: #less}
###### LESS Code Example

```css
/*
* Template Name: prettyDocs - Responsive Website Template for documentations
* Version: 1.0
* Author: Xiaoying Riley
* License: Creative Commons Attribution 3.0 License
* Twitter: @3rdwave_themes
* Website: http://themes.3rdwavemedia.com/
*/
@import "mixins.less";
@import "theme-default.less";
@import "base.less";
@import "doc.less";
@import "landing.less";
@import "responsive.less";
```


{: #sass}
###### Sass Code Example

```sass
#main {
    $width: 5em;
    width: $width;
}

#sidebar {
    width: $width;
}
```


{: #javascript}
###### JavaScript Code Example

```javascript
<script>
    function myFunction(a, b) {
        return a * b;
    }

    document.getElementById("demo").innerHTML = myFunction(4, 3);
</script>
```


{: #python}
###### Python Code Example

```python
>>> x = int(input("
Please enter an integer: ")) Please enter an integer: 42
>>> if x < 0:
... x = 0
... print('Negative changed to zero')
... elif x == 0:
... print('Zero')
... elif x == 1:
... print('Single')
... else:
... print('More')
... More
```


{: #php}
###### PHP Code Example

```php
<?php
$txt = "Hello world!";
$x = 5;
$y = 10.5;

echo $txt;
echo "<br>";
echo $x;
echo "<br>";
echo $y;
?>
```


{: #handlebars}
###### Handlebars Code Example

```handlebars
Handlebars.registerHelper('list', function(items, options) {
  var out = "<ul>";

  for(var i=0, l=items.length; i<l; i++) {
    out = out + "<li>" + options.fn(items[i]) + "</li>";
  }

  return out + "</ul>";
});
```


{: #git}
###### Git Code Example

```shell
$ git add Documentation.txt
```
