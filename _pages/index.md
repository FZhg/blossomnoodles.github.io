---
layout: defaults/page
permalink: index.html
narrow: true
---

{% include components/intro.md %}

[More about Bryan.]({{ site.baseurl}}{% link _pages/about.md %})

### What else?

Bryan keeps him busy learn Machine Learning, Computer Vision, and algorithms. During his study journey, he will inevitably have something to say. [His posts is here]({{ site.baseurl }}{% link list/posts.html %}). There's also a projects page about  [Machine Learning he has completed]({{ site.baseurl }}{% link list/projects.md %}).

Bryan wants to share his GRE Analytical Writing Essay, which he wrote for practice [Browse it here.]({{ site.baseurl }}{% link list/portfolio.html %})

Bryan has posted ***tutorial to install Cuda9.0, Cudnn7.0 and Tensorflow on Ubuntu 18.04***.[This tutorial is here]({{ site.baseurl }}{% link _posts/2018-4-30-ubuntu-18.04-cuda-installation.md %}) There's the three most-recent posts below, or here's [all posts by year.]({{ site.baseurl }}{% link list/posts.html %})

<div class="card mb-3">
    <img class="card-img-top" src="/theme/img/cat.jpg">
    <div class="card-body bg-light">
        <div class="card-text"> A picture bryan took when he was playing with the school stray cat</div>
    </div>
</div>

### Recent Posts

{% for post in site.posts limit:3 %}
{% include components/post-card.html %}
{% endfor %}


