---
layout: post
title: What do i do in my free time ?
subtitle: There's lots i do !
gh-badge: [star, fork, follow]
tags: [test]
comments: false
mathjax: false
author: Aloysius
---

{: .box-success}
This is a post to show you (the reader) what i spend my free time doing when i am bored or when i have not much to do.

**What do i dabble in?**

## Programming/coding

In my free time , i have touched on coding/programming . Mainly kali linux and python . The reason i got interested in coding/programming is due to my curiosity on how everything works . For example , when i see my computer screen , i wonder how pixels are displayed on the screen or how i am even able to see the screen. 

Here's a few projects i have made by my own through online resources: 


A calculator coded through python

![Crepe](https://beautifuljekyll.com/assets/img/crepe.jpg)

A hash maker : 



etc etc etc.



Here's the code for the calculator

~~~
var foo = function(x) {
  return(x + 5);
}
foo(3)
~~~

And here is the same code with syntax highlighting:

```javascript
var foo = function(x) {
  return(x + 5);
}
foo(3)
```

And here is the same code yet again but with line numbers:

{% highlight javascript linenos %}
var foo = function(x) {
  return(x + 5);
}
foo(3)
{% endhighlight %}

## Boxes
You can add notification, warning and error boxes like this:

### Notification

{: .box-note}
**Note:** This is a notification box.

### Warning

{: .box-warning}
**Warning:** This is a warning box.

### Error

{: .box-error}
**Error:** This is an error box.

## Local URLs in project sites {#local-urls}

When hosting a *project site* on GitHub Pages (for example, `https://USERNAME.github.io/MyProject`), URLs that begin with `/` and refer to local files may not work correctly due to how the root URL (`/`) is interpreted by GitHub Pages. You can read more about it [in the FAQ](https://beautifuljekyll.com/faq/#links-in-project-page). To demonstrate the issue, the following local image will be broken **if your site is a project site:**

![Crepe](/assets/img/crepe.jpg)

If the above image is broken, then you'll need to follow the instructions [in the FAQ](https://beautifuljekyll.com/faq/#links-in-project-page). Here is proof that it can be fixed:

![Crepe]({{ '/assets/img/crepe.jpg' | relative_url }})
