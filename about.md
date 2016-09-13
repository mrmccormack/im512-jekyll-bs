---
layout: default
title: 'About'
active: 'hi'

---

<!--  http://stackoverflow.com/questions/23935062/jekyll-github-pages-how-to-hide-a-post -->
<!-- published: false works with pages and posts, doesn't just hide -->

# This was updated on Mac at  home **TEST**

```c

#include <stdio.h>
int main(){
 printf("Hello Drone\n");
 return 0;
}
```


```html
<h1>Hello World!</h1>
```

<h1>test</h1>

```php
<?php

class Hello extends World
{
}
```

<h1>another</h1>



{% highlight ruby linenos %}
def foo
  puts 'foo'
end
{% endhighlight %}




<h1>Sure to get to work</h1>

~~~ html
<a href="#">Hello world</a>
<img src="asdf" alt="">

~~~


Some information about you! <strong> HEY! </strong> xxx

![](https://mrmccormack.github.io/images/shrek.jpg )

---

    {% if page.title == "Home" %}
# {{ page.title }}  This is <h4>HOME</h4> &middot; {{ site.tagline }}
    {% else %}
# {{ page.title }} This is NOT <h4>HOME</h4> &middot; {{ site.title }}
    {% endif %}

---

## With script tag

<script src="https://gist.github.com/VirtuaCreative/ef47c25b7f8933dd78fcb0f848464dde.js"></script>

<h1>Sure to get to work</h1>

`​`` html
<a href="#">Hello world</a>
`​``

## With liguid tag



{% gist VirtuaCreative/ef47c25b7f8933dd78fcb0f848464dde %}

---
# ANother attempt at code highlighting

{% highlight ruby %}
def show
  @widget = Widget(params[:id])
  respond_to do |format|
    format.html # show.html.erb
    format.json { render json: @widget }
  end
end
{% endhighlight %}


---

``` ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html


```

---

# More highlighing, this should work
 
``` ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html

```


``` html
<a href="#"><i class="fa fa-facebook"></i></a>
<a href="#"><i class="fa fa-twitter"></i></a>
<a href="#"><i class="fa fa-linkedin"></i></a>
<a href="#"><i class="fa fa-github"></i></a>

```

---

<div class="highlighter-rouge">
<pre class="highlight">
  <code>
    <span class="kd">var</span> <span class="nx">s</span> <span class="o">=</span> <span class="s1">'Hi'</span><span class="p">;</span>
  </code>
</pre>
</div>


---

Happy fun highlighting. 
[More details](https://github.com/mojombo/jekyll/wiki/liquid-extensions)

{% highlight ruby %}
def foo
  puts 'foo'
end
{% endhighlight %}

---

<iframe src="https://www.google.com/maps/d/embed?mid=1ELysbd_HcyENvsuK5auBFbFpwZ0" width="640" height="480"></iframe>
---

### More Information

A place to include any other types of information that you'd like to include about yourself.

### Contact me

[email@domain.com](mailto:email@domain.com)

---
<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2648.7897440927322!2d-89.27185718378226!3d48.40298077924549!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x4d5921d099e9d447%3A0x2fdeb4b250a8e1a8!2sConfederation+College!5e0!3m2!1sen!2sca!4v1473528846687" width="600" height="450" frameborder="0" style="border:0" allowfullscreen></iframe>
