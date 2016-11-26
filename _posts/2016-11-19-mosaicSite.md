---
layout:     post
title:      Mosaic Site
date:       2016-11-19
summary:    Landing Page.
categories: jekyll pixyll
image: "https://www.dropbox.com/s/e1x4vn2gcf4raov/28.mosaicSite.png?raw=1"
external-url: https://github.com/khari1090/30-30-projects/blob/master/28.mosaicSite.html
---

## Goal
Make a nice mosaic landing page.

## Result
It’s nice. At first i didn’t know how to incorporate JS into the equation as basically everything i did was achieved through HTML/CSS but I ended up adding in a GIF and making it’s placement variable. On refresh you should see that the ocean water gif will fill a different cell each time. It’s getting harder and harder to make projects but this one made me happy. As a designer I needed to make something pretty. Don’t worry, I’m not completely obsessed with Pharrell although it probably seems like it...

## Learned
I learned that I can make the item in a loop a single random number. I learned that embedding gifs is child's play. I learned that `:hover` is not really something I know how to control other than by hovering over the element in question.

## Issues
I am not sure but I am pretty convinced that `:hover` is not really something I know how to control other than by hovering over the element in question. What do I mean? I mean that I don’t know how to make it so that hovering over the “Media” link in the nav bar will trigger the `:hover` state of the corresponding element. I could have made all new classes I suppose but I wanted to reuse the overlay again and again to keep the CSS short. In the past I have experimented with appending classes and I actually *SUCCESSFULLY* did that today but it doesn’t work with `:hover`, only with `.hover`. These are not the same thing. `:hover` is the hover state and `.hover` is an additional class that I now know I can easily toggle with JS. Previously, i’ve been trying to toggle `:hover` to no avail and it was wildly disappointing. Now I understand that it wasn’t my method but, rather, WHAT I was trying to manipulate.
