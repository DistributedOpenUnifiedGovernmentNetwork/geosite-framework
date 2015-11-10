---
layout: wrapper_text
---
# [About Us]({{ site.baseurl }}/about) / [Stack]({{ site.baseurl }}/about/stack)

This framework uses Jekyll, Gulp, npm, less, and Bootstrap. 

## Jekyll

[geosite-framework]({{ site.code }}) uses [Jekyll](https://jekyllrb.com/) to template out most of the user interface.

## Gulp

[geosite-framework]({{ site.code }}) uses [Gulp](http://gulpjs.com/) to compile its source [less]({{ site.code }}/tree/{{ site.branch }}/src/less) and [javascript]({{ site.code }}/tree/{{ site.branch }}/src/js).  Gulp concats and compiles [less]({{ site.code }}/tree/{{ site.branch }}/src/less) into [css]({{ site.code }}/tree/build/css).  Gulp concats and uglifies [javascript]({{ site.code }}/tree/{{ site.branch }}/src/javascript).

## npm

[geosite-framework]({{ site.code }}) uses [npm](https://www.npmjs.com/) to manage [gulp dependencies]({{ site.code }}/blob/{{ site.branch }}/package.json#L20).

## less

[less](http://lesscss.org/) is a CSS pre-processor.  It is also used by [Bootstrap](http://getbootstrap.com/).

## Bootstrap

[Bootstrap](http://getbootstrap.com/) is a popular html/css framework.
