---
title: First Post
author: David Hintelmann
date: 2023-08-16
description: "This is my first blog post."
tags: ["Markdown", "LaTeX","KaTeX"]
---
{{< katex >}}
# First Blog Post

Hello my name is David Hintelmann and this is my personal website using [Hugo](https://gohugo.io/) with [Blowfish Theme](https://blowfish.page/).

I will be creating content for [python](https://www.python.org/) and [go](https://go.dev/) programming languages.
Additionally, there will be guides for various tech related goodies.

## Markdown Sample

**Lorem ipsum** dolor sit amet, consectetur adipiscing elit. Nam tristique ullamcorper dui. Nam a sem risus. Nullam tincidunt a eros nec faucibus. Proin lectus felis, pharetra ac pretium non, imperdiet quis ligula. Morbi non laoreet leo. Nunc scelerisque vulputate nunc, eget euismod dolor ornare in. Proin quis fringilla ligula. Etiam ac sem ligula. Suspendisse commodo non dolor sit amet pharetra. Suspendisse non tellus mattis dolor efficitur sollicitudin lobortis et lacus. Morbi et massa sed ipsum consequat blandit eget porta neque. Fusce lobortis aliquet urna, dapibus molestie nunc. Nulla elementum id orci et sollicitudin. Proin in elit porta, feugiat turpis eget, pretium magna.


## Basics of Markdown

Below are a few examples of creating bold and italic text, and other simple formatting tricks.

**bold text**

*italic text*

***bold and italic***

~~strikethrough~~

Here is a **block quote** for quoting text:

> "History never repeats itself, but it does often rhyme" - Mark Twain

Another way to write a **block quote**:

    "Not all those who wander are lost" - J.R.R. Tolkein

Example for quoting a **code block**:

Some basic Git commands are:
```
git status
git add
git commit
```

## Code and Syntax Highlighting

**Syntax highlighting**

*javascript*

``` js
var foo = function (bar) {
  return bar++;
};

console.log(foo(5));
```

*python*

``` python
import pandas as pd

df = pd.read_csv("sample.csv")
```

*go*

``` go
package main

import "fmt"

func main() {
	fmt.Println("Hello World")
}
```

### More Code and Syntax Highlighting

```
Inline `code` has `back-ticks around` it.
```

Inline `code` has `back-ticks around` it.

```c#
using System.IO.Compression;

#pragma warning disable 414, 3021

namespace MyApplication
{
    [Obsolete("...")]
    class Program : IInterface
    {
        public static List<int> JustDoIt(int count)
        {
            Console.WriteLine($"Hello {Name}!");
            return new List<int>(new int[] { 1, 2, 3 })
        }
    }
}
```

```css
@font-face {
  font-family: Chunkfive; src: url('Chunkfive.otf');
}

body, .usertext {
  color: #F0F0F0; background: #600;
  font-family: Chunkfive, sans;
}

@import url(print.css);
@media print {
  a[href^=http]::after {
    content: attr(href)
  }
}
```

```javascript
function $initHighlight(block, cls) {
  try {
    if (cls.search(/\bno\-highlight\b/) != -1)
      return process(block, true, 0x0F) +
             ` class="${cls}"`;
  } catch (e) {
    /* handle exception */
  }
  for (var i = 0 / 2; i < classes.length; i++) {
    if (checkCondition(classes[i]) === undefined)
      console.log('undefined');
  }
}

export  $initHighlight;
```

```php
require_once 'Zend/Uri/Http.php';

namespace Location\Web;

interface Factory
{
    static function _factory();
}

abstract class URI extends BaseURI implements Factory
{
    abstract function test();

    public static $st1 = 1;
    const ME = "Yo";
    var $list = NULL;
    private $var;

    /**
     * Returns a URI
     *
     * @return URI
     */
    static public function _factory($stats = array(), $uri = 'http')
    {
        echo __METHOD__;
        $uri = explode(':', $uri, 0b10);
        $schemeSpecific = isset($uri[1]) ? $uri[1] : '';
        $desc = 'Multi
line description';

        // Security check
        if (!ctype_alnum($scheme)) {
            throw new Zend_Uri_Exception('Illegal scheme');
        }

        $this->var = 0 - self::$st;
        $this->list = list(Array("1"=> 2, 2=>self::ME, 3 => \Location\Web\URI::class));

        return [
            'uri'   => $uri,
            'value' => null,
        ];
    }
}

echo URI::ME . URI::$st1;

__halt_compiler () ; datahere
datahere
datahere */
datahere
```

For **linking to a website** [Google](https://www.google.ca).

## Photography - Images

**Images** - [Philip Oroni Photography](https://unsplash.com/@philipsfuture)

[![Philip Oroni Photography](https://images.unsplash.com/photo-1691083055814-f2ead870d97d?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1932&q=80 "Purple thing")](https://images.unsplash.com/photo-1691083055814-f2ead870d97d?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1932&q=80)

**Relative link** for linking to files with folder path or images.

[Philip Oroni Photography](https://unsplash.com/@philipsfuture)

[![Philip Oroni Photography](img/image-Philip-Oroni.png "Red thing")](img/image-Philip-Oroni.png)

To do list:

  - [x] Take out trash
  - [ ] Vacuum
  - [ ] Dance

## Table, Math, Lists

**Table**

| Index | Value1 | Value2 |
| :---- | :----: | -----: |
| 1     |  Cat   |  small |
| 2     |  Dog   |  small |
| 3     |  Dog   |  large |

**Math - LaTeX**

$$
\frac{e^2}{\lambda^4}
$$

Maecenas pretium imperdiet malesuada. Aliquam placerat scelerisque est, sit amet bibendum odio hendrerit quis. Suspendisse potenti. Praesent nec porta est. Sed lobortis nibh vel porttitor ultrices. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia curae; Suspendisse a sem mi. 

--------

Example of **unordered list**:

    - item one
    - item two
    - item three

Another example of **unordered list**:

    * item one
    * item two
    * item three

Example of **ordered list**:

    1. item one
    2. item two
    3. item three


## Footnotes

More information on [footnotes](https://github.com/markdown-it/markdown-it-footnote) plugin for `markdown-it` markdown parser.

```
Footnote 1 link[^first].

Footnote 2 link[^second].

Inline footnote^[Text of inline footnote] definition.

Duplicated footnote reference[^second].

[^first]: Footnote **can have markup**

    and multiple paragraphs.

[^second]: Footnote text.
```

Footnote 1 link[^first].

Footnote 2 link[^second].

Inline footnote^[Text of inline footnote] definition.

Duplicated footnote reference[^second].

[^first]: Footnote **can have markup**

    and multiple paragraphs.

[^second]: Footnote text.

------

## Create HTML or PDF File with pandoc

Open terminal in the directory where there are markdown files, with file extension .md

### HTML

```
pandoc example.md --mathjax -s -o example.html
```

### PDF

```
pandoc example.md --pdf-engine=xelatex -o example.pdf
```

## YouTube Videos

```
[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg)](http://www.youtube.com/watch?v=YOUTUBE_VIDEO_ID_HERE)
```

[![IMAGE ALT TEXT HERE](img/otto-von-bismarck-yt.png)](https://www.youtube.com/watch?v=zc3Y-dU_GjM&pp=ygURT3R0byB2b24gQmlzbWFyY2s%3D)
