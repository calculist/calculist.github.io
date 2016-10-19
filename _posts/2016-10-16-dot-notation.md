---
layout: post
title:  "Dot Notation"
date:   2016-10-16 00:00:00 -0700
author: Dan Allison
---

There's a new feature in Calculist that allows you to reference values at different points of the hierarchy in a simple and intuitive way.

```
parts
  hubs [:] 39
  spokes [:] 14
  rims [:] 50
  tires [:] 20
  handlebars [:] 48
  frame [:] 380
  fork [:] 40
  seat [:] 33
wheels [=] parts.hubs + parts.rims + parts.spokes + parts.tires
```

[Read more](https://github.com/calculist/calculist/wiki/Computation#accessors) on the GitHub wiki.
