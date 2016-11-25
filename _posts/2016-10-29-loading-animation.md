---
layout:     post
title:      Loading Animation
date:       2016-10-29
summary:    Quick animation made with an imported SVG file and CSS animations.
categories: jekyll pixyll
image: "https://www.dropbox.com/s/ngxzppstzutktte/7.loading-animation.png?raw=1"
external-url: https://github.com/khari1090/30-30-projects/blob/master/7.loading-animation.html
---

## Goal
Get a css SVG animation to rotate from the center point. Today I was pretty busy so I can’t take on a more involved project.

## Result
It was actually pretty simple. I struggled with this a while back but the solution was `transform-origin: 50% 50%;`.

## Learned
How to use Transform origin and brushed up on my css keyframes for animation. There is no support for conical gradients in css and it’s extremely disappointing.

## Issues
As with any SVG drawing I make in Sketch, there are some things that need to be adjusted once you see how it works in browser. For example the radial gradient...wasn’t rendering at all in the browser so to remedy that I ended up just flattening that selection to bitmap.
