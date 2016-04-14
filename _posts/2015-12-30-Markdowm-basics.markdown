---
layout: post
title:  "Markdown basics
date:   2015-12-30 22:12:44 -0800
categories: status post
---


This post contains details of platform used for this blog. My blog is hosted on github and served using jekyll.
Blog is written using redcarpet markdown.

Following is basic formatting.

## H2

### H3

#### H4

##### H5

###### H6

__I am bold__

**I am bold as well**

__I am bold _with italic_ mixed__

This is a ~~strikethrough~~ text

This is a [HyperLink](http://www.vikrant.info)

Following is an image.

![Elephant] (http://www.sabisabi.com/blog/wp-content/uploads/2013/01/Elephant-twins-3.jpg)

Lets check how code formatting work on this platform.

Following is C++ code

{% highlight C++ %}
#include <iostream>
using namespace std;
int main()
{
  cout<<"Hello World";
  return 1;
}
{% endhighlight %}


Followimg is java code

{% highlight java %}
public class HelloWorld {

    public static void main(String[] args) {
        // Prints "Hello, World" to the terminal window.
        System.out.println("Hello, World");
    }
{%endhighlight%}

Last, it is scala code
{% highlight scala %}
object HelloWorld {
  def main(args: Array[String]): Unit = {
    println("Hello, world!")
  }
}
{%endhighlight%}


Following Blogs were of great help to understand syntax

[blog1](http://milanaryal.com/2015/writing-on-github-pages-and-jekyll-using-markdown/)
[blog2](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

Some more links to read if you are interested
[Markdown inventor] (https://en.wikipedia.org/wiki/John_Gruber)

