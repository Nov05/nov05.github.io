---
layout: post
title: Markdown Your Posts
subtitle: Each post could also have a subtitle
bigimg: /img/stars.jpg
gh-repo: daattali/beautiful-jekyll
gh-badge: [star, fork, follow]
tags: [tips]
comments: true
---

You can write regular [markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet "Markdown Cheatsheet") here and Jekyll will automatically convert it to a nice webpage.

**Here is some bold text.**  
*Here is some italic text.*  
~~Here is some strickthough text.~~

#### Here is a level 4 heading.  

Here is a useless table.  

| Number | Next number | Previous number |
| :------ |:--- | :--- |
| Five | Six | Four |
| Ten | Eleven | Nine |
| Seven | Eight | Six |
| Two | Three | One |

How about a picture?  

<img src="https://github.com/Nov05/nov05.github.io/blob/master/img/2019-06-15-markdown-your-posts/github-logo-icon-0.png?raw=true" width="200" height="200"/>

Here is a code chunk.  
~~~
var foo = function(x) {
  return(x + 5);
}
foo(3)
~~~

Here is the same code with syntax highlighting.  
```javascript
var foo = function(x) {
  return(x + 5);
}
foo(3)
```

Here is the same code yet again but with line numbers.  

{% highlight javascript linenos %}
var foo = function(x) {
  return(x + 5);
}
foo(3)
{% endhighlight %}

You can add notification, warning and error boxes like this.  

{: .box-note}
**Note:** This is a notification box.  

{: .box-warning}
**Warning:** This is a warning box.  

{: .box-error}
**Error:** This is an error box.   













