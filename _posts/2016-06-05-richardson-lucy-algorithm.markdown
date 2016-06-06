---
layout: post
title:  "Richardson Lucy in ArrayFire"
date:   2016-06-05 17:00:00 -0500
---

This update is long, long overdue.

This article is the first in a series describing image deconvolution performance on integrated graphics versus CPU. The catch is I’m not even talking about performance quite yet – this article focuses on developing a correct algorithm within the ArrayFire framework.

The idea was to present the algorithm implementation and performance analysis in a single article, but by the end of March I realized that the performance story warranted an article of its own. I wrote a draft describing the implementation of Richardson-Lucy, had it peered reviewed, then let it sit around for two months while I tried to keep the rest of my life in order.

But no more, it’s time to get the ball rolling. I really wanted to have the article embedded into the webpage, but it really is time to put something out there and move it. So here it is in it’s full, PDF glory:

[Richardson-Lucy Deconvolution in ArrayFire](/resources/richardsonLucy/algorithmReport.pdf)

And source code:
[Source](https://github.com/logik1286/richardsonLucyArrayFire)
