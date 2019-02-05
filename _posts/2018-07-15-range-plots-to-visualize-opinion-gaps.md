---
title: Range plots ≠ dot plots
date: '2018-07-14'
comments: true
excerpt: >-
  Range plots always have seemed a bit elitist to me. It's one of *those* types
  of charts that people who want to show how skilled they are at visualization
  use.
published: true
---

<p><iframe id="datawrapper-chart-q9mVW" src="//datawrapper.dwcdn.net/q9mVW/1/" scrolling="no" frameborder="0" allowtransparency="true" style="width: 0; min-width: 100% !important;" height="462"></iframe><script type="text/javascript">if("undefined"==typeof window.datawrapper)window.datawrapper={};window.datawrapper["q9mVW"]={},window.datawrapper["q9mVW"].embedDeltas={"100":902,"200":630,"300":535,"400":518,"500":462,"700":462,"800":437,"900":423,"1000":406},window.datawrapper["q9mVW"].iframe=document.getElementById("datawrapper-chart-q9mVW"),window.datawrapper["q9mVW"].iframe.style.height=window.datawrapper["q9mVW"].embedDeltas[Math.min(1e3,Math.max(100*Math.floor(window.datawrapper["q9mVW"].iframe.offsetWidth/100),100))]+"px",window.addEventListener("message",function(a){if("undefined"!=typeof a.data["datawrapper-height"])for(var b in a.data["datawrapper-height"])if("q9mVW"==b)window.datawrapper["q9mVW"].iframe.style.height=a.data["datawrapper-height"][b]+"px"});</script></p>
<p>
<em>Range plots – those charts with the fancy lines in them depicting a bucket of possible values – have always seemed overused and unnecessarily ornamental for my tastes. But I was confusing range plots with something else: dot plots!</em></p>

### LESSON I LEARNED TODAY
Contrary to my assumption all these years, a [range plot](https://academy.datawrapper.de/article/111-how-to-create-a-range-plot) is **not** the same thing as a [dot plot](https://en.wikipedia.org/wiki/Dot_plot_(statistics)). The former is a relatively new type of chart, while the latter was first popularized by [William Cleveland](https://en.wikipedia.org/wiki/William_S._Cleveland) in the 19th century as an alternative to the bar chart.

### WHAT I HATE ABOUT DOT PLOTS
What's the point of a dot plot when a bar chart works just as well and allows for greater precision? Defenders of the dot plot [may contend](http://www.maartenlambrechts.com/2015/05/03/to-the-point-7-reasons-you-should-use-dot-graphs.html) that the dot plot allows for a finer degree of granularity than a bar chart would, a point which I won't refute. But that was in the era of static print charts. We now live in an era of interactive graphics where we can get 'details on demand' by mouseover events and touch gestures.

For a good visual of the root of my disdain for dot plots, see the figure below. Sure, it communicates a great degree of information. But I'm drowning in complexity!

![](http://www.maartenlambrechts.com/assets/dotplot_eurostat.png)

*Dot plots like this are just too much!*

### WHAT I LIKE ABOUT RANGE PLOTS 
Range plots provide a novel way of visualizing our era of stark polarization. Sometimes called 'gap charts,' they allow us at a glance to get an understanding of the gulf in value between two variables.
