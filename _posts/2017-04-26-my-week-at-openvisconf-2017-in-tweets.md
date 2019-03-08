---
title: My week at OpenVisConf 2017 in tweets – or, how I learned to stop hating and
  be okay with Tableau
date: '2017-04-27T03:28:00.000+00:00'
comments: true
excerpt: I never thought I'd be so **basic** as to use Tableau Public, but it's important to keep in mind the end goal of data visualization is insight, not technology or tools.
---

```javascript    
  var divElement = document.getElementById('viz1495814399289');  
  var vizElement = divElement.getElementsByTagName('object')[0];                   
  if ( divElement.offsetWidth > 800 ) { 
    vizElement.style.minWidth='324px';
    vizElement.style.maxWidth='654px';
    vizElement.style.width='100%';
    vizElement.style.minHeight='629px';
    vizElement.style.maxHeight='929px';
    vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
  } else if ( divElement.offsetWidth > 500 ) { 
    vizElement.style.minWidth='324px';
    vizElement.style.maxWidth='654px';
    vizElement.style.width='100%';
    vizElement.style.minHeight='629px';
    vizElement.style.maxHeight='929px';
    vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
  } else {
    vizElement.style.minWidth='324px';
    vizElement.style.maxWidth='654px';
    vizElement.style.width='100%';
    vizElement.style.minHeight='629px';
    vizElement.style.maxHeight='929px';
    vizElement.style.height=(divElement.offsetWidth*1.77)+'px';
  }    
  var scriptElement = document.createElement('script');    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';   
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
```
*I never thought I'd be so **basic** as to use Tableau Public, but it's important to keep in mind the end goal of data visualization is insight, not technology or tools.*

Visualization, at its heart, is about insight and storytelling, *not* <a href="http://dataviz.tools">tools</a>. But ask most anyone who's ever worked with me what I think of one particular tool called <a href="http://public.tableau.com">Tableau Public</a>, and they'll quickly tell you it is a tool I'm quick to criticize. I don't like its proprietary, closed-source model, its lack of adherence to web standards or its lack of support for full responsiveness.

But, if we really get back to what the fundamental essence of data visualization is, it shouldn't matter so much what *tools* we use so much as it does what *visual insight* we glean and how *accessible* that insight is to the intended audience. 

In my defense, my high-level data viz snobbery of vendor lock-in and freemium tools such as Tableau has frequently been on-point, especially when it comes to *accessibility* of visual insights to users of *all* devices. Up until its latest version, Tableau offered virtually <a href="https://cmtoomey.github.io/responsive/2015/11/18/responsiveresponse.html">no configuration whatsoever even to build adaptive visualizations</a>, much less visualizations that could be remotely considered responsive (<a href="https://www.tableau.com/about/blog/2016/8/tips-designing-device-specific-dashboards-make-everyone-happy-57548">"device-specific dashboards"</a> is the marketing lingo Tableau touted upon its latest release, which means the visualization designer had to create separate dashboards for different device sizes). So, in that sense, at least, my begrudgery of Tableau was warranted. Right? Let's keep in mind quotation from the legendary Ben Schneiderman Bostock mentions at the beginning of his talk:

> "The purpose of visualization is insight, not pictures." -Ben Schneiderman

Sure, on the surface, Bostock's comments can be taken as the now cliche Tufte-esque quip for higher "data-to-ink" ratios and less decorative embellishments. I'm afraid, however, that wasn't the point Bostock was making.

Let's keep in mind Mike Bostock's words-of-wisdom in his keynote on <a href="http://d3.express">d3.express,</a> a notebook-style interface for d3.js programming: 

> Code is often the best tool we have because it is the most general tool. -Bostock

And therein lies the reason for much of my heretofore disdain for B.I. apps such as Tableau. But just because Tableau abstracts code with 'drop-down menus' doesn't have value whatsoever. As Bostock reminds us, "Code has come a long way, but it's still far from human-friendly."

Which got me thinking more deeply about what it means to be 'human-friendly.' Certainly, Tableau must have something going for it in the HCD arena or else it wouldn't enjoy such ad nouveau popularity. So, when a dataset of tweets from the conference flashed in a notification on my screen, I figured I'd see if I could, in less than 15 minutes, visualize the dataset in a meaningful way that conveyed a narrative, afforded user interaction and was *accessible* to users of all screen sizes. While I'd normally reach for a d3 plugin like `d3.treemap` or `d3.circle' and spend roughly 30-45 minutes building a bespoke visualization, I found myself, as a new user of Tableau, quickly producing precisely what I'd envisioned well within my 15-minute time constraint. Did I inherently limit the expressiveness of what I *might* have created using code alone? Certainly. But I also accomplished the goal that, as Schneiderman reminds us, is the ultimate goal of visualization: insight.

So, I no longer *hate* Tableau. That has very little to do with the multitude of things I learned at OpenVis, but it, to me, was a central theme surrounding many of the talks. What is the purpose of visualization? Innovation for innovation's sake or insight?

And I now – without feeling like I've 'cheated' – can say I put Tableau to use:


-CVL
