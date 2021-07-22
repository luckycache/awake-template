---
title: "Ghostbusters "
subtitle: That’s a big twinkie
category:
  - About Awake
author: Craig
date: 2021-07-22T14:05:33.084Z
featureImage: /uploads/home-hero.jpg
---
Awake is fast for a couple different reasons. It both capitalizes on the platform it's built for (JAM Stack) and the framework it's built on  use it, but that's as easy as adding it to an array in `config/modules.js` like so: 

```
 icons: ['faTimes', 'faSearch', 'faEnvelope', 'faUser', 'faBriefcase']
```

## Lazy Loading Like Crazy

In order to speed up both compile time and page load time, basically everything but the header, footer, hero, and main content of the posts are lazy loaded. All grids are lazy loaded with infinite scroll and all images (feature images and those in posts) are also lazy loaded. Comments can be lazy loaded or loaded on click of "Show Comments" button.

## Pretty Stinkin' Fast, I'd Say

I've taken a number of steps to try and make Awake as fast and snappy as possible for the end user and I think you'll find it's been handled fairly well. Last I ran one of the posts through Page Speed Insights I got a 99 score for desktop and 89 for mobile. [Give it a try for yourself!](https://developers.google.com/speed/pagespeed/insights/?url=https%3A%2F%2Fawake-template.netlify.com%2Fpost-markup-and-formatting%2F&tab=desktop)

![Page speed insights score 99!!](/uploads/page-speed-insights.jpg)