---
layout: post
title: Dynamic Memory 101
date: 2017-07-19T13:30:00.000Z
author: Jospeh Kossmann
categories:
  - Dungeon Death
  - Snake
  - CLASSIFIED
  - CLASSIFIED
  - CLASSIFIED
img: post01.jpg
thumb: c_thumb.jpg
published: true
---

<b>Dungeon Death</b> 

Been having issues with both github and the


#### Why do we use it?



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


