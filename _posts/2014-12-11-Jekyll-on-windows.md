---
layout: post
title:  "Jekyll on Windows error"
date:   2014-01-02 21:30:26
comments: true
tags: dxartist_blog
archive: false
---
I'm not going to explain the process of setting up Jekyll in Windows. There are a lot of other blogs have already done it. I'm just trying to explain a common error we see while using Jekyll on Windows.

Whenever you are trying to build a jekyll site or editing the forked repository locally, you may face this issue.

<pre>
C:\Users\rdquintas\Desktop\jek\zrq>jekyll build
Configuration file: C:/Users/rdquintas/Desktop/jek/zrq/_config.yml
            Source: C:/Users/rdquintas/Desktop/jek/zrq
       Destination: C:/Users/rdquintas/Desktop/jek/zrq/_site
      Generating...
  Liquid Exception: cannot load such file -- yajl/2.0/yajl in _posts/2014-05-21-
welcome-to-jekyll.markdown
</pre>
