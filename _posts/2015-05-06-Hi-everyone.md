---
layout: post
title: Hello Everyone!
tags: [GSoC-2015,jekyll]
---

This maybe my first post here and as you can guess by now, I am very new to jekyll and it has infact baffled me to a great extent. This theme that you see in infact the third theme that I have decided to use after failing miserably with others
{% highlight ruby %}
def show
  @widget = Widget(params[:id])
  respond_to do |format|
    format.html # show.html.erb
    format.json { render json: @widget }
  end
end
{% endhighlight %}
