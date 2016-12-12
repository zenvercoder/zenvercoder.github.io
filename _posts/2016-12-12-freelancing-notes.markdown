---
layout: post
title:  "Cool line"
date:   2016-11-19 13:26:00 -0700
categories: cli
---

`du -h ./ | grep '^\s*[0-9\.]\+G' | sort -nr`

If you're running out of space on your machine, type this line into the terminal

This line says:
"disk usage human readable write input to output, search for anything of size Gigabyte or larger and arrange it with biggest at the top"

du - display disk usage
h - human readable
./ - this directory
| - pipe (write input to output)
grep - file pattern searcher
'^\s*[0-9\.]\+G' - a bunch of regex
-nr - numerically ordered r for reverse, biggest at the top
