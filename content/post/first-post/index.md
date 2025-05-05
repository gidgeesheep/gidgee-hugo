---
date: '2025-05-01T13:33:26-04:00'
draft: false
title: 'Every blog starts somewhere...'
image: 
math: 
license: 
hidden: false

categories:

tags:

comments: true
draft: false

unsafe: true
---

# And this one starts here!
I'm constantly adding shit so who knows what you'll see next!
<p style="font-size: 5vw;">HELLO EVERYBODY!!!</p>
<img src="pim.gif" width=100% style="margin: 1; border-style:solid; border-color: white;   display: block; margin-left: auto; margin-right: auto;">


That doesn't nessesarily mean it's a [good](https://www.youtube.com/watch?v=dQw4w9WgXcQ&autoplay=1) post. It could suck! But we are `here` anyway, so welcome to the beginning of everything!

>this is not it my dude

```html
<br>
<img src="pim.gif">
```
<!-- This is modified in the stack theme to do some strange thing i don't want, specifically it adds a static layer on my gif that makes it ugly -->
<!-- ![pim](pim.gif "HELLOEVERYBODY") -->


<!-- 
I am trying to wrangle with what the fuck they hugo documentation says about resources
but it just ends up reading it as a <p> paragraph, i don't know what it wants
I think the $ is a way of saying this is a variable??
the := might be a pipe but i don't know
 .Resources.Get looks like a function name and it specifies with first letter capital for this local image, the global one was all lowercase
 i dont fucking get it

 ok so in the GO language, hugo does use $ to state the name of the variable, and the := is like an initialization, and = is like assignment 
 https://www.thenewdynamic.com/article/hugo-data/manipulation-and-logic-the-basics/
 
-->
<!-- {{ $pim := .Resources.Get "pim.gif" }} -->

<!-- 
this is raw html, and the renderer sees it, it seems to be intentionally ignoring it at render, i'll try to change the global .config for markup:goldmark:renderer:unsafe
into the true bool

the warning is gone now, but my html is not fixed yet
update: working good enough
-moved to top of screen

-->



