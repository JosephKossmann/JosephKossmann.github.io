---
layout: post
title: Dungeon Death
date: 2017-10-12T15:20:00.000Z
author: Jospeh Kossmann
categories:
  - Snake
  - CLASSIFIED
  - CLASSIFIED
  - CLASSIFIED
img: post01.jpg
thumb: c_thumb.jpg
published: true
---

<b>Dungeon Death</b> 

Been having issues with github, but slowly working through it, plan to lay down the basics from the tutorials whilst changing it in my own way, have yet to decide what exactly to focus on.


img: Pixel fire.gif



#### How do we use it?
```C++
int  static_int  = 2;
int* dynamic_int = new int(2);
```

#### How do we free it?
```C++
if ( dynamic_int )
{ 
  delete dynamic_int;
  dynamic_int = nullptr;
}
```
