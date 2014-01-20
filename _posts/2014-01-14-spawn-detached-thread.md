---
layout: post
title: spawn_detached_thread
allsummary: ancient C code
githubrepo: [gw_malloc, CServer]
---
This was one of my favourite C functions ever. I don't remember when I first wrote it but I think
I recreated it at least a couple of times on different projects (possibly for different employers):

<script src="https://gist.github.com/adsgray/8364610.js"></script>

I'd use it to spawn a *pthread* thread which would go and do something that might take a while and whose
result I didn't care about. 

I found some of this code (complete with original README, ca. 2000 A.D.) on an old hard drive and put it into a respository imaginatively named [CServer](https://github.com/adsgray/CServer) as
it is TCP server code written in C.

