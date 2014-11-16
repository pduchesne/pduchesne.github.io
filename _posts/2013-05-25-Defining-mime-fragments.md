---
layout: post
title: "Media fragments : extension and implementation"
description: An attempting at extending mediafragment syntax to new mime types and implementing them
tags: fragments, javascript
type: post
published: false
comments: true
---

Following a [paper](http://www.w3.org/2013/04/odw/odw13_submission_28.pdf) presented at the recent W3C [Open Data on the Web](http://www.w3.org/2013/04/odw/) workshop, here's some more information about the javascript implementation of the mediafragments codec library.


  {% highlight ruby linenos %}
  def show
    puts "Outputting a very lo-o-o-o-o-o-o-o-o-o-o-o-o-o-o-o-ong lo-o-o-o-o-o-o-o-o-o-o-o-o-o-o-o-ong line"
    @widget = Widget(params[:id])
    respond_to do |format|
      format.html # show.html.erb
      format.json { render json: @widget }
    end
  end
  {% endhighlight %}