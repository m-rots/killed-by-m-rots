+++
title = "Project Stream"
date = 2020-07-25

[extra]
killed = "July 2020"
+++

I have never liked Plex. The way it forces transcodes by default, the fact that you have to run a server and the restriction of solely serving content from one location.

I thought I could do better. Project Stream was a resource-efficient application which ran on CloudFlare Workers initially. It connected straight to Google Drive and was able to proxy content effortlessly to clients such as Kodi and Infuse. All while costing about $5 a month to run.

However, it was uncertain whether CloudFlare would allow their Workers platform to proxy terabytes of media streams. Therefore, I switched over to a self-host-able model which allowed Project Stream to run on cheap cloud servers and Raspberry Pis. While it did work, the TypeScript codebase was far from perfect and the opinionated API made it difficult to use existing Shared Drives. This second iteration of Project Stream died in November 2019.

Finally, with the rise of Bernard in June 2020, I rewrote Project Stream in the language of Go. I spent a lot of time tweaking its proxy capabilities to make this rewrite the most memory efficient version of Project Stream yet. In addition, I tried to tackle the API flaws of the previous iteration. However, I soon realised that a perfect API was hard to realise without having full control over the client. Hacks had to be implemented to speed up many operations which led to an even worse API design.

Project Stream's last commit was on the 25th of July 2020.

<!-- more -->